Git for gits
============

  Git is a free and open source distributed version control system designed to
  handle everything from small to very large projects with speed and efficiency.

  —https://git-scm.com/

https://xkcd.com/1597/

Where it's used by Arch Linux:

- https://git.archlinux.org
- https://github.com/archlinux
- https://aur.archlinux.org/packages
- https://github.com/archwomen
- https://github.com/archclassroom

.. contents:: Table of contents

ToDo
----

- Add checkboxes

- Add/Improve structure and flow, repitition & variation

  - https://mgattozzi.github.io/2016/11/08/scheme-input.html

- Assess:

  - gitcore-tutorial(7)
  - https://alexwlchan.net/a-plumbers-guide-to-git/

- Include Arch and AUR somehow

Intro
-----

- ``sudo pacman -Syu git``

- `git-config(1)`__

- git-{init,clone}(1)

.. note:: Use ``git remote -v`` to show existing remotes and their URLs.

__ https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup#Your-Identity

Version control
---------------

.. note::
  Use ``git checkout -b <branch>`` to create and checkout a new branch for the
  feature/issue you will work on.

- git-{add,mv,rm}(1)

- git-ls-files(1)

- gitignore(5)

.. note:: Use ``git diff --cached`` to see staged changes.

- git-commit(1)

  - “`A Note About Git Commit Messages`__” (written by Tim Pope)
  - `"Commit early and often"`__

- git-checkout(1)

.. note:: Use ``git commit --amend`` to reword and/or change the last commit.

- git-reset(1)

- git-revert(1)

__ https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
__ https://sethrobertson.github.io/GitBestPractices/#commit

History
-------

- git-diff(1)

- git-log(1)

- git-reflog(1)

- git-show(1)

- gitrevisions(7) (eg. ``@`` and ``-``)

.. note:: `Tig: text-mode interface for Git`__

__ http://jonas.nitro.dk/tig/

Distribution
------------

- git-merge(1)

- git-{pull,push}(1)

- ``git pull --rebase`` while one commit ahead and behind upstream

- git-format-patch(1) and git-send-email(1)

Credits
-------

Thanks to meskarune, fsckd, alad, spider-mario, and to all those who provide
in-class support.

Further reading
---------------

- “`Git from the Bottom Up`__” (written by John Wiegley) # Assess
- `Git Tutorial - Try Git`__
- git-tutorial{,-2}(7) (suggested by alad)
- “`Knowledge is Power: Getting out of trouble by understanding Git`__” (talk by Steve Smith)
- `Pro Git`__ (written by Scott Chacon and Ben Straub)

__ https://jwiegley.github.io/git-from-the-bottom-up/
__ https://try.github.io/
__ https://www.youtube.com/watch?v=sevc6668cQ0
__ https://git-scm.com/book/
