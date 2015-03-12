# MakeNext - A helper for Make

## Installation

```console
$ curl --silent https://raw.github.com/kud/makenext/master/makenext.mk > /your/project/root/path/makenext.mk
```

## Usage

In your `Makefile`:

```make
include makenext

command:
  @ echo "$(ERROR_COLOUR)this $(WARN_COLOUR)is $(OK_COLOUR)a $(NO_COLOUR)test."
```
