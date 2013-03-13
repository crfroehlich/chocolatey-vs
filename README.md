chocolatey-vs
=============

PowerShell Script to install all the prerequisite apps for a ~working Visual Studio environment.

This script makes 2 presumptions:

* You've executed it from the directory of the _web_ project you want to initialize for use in your VS environment
    * If this isn't true for you, it's OK--all install options default to 'NO', so just say no
* You've executed this using the syntax `@powershell -NoProfile -ExecutionPolicy unrestricted -File [this].ps1`

Beyond that, read the source, follow the [Chocolately Gods] (https://github.com/chocolatey/chocolatey/wiki/DevelopmentEnvironmentSetup) and fork this repo.

My work is always public domain, though its inspirations may not be. If you can help it, public domain it.
