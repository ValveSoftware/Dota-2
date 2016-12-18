# Dota-2-Reborn
Tracker for issues specific to Linux and Mac in the Reborn client. If you have a general issue or non-system-specific feature request please go to dev.dota2.com

Notes:

* The game requires a 64-bit capable CPU and distribution
* If using nVidia proprietary drivers on Linux, please update to 340.xx or newer before filing a bug report
* If using Mesa on Linux, please update to 10.5.9 or newer before fixing a bug report.

If the game fails to launch with a "missing executable" error, please use Steam to [verify the integrity](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335) of the game's files in order to acquire the missing binaries.

Conduct
-------

There are basic rules of conduct that should be followed at all times by everyone participating in the discussions.  While this is generally a relaxed environment, please remember the following:

- Do not insult, harass, or demean anyone.
- Do not intentionally multi-post an issue.
- Do not use ALL CAPS when creating an issue report.
- Do not repeatedly update an open issue remarking that the issue persists.

Remember: Just because the issue you reported was reported here does not mean that it is an issue with Dota 2 Reborn.  As well, should your issue not be resolved immediately, it does not mean that a resolution is not being researched or tested.  Patience is always appreciated.

Reporting Issues
----------------

If you encounter a bug while using Dota 2 Reborn, first search the [issue list](https://github.com/ValveSoftware/Dota-2-Reborn/issues) to see if it has already been reported. Include closed issues in your search.

If it has not been reported, create a new issue with at least the following information:

- what platform this is occuring on: Linux or Mac;
- a short, descriptive title;
- a detailed description of the issue, including any output from the command line;
- steps for reproducing the issue; and
- your [system information](#system-information).

Please place logs either in a code block (press `M` in your browser for a GFM cheat sheet) or a [gist](https://gist.github.com).

### System information

Your system information must include:
- your Linux distro or Mac OS version
- if Linux, your Desktop/Window Manager
- if Mac, the model and revision of your hardware
- your Graphics card info (manufacturer, card version), any and all graphics driver versions
- anything else that you think may be useful (mouse/keyboard, filesystem type, etc).

The preferred and easiest way to get this information is from Steam's Hardware Information viewer from the menu (`Help -> System Information`).

Once your information appears: right-click within the dialog, choose `Select All`, right-click again, and then choose `Copy`.
Paste this information into your report, preferably in a code block or a [gist](https://gist.github.com).

Feature Requests
-------------------

This repository is not meant for Dota 2 Reborn feature requests. There are forums dedicated to general Dota 2 discussion at http://dev.dota2.com.

Linux Specific
==============

Driver Contact Information
--------------------------

Some of the issue you may be experiencing are due to the various video drivers.  Here is an incomplete list of places that you might be able to file bugs or get additional help:

### AMD

AMD Steam Linux forum for reporting **compatibility and performance issues with AMD hardware**:

https://community.amd.com/community/devgurus/steam-linux

The AMD Open Source driver is a part of Mesa, so use the links under "Intel" to report issues with it.

### Intel

For discussions, there is the mesa-users email list:

http://mesa3d.org/lists.html

Bugs and feature requests should be logged in bugzilla:

http://mesa3d.org/bugs.html

### NVIDIA

NVIDIA supported drivers
- https://devtalk.nvidia.com/default/board/98

Open Source NVIDIA driver (nouveau)
- http://nouveau.freedesktop.org/wiki

If you know of any other places, please let us know.
