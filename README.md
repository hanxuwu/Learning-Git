# Learning-Git


# version 0.0.1  print hello Git
git config --global user.name XXXXX
git config --global user.email XXXXX@XXX.com
git config --global --list
git clone https://github.com/XXXXXX/Learning-Git.git

Q & A

1.not a git repository (or any of the parent directories) .git
   git init

2.error: src refspec master does not match any
   There are some file in github,pull before push：
git pull origin master

3.Permission to hanxuwu/Learning-Git.git denied to zeromov:
  Manage windows Credentials


# version 0.0.2  modify the testGit and push the commit

TIPS:after clone you need to use:
> cd ./Learning-Git    to change the direction to the folder with .git   otherwise   fatal: Not a git repository (or any of the parent directories) 

then use:
> git push origin master

to push the commit