# go-shdlc

[![GoDoc](https://godoc.org/github.com/lvdlvd/go-hdlc?status.svg)](https://godoc.org/github.com/lvdlvd/go-hdlc)

Package shdlc implements HDLC-like framing of packets on bytestreams used by Sensirion.

The C directory contains 2 C functions to do the same.

I use this to have my go programs on a macbook exchange binary packets with an arduino over a serial port.

