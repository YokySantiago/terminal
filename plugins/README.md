# Git

## Aliases

Estos alias son en base al frmework OhMyZsh con el plugin [Git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git)

| Alias                                         | Command                                                                                                                          |
|:----------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------|
| git config --global alias.a                   | git add                                                                                                                          |
| git config --global alias.aa                  | git add --all                                                                                                                    |
| git config --global alias.apa                 | git add --patch                                                                                                                  |
| git config --global alias.au                  | git add --update                                                                                                                 |
| git config --global alias.av                  | git add --verbose                                                                                                                |
| git config --global alias.ap                  | git apply                                                                                                                        |
| git config --global alias.apt                 | git apply --3way                                                                                                                 |
| git config --global alias.b                   | git branch                                                                                                                       |
| git config --global alias.ba                  | git branch -a                                                                                                                    |
| git config --global alias.bd                  | git branch -d                                                                                                                    |
| git config --global alias.bD                  | git branch -D                                                                                                                    |
| git config --global alias.bl                  | git blame -b -w                                                                                                                  |
| git config --global alias.bnm                 | git branch --no-merged                                                                                                           |
| git config --global alias.br                  | git branch --remote                                                                                                              |
| git config --global alias.bs                  | git bisect                                                                                                                       |
| git config --global alias.bsb                 | git bisect bad                                                                                                                   |
| git config --global alias.bsg                 | git bisect good                                                                                                                  |
| git config --global alias.bsr                 | git bisect reset                                                                                                                 |
| git config --global alias.bss                 | git bisect start                                                                                                                 |
| git config --global alias.c                   | git commit -v                                                                                                                    |
| git config --global alias.c!                  | git commit -v --amend                                                                                                            |
| git config --global alias.cn!                 | git commit -v --no-edit --amend                                                                                                  |
| git config --global alias.ca                  | git commit -v -a                                                                                                                 |
| git config --global alias.ca!                 | git commit -v -a --amend                                                                                                         |
| git config --global alias.can!                | git commit -v -a --no-edit --amend                                                                                               |
| git config --global alias.cans!               | git commit -v -a -s --no-edit --amend                                                                                            |
| git config --global alias.cam                 | git commit -a -m                                                                                                                 |
| git config --global alias.csm                 | git commit -s -m                                                                                                                 |
| git config --global alias.cb                  | git checkout -b                                                                                                                  |
| git config --global alias.cf                  | git config --list                                                                                                                |
| git config --global alias.cl                  | git clone --recurse-submodules                                                                                                   |
| git config --global alias.clean               | git clean -id                                                                                                                    |
| git config --global alias.pristine            | git reset --hard && git clean -dffx                                                                                              |
| git config --global alias.cd                  | git checkout develop                                                                                                             |
| git config --global alias.cmsg                | git commit -m                                                                                                                    |
| git config --global alias.co                  | git checkout                                                                                                                     |
| git config --global alias.count               | git shortlog -sn                                                                                                                 |
| git config --global alias.cp                  | git cherry-pick                                                                                                                  |
| git config --global alias.cpa                 | git cherry-pick --abort                                                                                                          |
| git config --global alias.cpc                 | git cherry-pick --continue                                                                                                       |
| git config --global alias.cs                  | git commit -S                                                                                                                    |
| git config --global alias.d                   | git diff                                                                                                                         |
| git config --global alias.dca                 | git diff --cached                                                                                                                |
| git config --global alias.dcw                 | git diff --cached --word-diff                                                                                                    |
| git config --global alias.dct                 | git describe --tags $(git rev-list --tags --max-count=1)                                                                         |
| git config --global alias.ds                  | git diff --staged                                                                                                                |
| git config --global alias.dt                  | git diff-tree --no-commit-id --name-only -r                                                                                      |
| git config --global alias.dnolock             | git diff $@ ":(exclude)package-lock.json" ":(exclude)&ast;.lock"                                                                 |
| git config --global alias.dv                  | git diff -w $@ \| view -                                                                                                         |
| git config --global alias.dw                  | git diff --word-diff                                                                                                             |
| git config --global alias.f                   | git fetch                                                                                                                        |
| git config --global alias.fa                  | git fetch --all --prune                                                                                                          |
| git config --global alias.fg                  | git ls-files \| git config --global alias.rep                                                                                    |
| git config --global alias.fo                  | git fetch origin                                                                                                                 |
| git config --global alias.g                   | git gui citool                                                                                                                   |
| git config --global alias.ga                  | git gui citool --amend                                                                                                           |
| git config --global alias.gf                  | git push --force origin $(current_branch)                                                                                        |
| git config --global alias.gfl                 | git push --force-with-lease origin $(current_branch)                                                                             |
| git config --global alias.gl                  | git pull origin $(current_branch)                                                                                                |
| git config --global alias.gp                  | git push origin $(current_branch)                                                                                                |
| git config --global alias.gpnp                | git config --global alias.gl && ggp                                                                                              |
| git config --global alias.gpush               | git push origin "$(git_current_branch)"                                                                                          |
| git config --global alias.gsup                | git branch --set-upstream-to=origin/$(git_current_branch)                                                                        |
| git config --global alias.gu                  | git pull --rebase origin $(current_branch)                                                                                       |
| git config --global alias.psup                | git push --set-upstream origin $(git_current_branch)                                                                             |
| git config --global alias.hh                  | git help                                                                                                                         |
| git config --global alias.ignore              | git update-index --assume-unchanged                                                                                              |
| git config --global alias.l                   | git pull                                                                                                                         |
| git config --global alias.lg                  | git log --stat                                                                                                                   |
| git config --global alias.lgp                 | git log --stat -p                                                                                                                |
| git config --global alias.lgg                 | git log --graph                                                                                                                  |
| git config --global alias.lgga                | git log --graph --decorate --all                                                                                                 |
| git config --global alias.lgm                 | git log --graph --max-count=10                                                                                                   |
| git config --global alias.lo                  | git log --oneline --decorate                                                                                                     |
| git config --global alias.lol                 | git log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset'                           |
| git config --global alias.lols                | git log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --stat                    |
| git config --global alias.lod                 | git log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset'                           |
| git config --global alias.lods                | git log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset' --date=short              |
| git config --global alias.lola                | git log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --all                     |
| git config --global alias.log                 | git log --oneline --decorate --graph                                                                                             |
| git config --global alias.loga                | git log --oneline --decorate --graph --all                                                                                       |
| git config --global alias.lp                  | git log --pretty=\<format\>                                                                                                      |
| git config --global alias.m                   | git merge                                                                                                                        |
| git config --global alias.mt                  | git mergetool --no-prompt                                                                                                        |
| git config --global alias.mtvim               | git mergetool --no-prompt --tool=vimdiff                                                                                         |
| git config --global alias.ma                  | git merge --abort                                                                                                                |
| git config --global alias.p                   | git push                                                                                                                         |
| git config --global alias.pd                  | git push --dry-run                                                                                                               |
| git config --global alias.pf                  | git push --force-with-lease                                                                                                      |
| git config --global alias.pf!                 | git push --force                                                                                                                 |
| git config --global alias.poat                | git push origin --all && git push origin --tags                                                                                  |
| git config --global alias.pu                  | git push upstream                                                                                                                |
| git config --global alias.pv                  | git push -v                                                                                                                      |
| git config --global alias.r                   | git remote                                                                                                                       |
| git config --global alias.ra                  | git remote add                                                                                                                   |
| git config --global alias.rb                  | git rebase                                                                                                                       |
| git config --global alias.rba                 | git rebase --abort                                                                                                               |
| git config --global alias.rbc                 | git rebase --continue                                                                                                            |
| git config --global alias.rbd                 | git rebase develop                                                                                                               |
| git config --global alias.rbi                 | git rebase -i                                                                                                                    |
| git config --global alias.rbs                 | git rebase --skip                                                                                                                |
| git config --global alias.rev                 | git revert                                                                                                                       |
| git config --global alias.rh                  | git reset                                                                                                                        |
| git config --global alias.rhh                 | git reset --hard                                                                                                                 |
| git config --global alias.rm                  | git rm                                                                                                                           |
| git config --global alias.rmc                 | git rm --cached                                                                                                                  |
| git config --global alias.rmv                 | git remote rename                                                                                                                |
| git config --global alias.rrm                 | git remote remove                                                                                                                |
| git config --global alias.rs                  | git restore                                                                                                                      |
| git config --global alias.rset                | git remote set-url                                                                                                               |
| git config --global alias.rss                 | git restore --source                                                                                                             |
| git config --global alias.ru                  | git reset --                                                                                                                     |
| git config --global alias.rup                 | git remote update                                                                                                                |
| git config --global alias.rv                  | git remote -v                                                                                                                    |
| git config --global alias.sb                  | git status -sb                                                                                                                   |
| git config --global alias.sd                  | git svn dcommit                                                                                                                  |
| git config --global alias.sh                  | git show                                                                                                                         |
| git config --global alias.si                  | git submodule init                                                                                                               |
| git config --global alias.sps                 | git show --pretty=short --show-signature                                                                                         |
| git config --global alias.sr                  | git svn rebase                                                                                                                   |
| git config --global alias.ss                  | git status -s                                                                                                                    |
| git config --global alias.st                  | git status                                                                                                                       |
| git config --global alias.sta                 | git stash push                                                                                                                   |
| git config --global alias.sta                 | git stash save                                                                                                                   |
| git config --global alias.staa                | git stash apply                                                                                                                  |
| git config --global alias.stc                 | git stash clear                                                                                                                  |
| git config --global alias.std                 | git stash drop                                                                                                                   |
| git config --global alias.stl                 | git stash list                                                                                                                   |
| git config --global alias.stp                 | git stash pop                                                                                                                    |
| git config --global alias.sts                 | git stash show --text                                                                                                            |
| git config --global alias.stu                 | git stash --include-untracked                                                                                                    |
| git config --global alias.stall               | git stash --all                                                                                                                  |
| git config --global alias.su                  | git submodule update                                                                                                             |
| git config --global alias.sw                  | git switch                                                                                                                       |
| git config --global alias.swc                 | git switch -c                                                                                                                    |
| git config --global alias.ts                  | git tag -s                                                                                                                       |
| git config --global alias.tv                  | git tag \| sort -V                                                                                                               |
| git config --global alias.unignore            | git update-index --no-assume-unchanged                                                                                           |
| git config --global alias.up                  | git pull --rebase                                                                                                                |
| git config --global alias.upv                 | git pull --rebase -v                                                                                                             |
| git config --global alias.upa                 | git pull --rebase --autostash                                                                                                    |
| git config --global alias.upav                | git pull --rebase --autostash -v                                                                                                 |
| git config --global alias.wch                 | git whatchanged -p --abbrev-commit --pretty=medium                                                                               |
| git config --global alias.am                  | git am                                                                                                                           |
| git config --global alias.amc                 | git am --continue                                                                                                                |
| git config --global alias.ams                 | git am --skip                                                                                                                    |
| git config --global alias.ama                 | git am --abort                                                                                                                   |
| git config --global alias.amscp               | git am --show-current-patch                                                                                                      |

