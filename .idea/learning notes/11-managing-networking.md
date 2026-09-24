# 11. Managing networking

## What I learned

A host needs an interface, address, route, and usually DNS to reach network services. NetworkManager manages connections on RHEL and `nmcli` provides a terminal interface.

## Key idea

Inspect the address, default route, resolver, and active connection separately. Changing networking over SSH can disconnect you.

## Commands to explore

```bash
ip -br addr
ip route
nmcli connection show --active
getent hosts redhat.com
```

## Practice

Record the active interface and default route on your practice machine. Explain what DNS adds beyond an IP route.
