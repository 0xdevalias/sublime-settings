[/dev/alias's](http://devalias.net) [Sublime Text 2](http://www.sublimetext.com/2) Settings
================

## Features

- Packages
  - [Alignment](https://github.com/wbond/sublime_alignment) for easy aligning of variables
	- [Gist](https://github.com/condemil/Gist) for [Gist](https://gist.github.com/) support
	- [GitGutter](https://github.com/jisaacks/GitGutter#readme) for inline git visuals
	- [MarkdownEditing](https://github.com/balupton/MarkdownEditing) for awesome visual markdown editing (like byword and iawriter)
	- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) for inline linting
  - TODO: Add the rest here
	- My keymaps, snippets and preferences


## Installation

* Install [Sublime Text 2](www.sublimetext.com/2)
* Install [Sublime Package Control]([http://wbond.net/sublime_packages/package_control)
* Proceed with cloning this repo as follows..

### OSX/Linux

- OSX: `cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User`

``` bash
rm *.sublime-settings
git init
git remote add origin https://github.com/alias1/sublime-settings.git
git pull origin master  --force
```

### Windows

- XP: `cd 'Application Data/Sublime Text 2/Packages/User'`
- 7+: `cd 'AppData/Roaming/Sublime Text 2/Packages/User'`
- Portable: `cd 'SublimeText2/Data/Packages/User'`

``` bash
rm *.sublime-settings
git init
git remote add origin https://github.com/alias1/sublime-settings.git
git fetch origin
git checkout windows
```

## Suggestion

* Instead of doing the above, you'll probably want to fork the repository and use your fork instead of mine. That'll allow you to push your changes back.
