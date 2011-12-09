
# Nitrix

## Run a NodeJS process Forever. Restart on File changes & crashes with piping to stdout or logs (both with --verbose)

***

### Motivation

A NodeJS process management tool that is always up to the latest NodeJS stable version. Ability to either use nitrix in **development** with realtime upon live local file edits; or in **production** with logging and optional --verbose output.

### Installation

```bash
$ [sudo] npm install nitrix -g
```

***

### Basic Usage

**Realtime Development**

```bash
$ nitrix app.js
```

**Production**

```bash
$ nitrix start app.js
$ nitrix list
$ => [0] app.js 00:00:04
```

### Usage (Advanced)
