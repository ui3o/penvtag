# penvtag
TAG a process. List and kill tagged process.

# Descrition

Tag a linux process easily with environment variable. Tag definition is `t=`

# Example

* `t=sleeptag sleep infinity`
* `t=tail tail -f /etc/group | t=vim less`
* `t=tail tail -f /etc/group | t=tailvim less`

# Usage

* `pegrep sleeptag` grep exact mach
* `pegrep tail` grep group mach

# Install

* git clone https://github.com/ui3o/penvtag
* export PATH=$PATH:/path/to/cloned/repo/penvtag
