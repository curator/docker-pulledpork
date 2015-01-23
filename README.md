docker-pulledpork
=============

Run the pulledpork client anywhere without any of the horror of perl dependencies

"Installation"
=============
```
alias pulledpork="docker run --rm -it curator/docker-pulledpork"
```

Usage
=============

Help:
```
pulledpork -help
```

Tinkering:
```
docker run -it -v ~/gitrepos/pulledpork:/etc/snort --entrypoint=/bin/bash --rm curator/docker-pulledpork -s
```

Using:
```
docker run -v ~/gitrepos/pulledpork:/etc/snort --rm curator/pulledpork -c /etc/snort/pulledpork/pulledpork.conf -S 2.9.7.0
```
*As Justin Clayton would say:*
> You did it!
