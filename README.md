# Git workshop notes

DCR 2019 git workshop notes

## Local

- `init`: initialize folder as git repo
- `status`: see what is going on in the repo
- `add`: put file(s) into staging area
- `commit`: commit files from staging area (snapshot)
- `diff`: looks at differences between commits
- `log`: looking at all your previous messages
  - `log --oneline`: get a one line representation of history
- `HEAD`: where you are currently looking at
- `checkout`: move your `HEAD` around

## Remotes

- `remote`: somewhere your git repo is stored (e.g., GitHub)
  - `origin`: the default you give your remote
- `push`: sending local changes to remote
- `pull`: receiving changes from remote

## Branches

- `branch <branch_name>`: create a new branch
- `checkout <branch_name>`: move to that branch
  - `checkout -b <branch_name>`: create and move at the same time
  - `branch -a`: see what branches we have
  - `git log --oneline --all --decorate --graph`: what is going on
  - `git switch <branch_name`: new command similar to checkout?
