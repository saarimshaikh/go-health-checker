## Healthchecker.

A tiny tool that checks the given domain is down.

## Installation

> This project needs to Go (At least 1.13) to compile.  
  Download from [**here**](https://golang.org/dl/).

**Get the repo.**

```bash
go get https://github.com/saarimshaikh/go-health-checker.git
```
OR

```bash
git clone https://github.com/saarimshaikh/go-health-checker.git
```
and then CD into the project and run

```bash
go run . --domain pexels.com
```

## Usage

```
NAME:
   Healthchecker - A tiny tool that checks the given domain is down.

USAGE:
   healthchecker [global options] command [command options] [arguments...]

COMMANDS:
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --domain value, -d value  Domain name to check.
   --port value, -p value    Port number to check.
   --help, -h                show help (default: false)

```
