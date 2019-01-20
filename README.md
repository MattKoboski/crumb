![crumb-cli logo](https://raw.githubusercontent.com/MattKoboski/crumb-cli/master/docs/u_crumb-01.jpg)
Scaffold microservices of your choice

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/crumb-cli.svg)](https://npmjs.org/package/crumb-cli)
[![CircleCI](https://circleci.com/gh/MattKoboski/crumb-cli/tree/master.svg?style=shield)](https://circleci.com/gh/MattKoboski/crumb-cli/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/MattKoboski/crumb-cli?branch=master&svg=true)](https://ci.appveyor.com/project/MattKoboski/crumb-cli/branch/master)
[![Codecov](https://codecov.io/gh/MattKoboski/crumb-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/MattKoboski/crumb-cli)
[![Downloads/week](https://img.shields.io/npm/dw/crumb-cli.svg)](https://npmjs.org/package/crumb-cli)
[![License](https://img.shields.io/npm/l/crumb-cli.svg)](https://github.com/MattKoboski/crumb-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g crumb-cli
$ crumb COMMAND
running command...
$ crumb (-v|--version|version)
crumb-cli/0.0.3 win32-x64 node-v10.15.0
$ crumb --help [COMMAND]
USAGE
  $ crumb COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`crumb hello [FILE]`](#crumb-hello-file)
* [`crumb help [COMMAND]`](#crumb-help-command)

## `crumb hello [FILE]`

describe the command here

```
USAGE
  $ crumb hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ crumb hello
  hello world from ./src/hello.ts!
```

_See code: [src\commands\hello.ts](https://github.com/MattKoboski/crumb-cli/blob/v0.0.3/src\commands\hello.ts)_

## `crumb help [COMMAND]`

display help for crumb

```
USAGE
  $ crumb help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.4/src\commands\help.ts)_
<!-- commandsstop -->
