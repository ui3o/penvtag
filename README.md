# penvtag
TAG one or more process. List or kill tagged process/es.

# Descrition

Tag one or more linux process easily with environment variable. Tag definition is `t=`

# Example

* `t=sleeptag sleep infinity`
* `t=tail tail -f /etc/group | t=vim less`
* `t=tail tail -f /etc/group | t=tailvim less`

# Usage

* `pegrep sleeptag` grep exact mach
* `pegrep tail` grep group mach
* `pekill sleeptag` kill exact mach
* `pekill tail` kill group mach

# Install

* git clone https://github.com/ui3o/penvtag
* export PATH=$PATH:/path/to/cloned/repo/penvtag

# Troubleshoot

* Process not listed: to read a process environment variables make sure you have right privilege 