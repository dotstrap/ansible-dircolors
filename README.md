dircolors
=========
[![Build Status](https://travis-ci.org/mkwmms/ansible-dircolors.svg)](https://travis-ci.org/mkwmms/ansible-dircolors)

Configure LS_COLORS for [bash], [zsh] & [fish] shells.

Requirements
------------

OS X: [homebrew] and the latest XCode tools (to install `dircolors`).

Linux: None.

Role Variables
--------------

See [default variables].

Dependencies
------------

OS X:

```
mkwmms.coreutils
```

Linux: None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mkwmms.dircolors }
```

Notes
-----

__Warning__: This role modifies your default shell configuration file, eg.
`~/.bash_profile`, `~/.zshrc` or `~/.config/fish/config.fish`.

License
-------

GPLv3

Author Information
------------------

[@mkwmms]

[@mkwmms]: https://github.com/mkwmms
[aura]: https://github.com/aurapm/aura
[bash]: https://www.gnu.org/software/bash/manual/bashref.html
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mkwmms/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[pure]: https://github.com/sindresorhus/pure
[variables]: vars/main.yml
[variables]: vars/main.yml
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net
