# 06. Basic file management

## What I learned

Files and directories can be created, copied, moved, and removed from the terminal. `mv` can rename a file. Destructive removal is usually not sent to a recycle bin.

## Key idea

Work in a scratch directory and check the target before `rm`. `cp -i`, `mv -i`, and `rm -i` can request confirmation.

## Commands to explore

```bash
mkdir -p "$HOME/rh024-practice"
cd "$HOME/rh024-practice"
printf "practice\n" > note.txt
cp note.txt copy.txt
mv copy.txt renamed.txt
ls -l
```

## Practice

Create two files, rename one, and describe which operation preserved the original.
