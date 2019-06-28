webpack-conf-cli
================

webpack config generate cli

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/webpack-conf-cli.svg)](https://npmjs.org/package/webpack-conf-cli)
[![Downloads/week](https://img.shields.io/npm/dw/webpack-conf-cli.svg)](https://npmjs.org/package/webpack-conf-cli)
[![License](https://img.shields.io/npm/l/webpack-conf-cli.svg)](https://github.com/https://github.com/wzhkobe2408/repo/https://github.com/owner/webpack-conf-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g webpack-conf-cli
$ wpconf COMMAND
running command...
$ wpconf (-v|--version|version)
webpack-conf-cli/0.0.1 darwin-x64 node-v10.13.0
$ wpconf --help [COMMAND]
USAGE
  $ wpconf COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`wpconf hello [FILE]`](#wpconf-hello-file)
* [`wpconf help [COMMAND]`](#wpconf-help-command)

## `wpconf hello [FILE]`

describe the command here

```
USAGE
  $ wpconf hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ wpconf hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/wzhkobe2408/repo/https://github.com/owner/webpack-conf-cli/blob/v0.0.1/src/commands/hello.ts)_

## `wpconf help [COMMAND]`

display help for wpconf

```
USAGE
  $ wpconf help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.0/src/commands/help.ts)_
<!-- commandsstop -->