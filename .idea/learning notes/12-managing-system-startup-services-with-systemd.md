# 12. Managing system startup services with Systemd

## What I learned

Systemd starts and supervises services and other units. A service can be running now, enabled for a future boot, both, or neither.

## Key idea

`systemctl status` and `journalctl` help diagnose a service. `start` changes current runtime state; `enable` changes startup behaviour. Administrative changes belong in a practice VM.

## Commands to explore

```bash
systemctl list-units --type=service --state=running
systemctl status sshd --no-pager
journalctl -u sshd -n 10 --no-pager
```

## Practice

Pick an installed service. Check whether it is active and enabled, and explain the distinction.
