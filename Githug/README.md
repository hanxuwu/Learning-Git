# Githug

1. install ruby  
`ruby --version`  
`sudo apt-get install ruby && ruby --version`  
2. install githug  
`sudo gem install githug`  
3. run githug  
`githug`  

ALL THE QUESTION  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/ALLTHEQUESTION1.PNG)  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/ALLTHEQUESTION2.PNG)  



## 1. Initialize empty Git repository  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/1.PNG)   
`cd git_hug`    
`git init`  

## 2. Config  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/2.PNG) 
`git config --global user.name zeromov`  
`git config --global user.email zeromov@163.com`  
`git config --global -l`  

## 3. There is a file in your folder called 'README',you should add it to your staging area  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/3.PNG)  
`git add README`  

## 4. commit it   
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/4.PNG)  
`git commit`  
then input the commit message and save  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/a4.PNG)   

## 5. Clone the respository at https://github.com/Gazler/cloneme.  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/5.PNG)      
`git clone https://github.com/Gazler/cloneme`  

## 6. Clone the respository at https://github.com/Gazler/cloneme to \`my\_cloned\_repo\`  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/6.PNG)   
`git clone https://github.com/Gazler/cloneme my_cloned_repo`  

## 7.ignore  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/7.PNG)   
`gedit .gitignore`  
>
Vim temporary files end with ~ so you can add to the file .gitignore the line
>
*~  
Vim also creates swap files that have the swp and swo extensions. to remove those use the lines:
>
*.swp  
*.swo  
This will ignore all the vim temporary files in a single project
>
If you want to do it globally, you can create a .gitignore file in your home (you can give it other name or location), and use the following command:
>
git config --global core.excludesfile ~/.gitignore
Then you just need to add the files you want to ignore to that file  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/7a.PNG) 


## 8. include  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/8.PNG)   
`*.a`  
`!lib.a`  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/8a.PNG)  


## 9. status  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/9.PNG)   
use git status  
`git status`  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/9a.PNG)  

## 10.number of files committed  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/10.PNG)  
`git status`  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/10a.PNG)     



## 11.rm  
`git status`  
`git rm deleteme.rb`  
![Image](https://github.com/hanxuwu/Learning-Git/blob/master/Githug/SCREENSHOT/10a.PNG)  


