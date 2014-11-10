markdown for what
=================

A CLI that takes markdown files as input and outputs HTML pages.

```
NAME:
   mdfw - Static site generator for markdown source files

USAGE:
   mdfw [global options] command [command options] [arguments...]

VERSION:
   0.0.0

COMMANDS:
   help, h      Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --input, -i '*.md'
                Markdown files to process
   --template, -t '<html><head><title>{{.Title}}</title></head><body>{{.Body}}</
body></html>'   Template file to use for generating HTML
   --output, -o './'
                Location to write HTML files to
   --help, -h
                show help
   --version, -v
                print the version
```