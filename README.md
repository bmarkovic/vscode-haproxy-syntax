# HAProxy for Visual Studio Code

This is the syntax highlighter for HAProxy/HAPEE configuration files, based on
[sublime-haproxy](https://github.com/ramonfritsch/sublime-haproxy) Sublime Text
package.

See: https://www.haproxy.com/ (HAPEE) http://www.haproxy.org/ (HAProxy)


## Features

- Syntax highlighting for HAProxy configuration files (`haproxy.cfg`), greatly
  expanded from Sublime Original, and adjusted to better fit VS Code coloring
  schemas
- Basic snippets for most common blocks of configuration text i.e. *frontends,
  backends, listeners, acls, userlists*
- A *global/default* config starter template -- available as a snippet.

## Known Issues

Currently it will automatically triger only on files called "haproxy.cfg"
verbatim, but you can always set syntax manually by pressing <kbd>Ctrl +
K</kbd>, <kbd>M</kbd> and then typing `haproxy` or selecting from the drop down.

## Release Notes

### 0.1.2

* Added stick table, stick table aggregator, peers and resolvers syntax

### 0.1.1

* Integrated the changes from https://github.com/nvtkaszpir/sublime-haproxy
* Simplified regexes for better maintainability
* Additional syntax
* Snippets for common configuration blocks

### Unreleased

Initial version of HAProxy for Visual Studio Code -- just repackaged
sublime-haproxy
