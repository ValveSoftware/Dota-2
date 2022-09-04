# Dota-2
Tracker for issues specific to Dota 2 on Linux and macOS. 
* If you have a general issue or non-system-specific feature request, please use [Dota2-Gameplay](https://github.com/ValveSoftware/Dota2-Gameplay) tracker instead. 
* Issues that only occur with Vulkan should be logged in the [Dota-2-Vulkan](https://github.com/ValveSoftware/Dota-2-Vulkan) tracker.

As this is a bug tracker and not a discussion forum the existence of the issue is sufficient for Valve to see it.  New issues will be checked by a Valve dev and marked reviewed if they are kept.  This means that Valve is aware of the issue and the issue will stay open as long as Valve believes it hasn't been fixed.  There won't be further comments on the issue unless there are specific questions or information to convey.  In particular it isn't possible to give up-front timeframes for when things will be fixed.  There is no need to post on open issues that they have not been fixed as Valve will close issues when they are expected to be fixed.

Notes:

* Make sure to validate your Dota install from the Steam client: https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB
* The game requires a 64-bit capable CPU and distribution.
* If using NVIDIA proprietary drivers on Linux, please update to 340.xx or newer before filing a bug report.
* If using Mesa on Linux, please update to 10.5.9 or newer before filing a bug report.

If the game fails to launch with a "missing executable" error the [validation](https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB) should correct it.

Conduct
-------

There are basic rules of conduct that should be followed at all times by everyone participating in the discussions.  While this is generally a relaxed environment, please remember the following:

- Do not insult, harass, or demean anyone.
- Do not intentionally multi-post an issue.
- Do not use ALL CAPS when creating an issue report.
- Do not repeatedly update an open issue remarking that the issue persists.

Remember: Just because the issue you reported was reported here does not mean that it is an issue with Dota 2.  As well, should your issue not be resolved immediately, it does not mean that a resolution is not being researched or tested.  Patience is always appreciated.

Reporting Issues
----------------

If you encounter a bug while using Dota 2, first search the [issue list](https://github.com/ValveSoftware/Dota-2/issues) to see if it has already been reported. Include closed issues in your search. If your issue has been reported, please upvote the issue by clicking the "Add Reaction" button (smiley face with a plus sign) on the top post and adding a thumbs up. Voting helps us determine which issues are important to users without cluttering the bug database.

***Note:*** Comments do not count as votes.

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

### Crash dumps / Failure report files

Your Steam system information may have a Failure Reports section which indicates failures that were recognized and submitted to Valve.  If a failure report has a crash ID it was recorded at Valve and will be available to Valve developers.  If the crash was discarded it means that other similar reports are already available.  If there are no failure reports in the Steam system information then the failures are not being caught by Dota.  This may indicate a system problem or a class of failure that can't be captured.  On Linux you can look in /tmp/dumps to see if there are crash dump files there.  Also on Linux you can look at the tail of the dmesg output after a crash to see if Dota is mentioned.  On macOS you can look at system crash information to see if there is a report of a failure.

Feature Requests
-------------------

This repository is not meant for Dota 2 feature requests. For feature requests, please use [Dota2-Gameplay](https://github.com/ValveSoftware/Dota2-Gameplay) tracker instead.

Linux Specific
==============

Driver Contact Information
--------------------------

Some of the issue you may be experiencing are due to the various video drivers. Here is an incomplete list of places that you might be able to file bugs or get additional help:


### AMD / Intel Open Source driver

For discussions, there is the mesa-users email list:

- https://docs.mesa3d.org/lists.html

Bugs and feature requests should be logged in bugzilla:

- https://docs.mesa3d.org/bugs.html

### NVIDIA

NVIDIA supported drivers:

- https://forums.developer.nvidia.com/c/gpu-graphics/linux/148

Open Source NVIDIA driver (nouveau):

- https://nouveau.freedesktop.org/

If you know of any other places, please let us know.
