# ropen

`ropen` is a command line viewer for data files.

## Requirements

* [io](https://bitbucket.org/djhshih/io)

## Installation

Download a release archive, extract it, and place `ropen` in a 
directory included in the `$PATH` environmental variable, such as `/usr/local/bin`.

If you are on Linux, you can also do

```bash
curl -L https://github.com/djhshih/ropen/archive/v0.1.tar.gz | \
	tar -xz --strip-components=1 ropen-*/ropen
install ropen /usr/local/bin && rm ropen
```

Note that the second line requires root permission (`sudo`).


## Usage

```
ropen infile.ext
```

`ropen` will read the input file `infile.ext`, assuming that the file format is correctly
specified by the file extension `ext`. This file extension must be supported by the `io` R package.

