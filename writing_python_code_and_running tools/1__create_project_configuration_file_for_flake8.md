## 1 . Create a project configuration file for flake8: {#1-create-project-configuration-file-for-flake8}

`Flake8` allows the user to use a ‘global’ configuration file to store preferences. The user configuration file is expected to be stored  somewhere in the user’s home directory.

On Windows the home directory will be something like `c:\\Users\kpurma`, a.k.a, ~\.

On Linux and other Unix like systems(including OS X) look in `!/`.

Flake8 looks for "`~\.flake8`" on Windows and "`~/.config/flake8`" on Linux and other Unix systems.

User configuration files use the same syntax as Project Configuration files.

`Flake8` configuration can be stored as "**`.flake8`**", “**`setup.cfg`**” or “**`tox.ini`**”. Flake8 configuration uses INI as a format.

Note that project specific configuration files need to keep at the root level.
 
Any `Flake8` configuration will wish to set the needs to be in the `flake8 `section, which means it needs to start like following:

```
[flake]
```
On your project folder create a new configuration file named  `tox.ini` (or `.flake8`or `setup.cfg`) and define a section with flake8 and add project specific rules to consider. The Config defined in Appendix is used for EDK II.

![](/media/image2.png)
###### Fig 2. Configuration File{#fig-2-configuration-file}

The contents of `tox.ini` available in the appendix.