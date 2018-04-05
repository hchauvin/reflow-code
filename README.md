# reflow-code

reflow-code is a [Visual Studio Code](https://code.visualstudio.com/) extension that supports [Reflow](github.com/grailbio/reflow) development.


## Features

Currently, only syntax highlighting is supported.

## Installation

### From the VSCode market place

This plugin is in alpha version and currently not published.
To install the development version, see below.

### Development version

To install the latest development version directly from HEAD:

1. Clone the Git repository, e.g. to `~/reflow-code`:
```bash
cd ~ && git clone https://github.com/hchauvin/reflow-code.git
```
2. Symlink the local repository to the VSCode extensions folder.  On Linux and Mac:
```bash
ln -s ~/reflow-code ~/.vscode/extensions/reflow-code
```
3. Restart VSCode (just quit and reopen).

## Development

1. Clone the Git repository, e.g. to `~/reflow-code`:
```bash
cd ~ && git clone https://github.com/hchauvin/reflow-code.git
```
2. Open VSCode from within the repository:
```bash
code ~/reflow-code
```
3. Go to `Debug > Start Debugging` (F5) to open a new VSCode window where the
development version of the extension is enabled.

## Release Notes

### 0.1.0

Initial release of the "reflow-code" extension.

## License: [MIT](https://github.com/hchauvin/reflow-code/blob/master/LICENSE)