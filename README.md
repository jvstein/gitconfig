# Git dotfiles
Some git things, along with my gitconfig.

## Mine
  - git-diff-wrapper (support textconv and extdiffcmd via gitattributes)
  - git-loga (distinct authors for a commit-ish using "git log")
  - git-proxy (pipe git:// over a socks proxy, e.g. via ssh)
  - git-ssh (set the ssh key used by git with the GIT_SSH_KEY env variable)
  - git-vimmerge (slightly modified version of [diffconflicts])
  - img2ascii (converts images to ASCII art using ImageMagick; used with git-diff-wrapper)

## Third party
  - [git-activity] (show ref activity; from [git-pastiche])
  - [git-contacts] (from git contrib)

[git-activity]: https://bitbucket.org/ssaasen/git-pastiche/raw/ffaaf4a499d0ed54f1f2c2cdcaab13a446f16337/man/git-activity.1
[git-contacts]: https://github.com/git/git/blob/master/contrib/contacts/git-contacts
[git-pastiche]: https://bitbucket.org/ssaasen/git-pastiche
[diffconflicts]: https://github.com/whiteinge/dotfiles/blob/master/bin/diffconflicts
