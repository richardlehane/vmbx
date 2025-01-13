# HP TRIM VMBX Email Format

This is a library and command line tool for working with HP TRIM VMBX email files. You can use this tool for extracting attachments and converting VMBX files to EML.

## Install

From source:

	go install github.com/richardlehane/vmbx/vmbx@latest

Or get a precompiled Windows 64-bit binary from the [releases page](https://github.com/richardlehane/vmbx/releases).


## Usage

To extract attachments from a VMBX file, or set of files:

	vmbx -dump FILE or DIR

To convert a VMBX file, or set of files, to EML format, do:

	vmbx -mail FILE or DIR



