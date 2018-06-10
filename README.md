# reflow-code

reflow-code is a syntax highlighter and set of preferences for the [Reflow](https://github.com/grailbio/reflow) language.  The syntax is compatible with [Visual Studio Code](https://code.visualstudio.com/) and [Sublime Text](http://www.sublimetext.com/).


## Features

Currently, only syntax highlighting is supported.

## Installation for VSCode

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

## Installation for Sublime Text

### From Package Control

This plugin is in alpha version and currently not published.
To install the development version, see below.

### Development version

To install the latest development version directly from HEAD:

1. Install [PackageDev](https://github.com/SublimeText/PackageDev) using
[Package Control](https://packagecontrol.io/).
2. Go to menu `Tools > Packages > Package Development > New Syntax Definition...`
3. Copy-paste the content of [syntaxes/reflow.sublime-syntax](syntaxes/reflow.sublime-syntax) to the new
buffer and save in default location as `reflow.sublime-syntax`.
4. Now, `.rf` or `.reflow` files benefit from syntax highlighting without
the need to restart Sublime Text.

## Release Notes

### 0.1.0

Initial release of the "reflow-code" extension.

### 0.2.0

Add support for Sublime Text.

## License: [MIT](https://github.com/hchauvin/reflow-code/blob/master/LICENSE)
