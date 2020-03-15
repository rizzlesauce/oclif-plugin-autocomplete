@oclif/plugin-autocomplete
==========================

autocomplete plugin for oclif (bash & zsh)

[![Version](https://img.shields.io/npm/v/@oclif/plugin-autocomplete.svg)](https://npmjs.org/package/@oclif/plugin-autocomplete)
[![CircleCI](https://circleci.com/gh/oclif/plugin-autocomplete/tree/master.svg?style=shield)](https://circleci.com/gh/oclif/plugin-autocomplete/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/plugin-autocomplete?branch=master&svg=true)](https://ci.appveyor.com/project/oclif/plugin-autocomplete/branch/master)
[![Codecov](https://codecov.io/gh/oclif/plugin-autocomplete/branch/master/graph/badge.svg)](https://codecov.io/gh/oclif/plugin-autocomplete)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/plugin-autocomplete.svg)](https://npmjs.org/package/@oclif/plugin-autocomplete)
[![License](https://img.shields.io/npm/l/@oclif/plugin-autocomplete.svg)](https://github.com/oclif/plugin-autocomplete/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
See https://oclif.io/docs/plugins.html
# Commands
<!-- commands -->
* [`oclif-example _autocomplete [SHELL]`](#oclif-example-_autocomplete-shell)

## `oclif-example _autocomplete [SHELL]`

display autocomplete installation instructions

```
USAGE
  $ oclif-example _autocomplete [SHELL]

ARGUMENTS
  SHELL  shell type

OPTIONS
  -r, --refresh-cache  Refresh cache (ignores displaying instructions)

EXAMPLES
  $ oclif-example _autocomplete
  $ oclif-example _autocomplete bash
  $ oclif-example _autocomplete zsh
  $ oclif-example _autocomplete --refresh-cache
```

_See code: [src/commands/_autocomplete/index.ts](https://github.com/rizzlesauce/oclif-plugin-autocomplete/blob/v0.1.6-rossa.1/src/commands/_autocomplete/index.ts)_
<!-- commandsstop -->
