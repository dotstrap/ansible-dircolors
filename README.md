dotstrap-dircolors
=========
[![Build Status](https://travis-ci.org/mkwmms/ansible-dotstrap-dircolors.svg)](https://travis-ci.org/mkwmms/ansible-dotstrap-dircolors)

Configure LS_COLORS via .dir_colors. 

Requirements
------------

OS X: [homebrew] and the latest XCode tools (to install `coreutils` for `dircolors`)

Linux: None.

Role Variables
--------------

See [default variables].

Dependencies
------------

OS X:

```
mkwmms.dotstrap-coreutils
```

Linux: None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mkwmms.dotstrap-dircolors }
```

License
-------

GPLv3

Author Information
------------------

[@mkwmms]

[@mkwmms]: https://github.com/mkwmms
[dotstrap]: https://github.com/mkwmms/dotstrap
[homebrew]: https://github.com/Homebrew/homebrew
[files]: files/
[default variables]: defaults/main.yml
[variables]: vars/main.yml
[zsh]: http://zsh.sourceforge.net
[fish]: http://fishshell.com/
