**Git Commands**
[x] [] git clone -- used initially to download a copy of the project for the first time
[] [] git pull -- used repeatedly during collaboration, to pull updates from team's remote changes (fetch+merge)
[] [] git pull origin main -- pull changes from the remote repo onto main branch of local repo
[] [] git fetch -- downloads latest commits without merging (changing your own branches/files)

[x] [] git status
[x] [] git add
[x] [] git commit
[x] [] git commit -am [message]
[x] [] git add [file] && git commit -m [message]
[x] [] git commit –amend -- rewrites commit message
[x] [] git log –oneline

[x] [] git push
[] [] git push -u origin [branch] -- pushes changes to a different bracnh on remote repo

[x] [] git switch -c
[x] [] git switch
[x] [x] git branch -- logs all your branches and displays active branch
[x] [] git branch -d [branch] -- delete a branch
[x] [] git merge [branch] -- combines another branch's commit in your current branch (if both branches committed, you'll get a merge commit/if both branches edited the same lines, you resolve the merge conflict by hand)
[x] [] git rebase -- combines branches by replaying your commits on top of the other branch, creating a straight-line history with no merge commit

[x] [] git diff -- shows changes that aren't added to staging area yet
[x] [] git diff --cached --shows changes that have been added to staging area, but not committed yet
[x] [] git diff main [branch] -- shows differences in the last commits between main branch and specified branch
[x] [] git diff HEAD [file] -- compares the uncommitted changes in the file from your working directory to your last commit

[x] [] git stash -- sets aside uncommitted changes to give you a clean working directory, so you can switch branches
[x] [] git stash pop -- brings your uncommitted changes back

[x] [] git restore <file> -- discards uncommitted changes to a file
[x] [] git restore –staged <file> -- remove files from staging area (unadd changes)

[x] [] git revert <commit> -- undoes a commit by creating a new commit that does the opposite
[x] [] git reset -- moves current branch back to an earlier commit (unstages changes, files untouched)
[x] [] git reset –soft -- keeps changes staged, files untouched
[x] [] git reset –hard -- staging area wiped, changes wiped
