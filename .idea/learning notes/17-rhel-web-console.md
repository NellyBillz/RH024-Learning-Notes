# 17. Managing systems with the RHEL web console

## What I learned

The RHEL web console (Cockpit) provides browser-based system administration for tasks such as checking resources, services, logs, storage, and networking. Access is governed by system accounts and privileges.

## Key idea

On an authorized lab host, check the `cockpit.socket` unit and use HTTPS on port 9090 if enabled. Avoid exposing an administration interface publicly without proper access controls.

## Commands to explore

```bash
systemctl status cockpit.socket --no-pager
ss -ltn | head
```

## Practice

Check whether Cockpit is installed and whether its socket is active. If it is absent, document that result instead of installing it on a shared machine.
