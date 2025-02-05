1.1:
swist@DESKTOP-NDOU684:~/csci338/lab03-exercises$ ls -a
.  ..  .git  README.md

.git is the new directory, its color coded as such in the terminal and you can cd into it.


swist@DESKTOP-NDOU684:~/csci338/lab03-exercises/.git$ ls -a
.  ..  HEAD  branches  config  description  hooks  info  objects  refs



1.2:
swist@DESKTOP-NDOU684:~/csci338/lab03-exercises$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    	README.md

nothing added to commit but untracked files present (use "git add" to track)



1.3:
swist@DESKTOP-NDOU684:~/csci338/lab03-exercises$ git status
On branch master
nothing to commit, working tree clean


1.4:
swist@DESKTOP-NDOU684:~/csci338/lab03-exercises$ git log
commit 3548d5bc2bef0e6980e355779f444f498bd44f1d (HEAD -> master)
Author: Swissssst <jimbobhe100th@gmail.com>
Date:   Wed Feb 5 15:13:20 2025 -0500

	add README.md to the repository


1.5:
swist@DESKTOP-NDOU684:~/csci338/lab03-exercises$ git diff
diff --git a/README.md b/README.md
index ae3a964..b826d95 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,3 @@
-HEADER
\ No newline at end of file
+Find All Duplicates
+
+Write a function (or static method in the case of Java) that accepts a list of integers and returns a list of only those integers that appear more than once.
\ No newline at end of file



git add: stages changes for commit

git status: shows the current status of the working directory and staging area

git log: shows commit history

git diff: shows differences between working directory, staging area, and commits

git branch: lists, creates, and deletes branches

git checkout: switches the branch or commit



Merge Pull Requests:

Create a merge commit: all commits from this branch added to the base branch

Squash and merge: combine multiple commits from this branch into one commit in the base branch

Rebase and merge: all commits from this branch get rebased and added to base branchRe
