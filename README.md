NOT WORKING YET !

# jupyterlab Blockly

A JupyterLab extension for viewing [Blockly](https://github.com/google/blockly) data
files. A file renderer for files with `.blockly` extensions and a mime renderer for the
`application/blockly+xml` mimetype is included. This extension uses
[blockly JS renderer](https://github.com/google/blockly).


Here are some screenshots ###

To use the file viewer, right-click on a `.blocky` file and choose the `blocky` viewer.

## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install jupyterlab_blockly
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

## TODO

* allow visual editing
* add tests
* add local/global variables
* add some functions/modules
* run python export on a running kernel
