# Git

## Aliases

Estos alias son en base al frmework OhMyZsh con el plugin [Git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git)

| Alias                                        |
|:---------------------------------------------|
| git config --global alias.a gitadd                   |
| git config --global alias.aa gitadd --all                  |
| git config --global alias.apa gitadd --patch                 |
| git config --global alias.au gitadd --update                  |
| git config --global alias.av gitadd --verbose                  |
| git config --global alias.ap gitapply                  |
| git config --global alias.apt gitapply --3way                 |
| git config --global alias.b gitbranch                   |
| git config --global alias.ba gitbranch -a                  |
| git config --global alias.bd gitbranch -d                  |
| git config --global alias.bD gitbranch -D                  |
| git config --global alias.bl gitblame -b -w                  |
| git config --global alias.bnm gitbranch --no-merged                 |
| git config --global alias.br gitbranch --remote                  |
| git config --global alias.bs gitbisect                  |
| git config --global alias.bsb gitbisect bad                 |
| git config --global alias.bsg gitbisect good                 |
| git config --global alias.bsr gitbisect reset                 |
| git config --global alias.bss gitbisect start                 |
| git config --global alias.c gitcommit -v                   |
| git config --global alias.c gitcommit -v --amend!                  |
| git config --global alias.cn gitcommit -v --no-edit --amend!                 |
| git config --global alias.ca gitcommit -v -a                  |
| git config --global alias.ca gitcommit -v -a --amend!                 |
| git config --global alias.can gitcommit -v -a --no-edit --amend!                |
| git config --global alias.cans gitcommit -v -a -s --no-edit --amend!               |
| git config --global alias.cam gitcommit -a -m                 |
| git config --global alias.csm gitcommit -s -m                 |
| git config --global alias.cb gitcheckout -b                  |
| git config --global alias.cf gitconfig --list                  |
| git config --global alias.cl gitclone --recurse-submodules                  |
| git config --global alias.clean gitclean -id               |
| git config --global alias.pristine gitreset --hard && git clean -dffx            |
| git config --global alias.cd gitcheckout develop                  |
| git config --global alias.cmsg gitcommit -m                |
| git config --global alias.co gitcheckout                  |
| git config --global alias.count gitshortlog -sn               |
| git config --global alias.cp gitcherry-pick                  |
| git config --global alias.cpa gitcherry-pick --abort                 |
| git config --global alias.cpc gitcherry-pick --continue                 |
| git config --global alias.cs gitcommit -S                  |
| git config --global alias.d gitdiff                   |
| git config --global alias.dca gitdiff --cached                 |
| git config --global alias.dcw gitdiff --cached --word-diff                 |
| git config --global alias.dct gitdescribe --tags $(git rev-list --tags --max-count=1                 |
| git config --global alias.ds gitdiff --staged                  |
| git config --global alias.dt gitdiff-tree --no-commit-id --name-only -r                  |
| git config --global alias.dnolock gitdiff $@ ":(exclude)package-lock.json" ":(exclude)&ast;.lock             |
| git config --global alias.dv gitdiff -w $@ \| view -                  |
| git config --global alias.dw gitdiff --word-diff                  |
| git config --global alias.f gitfetch                   |
| git config --global alias.fa gitfetch --all --prune                  |
| git config --global alias.fg gitls-files \| git config --global alias.rep                  |
| git config --global alias.fo gitfetch origin                  |
| git config --global alias.g gitgui citool                   |
| git config --global alias.ga gitgui citool --amend                  |
| git config --global alias.gf gitpush --force origin $(current_branch                  |
| git config --global alias.gfl gitpush --force-with-lease origin $(current_branch                 |
| git config --global alias.gl gitpull origin $(current_branch                  |
| git config --global alias.gp gitpush origin $(current_branch                  |
| git config --global alias.gpnp gitconfig --global alias.gl && ggp                |
| git config --global alias.gpush gitpush origin "$(git_current_branch)"               |
| git config --global alias.gsup gitbranch --set-upstream-to=origin/$(git_current_branch                |
| git config --global alias.gu gitpull --rebase origin $(current_branch                  |
| git config --global alias.psup gitpush --set-upstream origin $(git_current_branch                |
| git config --global alias.hh githelp                  |
| git config --global alias.ignore gitupdate-index --assume-unchanged              |
| git config --global alias.l gitpull                   |
| git config --global alias.lg gitlog --stat                  |
| git config --global alias.lgp gitlog --stat -p                 |
| git config --global alias.lgg gitlog --graph                 |
| git config --global alias.lgga gitlog --graph --decorate --all                |
| git config --global alias.lgm gitlog --graph --max-count=10                 |
| git config --global alias.lo gitlog --oneline --decorate                  |
| git config --global alias.lol gitlog --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset                 |
| git config --global alias.lols gitlog --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --stat                |
| git config --global alias.lod gitlog --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset                 |
| git config --global alias.lods gitlog --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset' --date=short                |
| git config --global alias.lola gitlog --graph --pretty='%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --all                |
| git config --global alias.log gitlog --oneline --decorate --graph                 |
| git config --global alias.loga gitlog --oneline --decorate --graph --all                |
| git config --global alias.lp gitlog --pretty=\<format\>                  |
| git config --global alias.m gitmerge                   |
| git config --global alias.mt gitmergetool --no-prompt                  |
| git config --global alias.mtvim gitmergetool --no-prompt --tool=vimdiff               |
| git config --global alias.ma gitmerge --abort                  |
| git config --global alias.p gitpush                   |
| git config --global alias.pd gitpush --dry-run                  |
| git config --global alias.pf gitpush --force-with-lease                  |
| git config --global alias.pf gitpush --force!                 |
| git config --global alias.poat gitpush origin --all && git push origin --tags                |
| git config --global alias.pu gitpush upstream                  |
| git config --global alias.pv gitpush -v                  |
| git config --global alias.r gitremote                   |
| git config --global alias.ra gitremote add                  |
| git config --global alias.rb gitrebase                  |
| git config --global alias.rba gitrebase --abort                 |
| git config --global alias.rbc gitrebase --continue                 |
| git config --global alias.rbd gitrebase develop                 |
| git config --global alias.rbi gitrebase -i                 |
| git config --global alias.rbs gitrebase --skip                 |
| git config --global alias.rev gitrevert                 |
| git config --global alias.rh gitreset                  |
| git config --global alias.rhh gitreset --hard                 |
| git config --global alias.rm gitrm                  |
| git config --global alias.rmc gitrm --cached                 |
| git config --global alias.rmv gitremote rename                 |
| git config --global alias.rrm gitremote remove                 |
| git config --global alias.rs gitrestore                  |
| git config --global alias.rset gitremote set-url                |
| git config --global alias.rss gitrestore --source                 |
| git config --global alias.ru gitreset --                  |
| git config --global alias.rup gitremote update                 |
| git config --global alias.rv gitremote -v                  |
| git config --global alias.sb gitstatus -sb                  |
| git config --global alias.sd gitsvn dcommit                  |
| git config --global alias.sh gitshow                  |
| git config --global alias.si gitsubmodule init                  |
| git config --global alias.sps gitshow --pretty=short --show-signature                 |
| git config --global alias.sr gitsvn rebase                  |
| git config --global alias.ss gitstatus -s                  |
| git config --global alias.st gitstatus                  |
| git config --global alias.sta gitstash push                 |
| git config --global alias.sta gitstash save                 |
| git config --global alias.staa gitstash apply                |
| git config --global alias.stc gitstash clear                 |
| git config --global alias.std gitstash drop                 |
| git config --global alias.stl gitstash list                 |
| git config --global alias.stp gitstash pop                 |
| git config --global alias.sts gitstash show --text                 |
| git config --global alias.stu gitstash --include-untracked                 |
| git config --global alias.stall gitstash --all               |
| git config --global alias.su gitsubmodule update                  |
| git config --global alias.sw gitswitch                  |
| git config --global alias.swc gitswitch -c                 |
| git config --global alias.ts gittag -s                  |
| git config --global alias.tv gittag \| sort -V                  |
| git config --global alias.unignore gitupdate-index --no-assume-unchanged            |
| git config --global alias.up gitpull --rebase                  |
| git config --global alias.upv gitpull --rebase -v                 |
| git config --global alias.upa gitpull --rebase --autostash                 |
| git config --global alias.upav gitpull --rebase --autostash -v                |
| git config --global alias.wch gitwhatchanged -p --abbrev-commit --pretty=medium                 |
| git config --global alias.am gitam                  |
| git config --global alias.amc gitam --continue                 |
| git config --global alias.ams gitam --skip                 |
| git config --global alias.ama gitam --abort                 |
| git config --global alias.amscp gitam --show-current-patch               |

