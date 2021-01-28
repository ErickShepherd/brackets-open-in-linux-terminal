Open in terminal
================

**Extension for Adobe Brackets**

Open the project folder in terminal.

Currently supports:

Linux: xfce4-terminal, konsole, gnome-terminal, lxterminal and terminator

OSX: Terminal and iTerm

Windows: cmd, powershell, ConEmu, and cmder


## Install

In extension manager, search for 'open project in terminal' and click 'Install'.

_To configure terminal Click View >> Set Terminal_

![Set Preferences](images/setterm.png)

Select One of the avilable options

![Preferences UI](images/ui.png)

## Opening a terminal

Right click on the sidebar and click "Open in Term"

![Open](images/right-click.png)

OR

Click the terminal icon in the extensions toolbar

![Open](images/ext.png)

OR

Use the keyboard shortcut Alt-T

## Windows Terminal

Currently, Windows Terminal can't take command-line arguments to change the starting directory or profile so you will have to alter its setting.json file accordingly.

To open a Windows Terminal in your current working directory, set the startingDirectory variable of your default profile to `"startingDirectory" : "%__CD__%"`.

To change your default Windows Terminal profile, set the defaultProfile key to the guid of your chosen profile.

[Detailed Instructions](https://weblog.west-wind.com/posts/2019/Sep/03/Programmatically-Opening-Windows-Terminal-in-a-Specific-Folder)
