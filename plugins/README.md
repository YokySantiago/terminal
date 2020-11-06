# Git

## Aliases

Estos alias son en base al frmework OhMyZsh con el plugin [Git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git)

| Alias                                        |
|:---------------------------------------------|
| git config --global alias.a "add"                   |
| git config --global alias.aa "add --all"                  |
| git config --global alias.apa "add --patch"                 |
| git config --global alias.au "add --update"                  |
| git config --global alias.av "add --verbose"                  |
| git config --global alias.ap "apply"                  |
| git config --global alias.apt "apply --3way"                 |
| git config --global alias.b "branch"                   |
| git config --global alias.ba "branch -a"                  |
| git config --global alias.bd "branch -d"                  |
| git config --global alias.bD "branch -D"                  |
| git config --global alias.bl "blame -b -w"                  |
| git config --global alias.bnm "branch --no-merged"                 |
| git config --global alias.br "branch --remote"                  |
| git config --global alias.bs "bisect"                  |
| git config --global alias.bsb "bisect bad"                 |
| git config --global alias.bsg "bisect good"                 |
| git config --global alias.bsr "bisect reset"                 |
| git config --global alias.bss "bisect start"                 |
| git config --global alias.c "commit -v"                   |
| git config --global alias.c "commit -v --amend"!                  |
| git config --global alias.cn "commit -v --no-edit --amend"!                 |
| git config --global alias.ca "commit -v -a"                  |
| git config --global alias.ca "commit -v -a --amend"!                 |
| git config --global alias.can "commit -v -a --no-edit --amend"!                |
| git config --global alias.cans "commit -v -a -s --no-edit --amend"!               |
| git config --global alias.cam "commit -a -m"                 |
| git config --global alias.csm "commit -s -m"                 |
| git config --global alias.cb "checkout -b"                  |
| git config --global alias.cf "config --list"                  |
| git config --global alias.cl "clone --recurse-submodules"                  |
| git config --global alias.clean "clean -id"               |
| git config --global alias.pristine "reset --hard && git clean -dffx"            |
| git config --global alias.cd "checkout develop"                  |
| git config --global alias.cmsg "commit -m"                |
| git config --global alias.co "checkout"                  |
| git config --global alias.count "shortlog -sn"               |
| git config --global alias.cp "cherry-pick"                  |
| git config --global alias.cpa "cherry-pick --abort"                 |
| git config --global alias.cpc "cherry-pick --continue"                 |
| git config --global alias.cs "commit -S"                  |
| git config --global alias.d "diff"                   |
| git config --global alias.dca "diff --cached"                 |
| git config --global alias.dcw "diff --cached --word-diff"                 |
| git config --global alias.dct "describe --tags $(git rev-list --tags --max-count=1"                 |
| git config --global alias.ds "diff --staged"                  |
| git config --global alias.dt "diff-tree --no-commit-id --name-only -r"                  |
| git config --global alias.dnolock "diff $@ ":(exclude)package-lock.json" ":(exclude)&ast;.lock"             |
| git config --global alias.dv "diff -w $@ \| view -"                  |
| git config --global alias.dw "diff --word-diff"                  |
| git config --global alias.f "fetch"                   |
| git config --global alias.fa "fetch --all --prune"                  |
| git config --global alias.fg "ls-files \| git config --global alias.rep"                  |
| git config --global alias.fo "fetch origin"                  |
| git config --global alias.g "gui citool"                   |
| git config --global alias.ga "gui citool --amend"                  |
| git config --global alias.gf "push --force origin $(current_branch"                  |
| git config --global alias.gfl "push --force-with-lease origin $(current_branch"                 |
| git config --global alias.gl "pull origin $(current_branch"                  |
| git config --global alias.gp "push origin $(current_branch"                  |
| git config --global alias.gpnp "config --global alias.gl && ggp"                |
| git config --global alias.gpush "push origin "$(git_current_branch)""               |
| git config --global alias.gsup "branch --set-upstream-to=origin/$(git_current_branch"                |
| git config --global alias.gu "pull --rebase origin $(current_branch"                  |
| git config --global alias.psup "push --set-upstream origin $(git_current_branch"                |
| git config --global alias.hh "help"                  |
| git config --global alias.ignore "update-index --assume-unchanged"              |
| git config --global alias.l "pull"                   |
| git config --global alias.lg "log --stat"                  |
| git config --global alias.lgp "log --stat -p"                 |
| git config --global alias.lgg "log --graph"                 |
| git config --global alias.lgga "log --graph --decorate --all"                |
| git config --global alias.lgm "log --graph --max-count=10"                 |
| git config --global alias.lo "log --oneline --decorate"                  |
| git config --global alias.lol "log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset"                 |
| git config --global alias.lols "log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --stat"                |
| git config --global alias.lod "log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset"                 |
| git config --global alias.lods "log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset' --date=short"                |
| git config --global alias.lola "log --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --all"                |
| git config --global alias.log "log --oneline --decorate --graph"                 |
| git config --global alias.loga "log --oneline --decorate --graph --all"                |
| git config --global alias.lp "log --pretty=\<format\>"                  |
| git config --global alias.m "merge"                   |
| git config --global alias.mt "mergetool --no-prompt"                  |
| git config --global alias.mtvim "mergetool --no-prompt --tool=vimdiff"               |
| git config --global alias.ma "merge --abort"                  |
| git config --global alias.p "push"                   |
| git config --global alias.pd "push --dry-run"                  |
| git config --global alias.pf "push --force-with-lease"                  |
| git config --global alias.pf "push --force"!                 |
| git config --global alias.poat "push origin --all && git push origin --tags"                |
| git config --global alias.pu "push upstream"                  |
| git config --global alias.pv "push -v"                  |
| git config --global alias.r "remote"                   |
| git config --global alias.ra "remote add"                  |
| git config --global alias.rb "rebase"                  |
| git config --global alias.rba "rebase --abort"                 |
| git config --global alias.rbc "rebase --continue"                 |
| git config --global alias.rbd "rebase develop"                 |
| git config --global alias.rbi "rebase -i"                 |
| git config --global alias.rbs "rebase --skip"                 |
| git config --global alias.rev "revert"                 |
| git config --global alias.rh "reset"                  |
| git config --global alias.rhh "reset --hard"                 |
| git config --global alias.rm "rm"                  |
| git config --global alias.rmc "rm --cached"                 |
| git config --global alias.rmv "remote rename"                 |
| git config --global alias.rrm "remote remove"                 |
| git config --global alias.rs "restore"                  |
| git config --global alias.rset "remote set-url"                |
| git config --global alias.rss "restore --source"                 |
| git config --global alias.ru "reset --"                  |
| git config --global alias.rup "remote update"                 |
| git config --global alias.rv "remote -v"                  |
| git config --global alias.sb "status -sb"                  |
| git config --global alias.sd "svn dcommit"                  |
| git config --global alias.sh "show"                  |
| git config --global alias.si "submodule init"                  |
| git config --global alias.sps "show --pretty=short --show-signature"                 |
| git config --global alias.sr "svn rebase"                  |
| git config --global alias.ss "status -s"                  |
| git config --global alias.st "status"                  |
| git config --global alias.sta "stash push"                 |
| git config --global alias.sta "stash save"                 |
| git config --global alias.staa "stash apply"                |
| git config --global alias.stc "stash clear"                 |
| git config --global alias.std "stash drop"                 |
| git config --global alias.stl "stash list"                 |
| git config --global alias.stp "stash pop"                 |
| git config --global alias.sts "stash show --text"                 |
| git config --global alias.stu "stash --include-untracked"                 |
| git config --global alias.stall "stash --all"               |
| git config --global alias.su "submodule update"                  |
| git config --global alias.sw "switch"                  |
| git config --global alias.swc "switch -c"                 |
| git config --global alias.ts "tag -s"                  |
| git config --global alias.tv "tag \| sort -V"                  |
| git config --global alias.unignore "update-index --no-assume-unchanged"            |
| git config --global alias.up "pull --rebase"                  |
| git config --global alias.upv "pull --rebase -v"                 |
| git config --global alias.upa "pull --rebase --autostash"                 |
| git config --global alias.upav "pull --rebase --autostash -v"                |
| git config --global alias.wch "whatchanged -p --abbrev-commit --pretty=medium"                 |
| git config --global alias.am "am"                  |
| git config --global alias.amc "am --continue"                 |
| git config --global alias.ams "am --skip"                 |
| git config --global alias.ama "am --abort"                 |
| git config --global alias.amscp "am --show-current-patch"               |

