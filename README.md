# idcomments

Extract comments from an Internet-Draft with interspersed review comments.

Comments have to follow the text to which they apply without intervening blank
lines. The first comment line has to start with a comment tag, and following
comment lines has to be tab-indented. A comment ends with the first blank line.

The comment tag is by default `COMMENT:`, but the tag word is configurable with
the `-t` switch.

## Usage

``` shell
idcomments [OPTIONS] ... REVIEW
```

## Options

* `-h`, `--help`  
  Show this help, then exit

* `-t`, `--tag`  
  Use the provided tag string instead of `COMMENT:`

* `-V`, `--version`  
  Show program version, then exit

