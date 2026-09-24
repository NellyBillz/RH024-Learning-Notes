# 09. File permissions

## What I learned

The owner, group, and others each have read (`r`), write (`w`), and execute (`x`) permissions. Directories use execute permission for traversal. Permission changes must match the sharing need.

## Key idea

`ls -l` inspects basic permissions, `chmod` changes them, and `chown` changes ownership. `chmod 600` means owner read/write only; avoid blanket `777`.

## Commands to explore

```bash
cd "$HOME/rh024-practice"
printf "private\n" > private.txt
chmod 600 private.txt
ls -l private.txt
stat -c "%a %U:%G %n" private.txt
```

## Practice

Explain why a private file might use `600` and a directory might need execute permission.
