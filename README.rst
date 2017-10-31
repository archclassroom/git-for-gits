Git for gits (by gits)
======================

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

.. contents:: Table of Contents

Setup
-----

- ``sudo pacman -Syu git``

- `git-config(1)`__

- git-{init,clone}(1)

- Clone repo, add file, push commit

.. tip:: Use ``git remote -v`` to show existing remotes and their URLs.

__ https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup#Your-Identity

Version control
---------------

.. tip::
  Use ``git checkout -b <branch>`` to create and checkout a new branch for the
  feature/issue you will work on.

- git-{add,mv,rm}(1)

- gitignore(5)

.. tip:: Use ``git diff --cached`` to see staged changes.

- git-commit(1)

  - `Use imperative present tense`__
  - http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

- git-checkout(1)

.. tip:: Use ``git commit --amend`` to reword and/or change the last commit.

__ https://git-scm.com/book/en/v2/Distributed-Git-Contributing-to-a-Project

Review history
--------------

- git-diff(1)

- git-log(1)

- git-ls-files(1)

- git-reflog(1)

- git-reset(1)

- git-revert(1)

- git-show(1)

- gitrevisions(7)

.. tip:: http://jonas.nitro.dk/tig/

Distribution
------------

- git-pull(1)

- ``git pull --rebase`` while one commit ahead and behind upstream

- git-format-patch(1) can be used to manually share commits with others.

- Branch, add commit, and merge into master

Credits
-------

Thanks to meskarune, fsckd, alad, spider-mario, and all those who provide
in-class support.

Future Considerations
---------------------

- git-blame(1)

- git-grep(1)

- git-rebase(1)

- git-tag(1)

- `git-imerge`__ (suggested by spider-mario)

- Pull GitHub PR/s as branch/es (suggested by maerwald)

- Maintaining your repos:

  - Add, change, delete branches, remotes, and URLs
  - git-prune(1)
  - git-gc(1)
  - git-filter-branch(1)

- Workflow:

  - gitworkflows(7)
  - http://nvie.com/posts/a-successful-git-branching-model/
  - https://www.atlassian.com/git/tutorials/comparing-workflows

__ https://github.com/mhagger/git-imerge

Further reading
---------------

- https://git-scm.com/book/
- git-tutorial{,-2}(7) (suggested by alad)
- https://try.github.io/
- https://jwiegley.github.io/git-from-the-bottom-up/
