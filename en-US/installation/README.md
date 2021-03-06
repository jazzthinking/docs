---
root: true
name: Installation
sort: 1
---

## Requirements

- [MySQL](http://dev.mysql.com): Version >= 5.1 or [PostgreSQL](http://www.postgresql.org/) or **NOTHING**.
- [git](http://git-scm.com/)(bash): Version >= 1.6.6(both server and client)

### Install Database

Gogs supports MySQL, PostgreSQL and SQLite3, based on your choice, install either one of them or skip this step:

- [MySQL](http://dev.mysql.com/downloads/mysql/) (Engine: INNODB)
- [PostgreSQL](http://www.postgresql.org/download/)

**REMEMBER** use `conf/mysql.sql` to create a database called `gogs`(default). If you create it manually, make sure the encoding is `utf8`.
 
### Install other requirements
#### Max OS X

Assume you've installed [Homebrew](http://brew.sh/) already:

```
$ brew update
$ brew install git
```

#### Linux

```
$ sudo apt-get update
$ sudo apt-get install git
```

#### Windows

[Download and install Git](http://git-scm.com/downloads)

## Install Gogs

- [Install from binary](install_from_binary.md)
- [Install from source](install_from_source.md)