### Overview

My simple *nix setup and configuration backup.

### Setup

Clone the repository and change the local directory name:

* $ `git clone git@github.com:srobbibaro/.my-config-files.git my-config-files`

#### General

Update git configuration values and copy into place:

* Update `<<...>>` values in `gitconfig` with your actual configuration.
* $ `cp my-config-files/gitconfig ~/.gitconfig`

#### OSX

Copy the bash profile into place:

* $ `cp my-config-files/bash_profile ~/.bash_profile`

### Notes

* Do not submit `gitconfig` with `<<...>>` replaced with real configuration.
* Copying the files into place is preferable to using a symlink since it helps
  ensure that additions to the git repository are intentional.
