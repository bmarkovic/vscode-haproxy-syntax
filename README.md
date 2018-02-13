# HAProxy for Visual Studio Code

This is the syntax highlighter for HAProxy configuration files, based on [sublime-haproxy](https://github.com/ramonfritsch/sublime-haproxy) Sublime Text package.

## Features

At the moment, the extension is just a repackaged syntax highlighter for HAProxy configuration files. In the future I do plan adding some snippets/templates for *frontends, backends, listeners, ACLs* and other common syntax constructs in config files. Considering how infrequently these files are edited, and the complexity of developing "fancier" language support (like validation or code completion) for VS.Code, I don't plan on developing any of those in the foreseeable future.

## Known Issues

Currently it will automatically triger only on files called "haproxy.cfg" verbatim, but you can always set syntax manually by pressing <kbd>Ctrl + K</kbd>, <kbd>M</kbd> and then typing `haproxy` or selecting from the drop down.

## Release Notes

### 0.1.1

Integrated the changes from https://github.com/nvtkaszpir/sublime-haproxy

### 0.1.0

Initial version of HAProxy for Visual Studio Code -- just repackaged sublime-haproxy
