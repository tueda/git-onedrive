# git-onedrive

Manage Git repositories on OneDrive from WSL.

```
usage: git onedrive add [<name>=origin] <repo>
   or: git onedrive clone <repo> [<dir>=<repo>]
   or: git onedrive list
commands:
   add [<name>=origin] <repo>
       Create <repo> on OneDrive if it does not exist, and add it as a remote
       named <name>.
   clone <repo> [<dir>=<repo>]
       Clone a repository <repo> on OneDrive into a newly created directory
       <dir>.
   list
       List repositories on OneDrive.
environment variable:
   GIT_ONEDRIVE_ROOT
       The path to the root directory to store the repositories on OneDrive.
```

Use at your own risk: incomplete synchronization may destroy your repositories.
