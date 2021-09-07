# git-practice
1a. What is the commit ID of your change?
  
  dbb53bd5721b87695588089b46c97e726394a641
  
1b. Use git log to find out the time stamp for your commit
  
  Fri Sep 3 17:43:06 2021 -0400
  
2a. Use git log to find the ID and time stamp for your merged commit to hello.txt
  
  Mon Sep 6 22:00:00 2021 -0400
  
3a. How does git store changes to the repository? (1-2 sentences)
  
  The content will be stored as nodes and each commit will be regarded as snapshot. They will be stored as trees.

3b. How can local and remote repositories be synced?
  
  Use git checkout

3c. Consider the following, where the output of git status says:

On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
What does this message mean: "Your branch is ahead of 'origin/master' by 1 commit."?
  
  There is a change made that has not been pushed. i.e., there is a commit needed to be pushed.


3d. Why does Git report: "nothing to commit, working tree clean"?
  
  No change has been made since the last commit.

