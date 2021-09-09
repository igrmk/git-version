Git version
===========

This is a very simple Bash script that constructs a version string from a Git repository according to the rules of Go modules.

https://golang.org/ref/mod#versions

https://golang.org/ref/mod#pseudo-versions

Usage
-----

Copy the script

```bash
curl https://raw.githubusercontent.com/igrmk/git-version/main/describe-version > describe-version
chmod u+x describe-version
```

Use it as you wish

```bash
echo "__version__ = \"$(./describe-version)\"" > _version.py
```
