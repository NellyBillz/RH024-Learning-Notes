# 10. Managing software and updates

## What I learned

RHEL installs software as RPM packages and uses DNF to resolve repositories and dependencies. Keeping packages updated can include security and bug fixes.

## Key idea

Inspect packages first. Installation and upgrades require administrator rights and can alter the machine; try them in a VM. Package availability depends on configured repositories and subscriptions.

## Commands to explore

```bash
rpm -q bash
dnf list --installed bash
dnf repolist
```

## Practice

Find the installed Bash package version and list enabled repositories. On a practice VM, inspect `dnf --help` before any update.
