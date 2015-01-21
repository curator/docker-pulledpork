docker-pulledpork
=============

Run the pulledpork client anywhere without any of the horror of perl dependencies

"Installation"
=============
```
alias pulledpork="docker run --rm -it curator/pe-pulledpork"
```

Usage
=============

Help:
```
pulledpork -help
```

Tinkering:
```
docker run -it -v ~/Downloads/pulledpork:/etc/snort --entrypoint=/bin/bash --rm docker-pulledpork -s
```

*As Justin Clayton would say:*
> You did it!
