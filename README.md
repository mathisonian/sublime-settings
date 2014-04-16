sublime-settings
================

A git repo for keeping my SublimeText settings consistent across dev environments

### User Preferences

Can be found in the file [Preferences.sublime-settings](./Preferences.sublime-settings)

### Editing User Preferences

The sublime text user preferences file is stored in `~/Library/Application Support/Sublime Text {2,3}/Packages/User/Preferences.sublime-settings` (choose 2 or 3 depending upon your version of ST).

You can edit this file directly, or go through the sublime text preferences panel

![edit prefs](http://i.imgur.com/kOyel51.png)

### Package Manager

[Package Controlled](https://sublime.wbond.net/) is the preferred way to install packages.

### Packages

* [jshint gutter](https://github.com/victorporof/Sublime-JSHint) (javascript linting)
* [spacegray](https://github.com/kkga/spacegray) (theme)
* [grunt](https://sublime.wbond.net/packages/Grunt) (run grunt tasks inside of ST)
* [scss](https://sublime.wbond.net/packages/SCSS) (scss/sass syntax highlighting)
* [jade](https://sublime.wbond.net/packages/Jade) (support for jade markup, including syntax highlighting)

### Package Settings

In this repo my Package settings are stored in the folder [Package Settings](./Package%20Settings). There is one settings file per package. Sublime text stores these files at 
`~/Library/Application Support/Sublime Text {2,3}/Packages/<Package Name>/<Package Name>.sublime-settings`. Similar to the user settings, you can edit those files directly, or go
through the ST interface 

![package settings](http://i.imgur.com/gMZjRmQ.png)

### TODO

* It would be nice to have a dotfiles-esque bootstrap script that:
    * installs package manager if it is not already installed
    * installs any packages defined in this repo
    * transfers all settings files to the correct location

### License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>
