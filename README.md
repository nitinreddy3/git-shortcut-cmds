# Git Short-cut Commands

## Create a .gitconfig file in $HOME directory and add the alias as below

[alias]
  
  gco = git checkout
  
  gcm = git commit
  
  gs = git status
  
  gb = git branch
  
  hist = log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
  
  type = cat-file -t
  
  dump = cat-file -p
