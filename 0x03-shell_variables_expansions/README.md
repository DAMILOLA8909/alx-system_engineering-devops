# 0-alias: Dangerous Alias Demonstration

## Description
This script creates an alias named `ls` that overrides the standard `ls` command. When executed, typing `ls` will run `rm *` instead, deleting all files in the current directory.

**⚠️ WARNING: This is a dangerous alias meant for educational purposes only!**

## File Contents
```bash
#!/bin/bash
# 0-alias
# Creates an alias named 'ls' with value 'rm *'
alias ls='rm *'
