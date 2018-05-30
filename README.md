# merger

[![GoDoc](https://godoc.org/github.com/iph0/merger?status.svg)](https://godoc.org/github.com/iph0/merger) [![Build Status](https://travis-ci.org/iph0/merger.svg?branch=master)](https://travis-ci.org/iph0/merger)

Package merger recursively merge two maps or structures into new one. Non-zero
values from the right side has higher precedence. Slices do not merging, because
main use case of this package is merging of configuration parameters, and in
this case merging of slices is unacceptable. See documentation on
[GoDoc](https://godoc.org/github.com/iph0/merger) for more information.