---
layout: page-help
title: Mu - Help
---
<div id="mu-help-header-inject"></div>
<div class="jumbotron">
    <h1>Help for Mu</h1>
    <p class="lead"><a href="/">Mu</a> is a simple code editor for beginner
    programmers. It's written in Python and works on Windows, OSX, Linux and Raspberry Pi.</p>
</div>

# Help

## Starting Mu

Coming soon... ;-)

## Mu Buttons

### New
![new button](images/new.png)

Click the new button to start in a new file in mu. This won't damage your old files - a fresh place to work.

### Load
![load button](images/load.png)

Load a file - your old work or some other python file to work on.

### Save
![save button](images/save.png)

Saves your work so you can keep it for later and not loose it if you loose power. Do this often!

### Flash
![flash button](images/flash.png)

Flash your code onto the Microbit. This is how you get your code to run!

### Files
![files button](images/files.png)

Show the files on your Micropython.

### Repl
![repl button](images/repl.png)

The repl is a way of typing stuff and seeing the microbit do something immediately. It is an abbreviation for "read-eval-print-loop".

### Zoom In
![Zoom in button](images/zoom-in.png)

Make the letters bigger

### Zoom Out

![Zoom out button](images/zoom-out.png)

Make the letters smaller

### Check
![Check Code button](images/check.png)

This button will check your code and underline errors you have made. Worth doing before you flash your code.

### Help
![Help Button](images/help.png)

Show help - should be this help.

### Quit
![Quit Button](images/quit.png)

Press this when you are done with Mu. Mu will make sure you've saved your work if you want to keep it.

# Advanced - settings file

Workspace settings are stored in a file named settings.json.

By default this file is located in the application data directory, but a settings file in the same directory as the Mu application itself will take priority.

By default, Mu uses a bundled version of the MicroPython runtime, but advanced users (e.g. those developing the Microbit runtime) can use the settings.json file to configure Mu to use their own runtime hex file.

To do this, add a line like this to the settings.json file:

"microbit_runtime_hex": "customhex.hex"

If the file name is not fully qualified then it will be searched for in the workspace directory.

# Microbit Help

[Microbit Micropython Help](https://microbit-micropython.readthedocs.io/en/latest/)
