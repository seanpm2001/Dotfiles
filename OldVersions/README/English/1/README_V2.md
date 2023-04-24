
***

# dotfiles

`⚫️📄️ .dotfiles used by @seanpm2001`

## What are dotfiles?

Dotfiles are configuration files that are typically stored in files/folders starting with a `.` (period, or dot) for example:

`.profile`

contains profile configuration scripts/source code for the computer. This is what the inside looks like on a default Ubuntu 22.04 installation:

```shell
# ~/.profile: executed by the command interpreter for login shells.
# This file is not read by bash(1), if ~/.bash_profile or ~/.bash_login
# exists.
# see /usr/share/doc/bash/examples/startup-files for examples.
# the files are located in the bash-doc package.

# the default umask is set in /etc/profile; for setting the umask
# for ssh logins, install and configure the libpam-umask package.
#umask 022

# if running bash
if [ -n "$BASH_VERSION" ]; then
    # include .bashrc if it exists
    if [ -f "$HOME/.bashrc" ]; then
	. "$HOME/.bashrc"
    fi
fi

# set PATH so it includes user's private bin if it exists
if [ -d "$HOME/bin" ] ; then
    PATH="$HOME/bin:$PATH"
fi

# set PATH so it includes user's private bin if it exists
if [ -d "$HOME/.local/bin" ] ; then
    PATH="$HOME/.local/bin:$PATH"
fi
```

## Dotfiles repositories

Dotfiles repositories to check out.

- [:octocat: `Git-Templates`](https://github.com/seanpm2001/Git-Templates/)
- [:octocat: `My Linux Setup`](https://github.com/seanpm2001/My-Linux-setup/)
- [:octocat: `Linux.linux`](https://github.com/seanpm2001/Linux.linux/)
- - [:octocat: `Linux.Desktop`](https://github.com/seanpm2001/Linux.Desktop/)
- - [:octocat: `Linux.Templates`](https://github.com/seanpm2001/Linux.Templates/)
- - [:octocat: `Linux.Public`](https://github.com/seanpm2001/Linux.Public/)
- - [:octocat: `Linux.Trash`](https://github.com/seanpm2001/Linux.Trash/)
- - [:octocat: `Linux.Pictures`](https://github.com/seanpm2001/Linux.Pictures/)
- - [:octocat: `Linux.Music`](https://github.com/seanpm2001/Linux.Music/)
- - [:octocat: `Linux.Home`](https://github.com/seanpm2001/Linux.Home/)
- - - [:octocat: `Linux.home.Videos`](https://github.com/seanpm2001/Linux.home.Videos/)
- - - [:octocat: `Linux.home.Documents`](https://github.com/seanpm2001/Linux.home.Documents/)
- - [:octocat: `Linux.Ubuntu.SnapPackages`](https://github.com/seanpm2001/Linux.Ubuntu.SnapPackages/)

***

**File version:** `2 (2023, Sunday, April 23rd at 5:03 pm PST)`

***
