# @cypress/chrome-recorder

This repo provides tools to export Cypress Tests from Google Chrome DevTools' Recordings

## Installation

```sh
$ npm install -g @cypress/chrome-recorder
```

## Usage (CLI)

To use the interactive CLI, run:

```sh
$ npx @cypress/chrome-recorder
```

The CLI will prompt you to enter the path of the directory or file that you would like to modify as well as a path to write the generated Cypress test to.

If you prefer to enter paths via the CLI, you can run:

```sh
$ npx @cypress/chrome-recorder <relative path to target test file or directory>
```

### CLI Options

| Option      | Description                                               |
| ----------- | --------------------------------------------------------- |
| -f, --force | Bypass Git safety checks and force exporter to run        |
| -d, --dry   | Dry run (no changes are made to files)                    |
| -p, --print | Print transformed files to stdout, useful for development |
