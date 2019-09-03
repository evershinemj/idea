# how to show idea support for svn
open `version control` view
# important icons
- update(similar to `git pull`)
- commit(similar to `git push`)
# the version control view
three essential tabs:
- local changes
  > untracked files are shown here. if the file is within a svn working copy, you can add it by right clicking and choose `add to vcs`.
- repository
  > might contain commits not contained in history(as commits can come from other working copies).
- history
  > note that history might lag behind repository. after **update**, history is synchronized with repository.
# convention for view
- green is used to represent new files(A) 
- blue is used to represent modified files(M)

both idea and visualsvn browser obey this convention.
