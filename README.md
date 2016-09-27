Sublime Text configuration
==========================

This repository contains the configuration of Sublime Text editor version 3.  Thanks to [albertosantini/sublimetext-packages](https://github.com/albertosantini/sublimetext-packages) for the idea.

Installation
------------

Starting from a fresh ST installation, install [Package Control](https://sublime.wbond.net/installation) and quit the editor.

Use the link of your forked repo in the commands below.

Then you should clone the repository in `~/Library/Application Support/Sublime Text 3/Packages/User` on OSX and `Data/Packages` on Windows.

```
$ cd ~/Library/Application Support/Sublime Text 3/Packages/User
$ git init
$ git remote add origin https://github.com/Chookie/sublimetext-packages.git
$ git fetch
$ git checkout -t origin/master
```

Restart the editor and the plugins will be installed automatically. During the installation of the plugins it's normal for a few errors to be displayed. When the plugins installation has ended as shown in the console view you need to restart Sublime.
