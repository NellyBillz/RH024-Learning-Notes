# 02. Introduction to the shell

## What I learned

The shell interprets commands and starts programs. A command has a name, options, and arguments. Paths can be absolute or relative; the current directory affects relative paths.

## Key idea

Use `pwd` to locate yourself, `ls` to inspect, and `cd` to move. Quoting preserves spaces in a single argument. A failed command generally reports a nonzero exit status.

## Commands to explore

```bash
pwd
ls -la
cd /tmp
printf "%s\n" "hello shell"
printf "exit status: %s\n" "$?"
```

## Practice

Navigate from your home directory to `/tmp` and back. Predict the output of `pwd` before running it.
