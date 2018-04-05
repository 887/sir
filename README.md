# sir - sir I request
Command line tool to look for and install software

just an idea right now, but should essentially do the following:

- Be this command line tool, a lib and a gtk graphical tool.
- install, update and remove software from multiple sources
- should be able to manage or just detect:
    - user-home-folder-installed software in common locations
    - system wide installed software
    - software thats installed for other users, if applicable
    - software thats installed in multiple packages, prefixes, namespaces in common locations
    - software thats installed via flatpak, snap, appimage and what else is out there
    - software thats installed via packagekit
    - software thats installed via brew
    - software thats installed via npm -g and sudo npm install -g
    - software thats installed via what-else-is-out there

should otherwise take commandline parameters, generate a man page etc.

should also be apple to parse multiple backend apis, show icons for everything in the graphical app, scale nicely, show descriptions etc.


