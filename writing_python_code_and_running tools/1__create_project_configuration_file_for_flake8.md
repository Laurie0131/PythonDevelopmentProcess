<!--- @file
  1__create_a projtect configuration file for flake8.md for Python Development Process and Coding Specification

  Copyright (c) 2019, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->
## 1 . Create a project configuration file for flake8: {#1-create-project-configuration-file-for-flake8}

`Flake8` allows the user to use a ‘global’ configuration file to store preferences. The user configuration file is expected to be stored  somewhere in the user’s home directory.

On Windows the home directory will be something like `c:\\Users\kpurma`, a.k.a, ~\.

On Linux and other Unix like systems(including OS X) look in `!/`.

Flake8 looks for "`~\.flake8`" on Windows and "`~/.config/flake8`" on Linux and other Unix systems.

User configuration files use the same syntax as Project Configuration files.

`Flake8` configuration can be stored as "**.flake8**", “**setup.cfg**” or “**tox.ini**”. Flake8 configuration uses INI as a format.

Note that project specific configuration files need to keep at the root level.
 
Any `Flake8` configuration will wish to set the needs to be in the `flake8 `section, which means it needs to start like following:

```
[flake]
```
On your project folder create a new configuration file named  `tox.ini` (or `.flake8`or `setup.cfg`) and define a section with flake8 and add project specific rules to consider. The Config defined in Appendix is used for EDK II.



The contents of `tox.ini` available in the appendix.