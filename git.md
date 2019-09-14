# tabs in `version control view`
- Local Changes
  show the output like that of `git status`
- Log

# icons in `version control view`
- commit(tick)
- revert(discard local changes)
- diff(performs `git diff`; remember to choose a file to activate this icon)

# icons in the git section of the toolbar
- clock
the clock icon is particularly useful. after selecting a file in the project view, click the clock icon to 
show the **file history**. clicking a file doesn't automatically refresh the **file history**. an extra click
on the clock icon is necessary to refresh it.

# diff icons in different tabs
> diff icons in different tabs have different behaviors
- diif icon in **Local Changes**
this diff icon performs `git diff`.
besides **up** and **down** arrows, there are **left** and **right** arrows to navigate to previous and next file.
- diif icon in **Log**
this diff icon performs `git diff HEAD^ HEAD` given that HEAD points to the selected commit.
besides **up** and **down** arrows, there are **left** and **right** arrows to navigate to previous and next file.
- diif icon in **History**
this diff icon compares only diff for the selected file.
there are only **up** and **down** arrows to navigate inside the current file.

# choose vim or emacs for commit messages
you can choose to use vim or emacs to edit commit messages. just switch the editor to vim/emacs before committing.
