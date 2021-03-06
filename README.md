#dtsgenerator

[![NPM version](https://badge.fury.io/js/dtsgenerator.svg)](http://badge.fury.io/js/dtsgenerator)
[![Build Status](https://travis-ci.org/horiuchi/dtsgenerator.svg?branch=master)](https://travis-ci.org/horiuchi/dtsgenerator)
[![Coverage Status](https://img.shields.io/coveralls/horiuchi/dtsgenerator.svg)](https://coveralls.io/r/horiuchi/dtsgenerator?branch=coveralls)

TypeScript d.ts file generator from JSON Schema files

# Install

    npm install -g dtsgenerator

# Usage

```
$ dtsgen --help

  Usage: dtsgen [options] <file ... | file patterns using node-glob>

  Options:

    -h, --help        output usage information
    -V, --version     output the version number
    -o, --out [file]  output d.ts filename

```

## Example

    $ dtsgen --out types.d.ts schema/**/*.schema.json
    $ cat schema1.json | dtsgen
