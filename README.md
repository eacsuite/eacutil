eacutil
=======

[![Build Status](http://img.shields.io/travis/eacsuite/eacutil.svg)](https://travis-ci.org/eacsuite/eacutil) 
[![Coverage Status](http://img.shields.io/coveralls/eacsuite/eacutil.svg)](https://coveralls.io/r/eacsuite/eacutil?branch=master) 
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](http://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/eacsuite/eacutil)

Package eacutil provides earthcoin-specific convenience functions and types.
A comprehensive suite of tests is provided to ensure proper functionality.  See
`test_coverage.txt` for the gocov coverage report.  Alternatively, if you are
running a POSIX OS, you can run the `cov_report.sh` script for a real-time
report.

This package was developed for eacd, an alternative full-node implementation of
earthcoin based on btcd, which is under active development by Conformal.
Although it was primarily written for eacd, this package has intentionally been
designed so it can be used as a standalone package for any projects needing the
functionality provided.

## Installation and Updating

```bash
$ go get -u github.com/eacsuite/eacutil
```

## License

Package eacutil is licensed under the [copyfree](http://copyfree.org) ISC
License.
