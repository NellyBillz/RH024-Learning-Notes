# 13. Deploying an application runtime to host a simple application

## What I learned

An application needs a suitable runtime, its code, dependencies, configuration, and a process that listens on the expected address and port. A service manager can keep that process running.

## Key idea

A simple deployment flow is: install the runtime, place application files, configure the start command, start the service, and test locally. Firewall and SELinux rules may also affect external access.

## Commands to explore

```bash
python3 --version
python3 -m http.server 8000 --bind 127.0.0.1
```

## Practice

On a disposable machine, serve an empty practice directory, visit `http://127.0.0.1:8000`, then stop with Ctrl+C. Explain why binding to localhost limits access.
