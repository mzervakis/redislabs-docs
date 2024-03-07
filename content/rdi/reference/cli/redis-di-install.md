---
Title: redis-di install
linkTitle: redis-di install
description: Installs RDI
weight: 10
alwaysopen: false
categories: ["redis-di"]
aliases:
---

Installs RDI

## Usage

```
Usage: redis-di install [OPTIONS]
```

## Options

- `log_level`:

  - Type: Choice(['DEBUG', 'INFO', 'WARN', 'ERROR', 'CRITICAL'])
  - Default: `info`
  - Usage: `--log-level
-l`

- `file`:

  - Type: <click.types.Path object at 0x7ff8e7d1e130>
  - Default: `none`
  - Usage: `-f
--file`

  Path to a YAML configuration file for silent installation

- `help`:

  - Type: BOOL
  - Default: `false`
  - Usage: `--help`

  Show this message and exit.

## CLI help

```
Usage: redis-di install [OPTIONS]

  Installs RDI

Options:
  -l, --log-level [DEBUG|INFO|WARN|ERROR|CRITICAL]
                                  [default: INFO]
  -f, --file FILE                 Path to a YAML configuration file for silent
                                  installation
  --help                          Show this message and exit.
```