# List of tools and usage

## Install

- `$ git clone git@github.com:loydle/bin.git`
-  add bin folder to $PATH


## gitty

https://github.com/loydle/gitty-cli

 Add, Commit and push changes in one command! :sparkles:

### usage

`$ gitty` or `$ gitty [message]`

## gobuster

https://github.com/OJ/gobuster

Gobuster is a tool used to brute-force:
- URIs (directories and files) in web sites.
- DNS subdomains (with wildcard support).
- Virtual Host names on target web servers.
- Open Amazon S3 buckets

### usage

```bash
# Enumerate list of open endpoints
$ gobuster dir -k -u <url> -w <wordlist.txt>
``` 
