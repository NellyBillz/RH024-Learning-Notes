# 08. Organizing local users and groups

## What I learned

A user has a numeric UID and belongs to a primary group plus optional supplementary groups. Groups make shared access easier to manage. Local account information is listed in `/etc/passwd` and `/etc/group`.

## Key idea

`id` and `getent` inspect identities. `useradd`, `groupadd`, `usermod`, and `passwd` change accounts and need administrator access. Never commit `/etc/shadow` or password data.

## Commands to explore

```bash
id
getent passwd "$(id -un)"
getent group "$(id -gn)"
```

## Practice

Find your UID, primary GID, and supplementary groups. On a disposable VM, optionally create a practice group and user, then verify with `id`.
