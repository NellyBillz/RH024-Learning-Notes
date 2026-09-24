# 05. Linux directories explained

## What I learned

The Linux filesystem is one tree rooted at `/`. `/home` holds user homes, `/etc` configuration, `/var` variable data and logs, `/usr` most installed programs, and `/tmp` temporary files.

## Key idea

A path tells you where a file lives, not who owns it. RHEL may use symbolic links for legacy directories. Inspect paths rather than assuming each directory is a separate disk.

## Commands to explore

```bash
ls -ld / /home /etc /var /usr /tmp
readlink -f /bin
df -h /
```

## Practice

Choose a configuration file under `/etc` and a log under `/var/log`. Record only their paths, without copying private contents.
