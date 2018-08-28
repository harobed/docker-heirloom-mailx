# Docker heirloom-mailx

I want to use [heirloom-mailx](http://heirloom.sourceforge.net/mailx.html) with [corentinaltepe/heirloom-mailx](https://hub.docker.com/r/corentinaltepe/heirloom-mailx/) Docker image but I don't found Dockerfile source code, then I have created it in this repository.

## Build Docker image

```
$ docker build -t harobed/heirloom-mailx .
```

## Usage

```
$ docker run --rm harobed/heirloom-mailx mailx -h
Usage: mailx -eiIUdEFntBDNHRV~ -T FILE -u USER -h hops -r address -s SUBJECT -a FILE -q FILE -f FILE -A ACCOUNT -b USERS -c USERS -S OPTION users
```
