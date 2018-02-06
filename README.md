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

# version 0.0.3  modify the testGit and test the push in vscodeGit

Q:There is a "Push" menu item, but when I click on it, nothing happens except for a subtle progressing bar showing up and never finished. From Visual Studio Code's Docs page, I found this line: "Credential management is not handled by VSCode for now," and that page links to a GitHub page on credential helper, which is too specific for other remote server (in my case, bitbucket) and not specific enough on how to set up for VS Code.

A:  -- git config --global credential.helper wincred


# version 0.0.4  The method in version 0.0.3 doesn't work
misuse it in git shell forget to use it in git bash

use it in git bash

# version 0.0.5  The method in version 0.0.4 still doesn't work

# version 0.0.6  push the  version with wrong comment

undo the last commit in local  
try use  'the git push <remote> <branch> --force ' to amend the comment in github
git push -f  origin master     modified the github commit local history

# version 1.0.1   test Merge

# version 1.0.2   modified v1.0.1  