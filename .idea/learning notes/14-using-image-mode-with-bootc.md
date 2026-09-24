# 14. Using Image Mode with Bootc

## What I learned

RHEL image mode packages the operating system as a bootable container image. Bootc can manage deployment and updates from an image, supporting a repeatable image-based workflow.

## Key idea

Build and test a derived image in an appropriate RHEL image-mode environment; use the same validated image across targets. A regular package-based RHEL installation is not automatically a bootc-managed host.

## Commands to explore

```bash
command -v bootc || true
bootc status
```

## Practice

If on a bootc-managed test host, inspect `bootc status` and record the current deployment. Otherwise explain what environment would be needed before testing.
