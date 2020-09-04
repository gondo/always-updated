This repository is always up to date.

`git pull && GIT_COMMITTER_DATE="$(date)" git commit -C HEAD --amend --no-edit --date "$(date)" && git push -f`

Updates must be on `master` branch because GitHub defaults to master branch.

