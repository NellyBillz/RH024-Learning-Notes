# 15. Insights Image Builder

## What I learned

Image Builder creates tailored RHEL system images for target platforms. A blueprint or image definition specifies software and configuration; the output format depends on the deployment target.

## Key idea

Choose a target, select packages, build the image, test it, then revise. The hosted Insights service may require a Red Hat account and appropriate access; do not put image credentials in a repository.

## Commands to explore

```bash
cat /etc/os-release
command -v composer-cli || true
```

## Practice

Sketch a blueprint for a web server VM: target platform, packages, and how you would verify the resulting image. No cloud deployment is required.
