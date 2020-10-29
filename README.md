My own answers of [githug](https://github.com/Gazler/githug).

## Level 1
```
git init
```

## Level 2
```
git config user.email "TXYPotato@gmail.com"
git config user.name "LebronAl"
```

## Level 3
```
git add .
```

## Level 4
```
git commit -m "test"
```

## Level 5
```
git clone https://github.com/Gazler/cloneme
```

## Level 6
```
git clone https://github.com/Gazler/cloneme my_cloned_repo
```

## Level 7
```
vim .gitignore
--- content
*.swp
---
```

## Level 8
```
vim .gitignore
--- content
*.a
!lib.a
---
```

## Level 9
```
database.yml
```

## Level 10
```
2
```

## Level 11
```
git rm deleteme.rb 
```
or
```
git add .
```

## Level 12
```
git rm --cached deleteme.rb
```

## Level 13
```
git stash
```

## Level 14
```
git mv oldfile.txt newfile.txt
```
or
```
mv oldfile.txt newfile.txt
git add .
```

## Level 15
```
mkdir src
git mv *.html src
```

## Level 16
```
git log
--- content
d0bdc60ed5e44eb64f4739fe0795f6a9b0006799
---
```

## Level 17
```
git tag new_tag
```

## Level 18
```
git push origin --tags
```

## Level 19
```
git add .
git commit --amend --no-edit
```

## Level 20
```
git commit -m "test" --date="Thu Oct 30 18:41:16 2020 +0800"
```

## Level 21
```
git reset HEAD to_commit_second.rb
```

## Level 22
```
git reset --soft HEAD^
```

## Level 23
```
git checkout -- config.rb
```

## Level 24
```
git remote -v
--- content
my_remote_repo
---
```

## Level 25
```
git remote -v
--- content
https://github.com/githug/not_a_repo
---
```

## Level 26
```
git pull origin master
```

## Level 27
```
git remote add origin https://github.com/githug/githug
```

## Level 28
```
git rebase origin/master
git push origin master
```

## Level 29
```
git diff
--- content
26
---
```

## Level 30
```
git blame
--- content
Spider Man
---
```

## Level 31
```
git branch test_code
```

## Level 32
```
git checkout -b my_branch
```

## Level 33
```
git checkout v1.2
```

## Level 34
```
git checkout tags/v1.2
```

## Level 35
```
git checkout HEAD^
git checkout -b test_branch
```

## Level 36
```
git branch -d delete_me
```

## Level 37
```
git push origin test_branch:test_branch
```

## Level 38
```
git merge feature
```

## Level 39
```
git fetch origin
```

## Level 40
```
git rebase master feature
```

## Level 41
```
git rebase --onto master wrong_branch readme-update
```

## Level 42
```
git repack -d
```

## Level 43
```
git checkout new-feature
git log
git checkout master
git cherry-pick ca32a6dac7b6f97975edbe19a4296c2ee7682f68
```

## Level 44
```
git grep TODO
```

## Level 45
```
git rebase -i HEAD~2
--- content
use 'reword' and fix typo
---
```

## Level 46
```
git rebase -i HEAD~4
--- content
use 'squash' for last 3 commits
---
```

## Level 47
```
git merge --squash long-feature-branch
git commit -m"squash"
```

## Level 48
```
git rebase -i HEAD~3
---
reordering
---
```

## Level 49
```
git bisect start HEAD HEAD~19
ruby prog.rb 5
15
git bisect good
ruby prog.rb 5
11
git bisect bad
ruby prog.rb 5
15
git bisect good
ruby prog.rb 5
15
git bisect good
```

## Level 50
```
git add -e .
---
delete second feature
---
```

## Level 51
```
git reflog
---
find the branch which was checked out to current branch
---
git checkout solve_world_hunger
```

## Level 52
```
git log
git revert 2f072479e931a88019e362a54883f83c961158ce
```

## Level 53
```
git reflog
git reset --hard 9c720fc
```

## Level 54
```
git merge mybranch
---
fix conflict
---
git add .
git merge --continue
```

## Level 55
```
git submodule add https://github.com/jackmaney/githug-include-me
```