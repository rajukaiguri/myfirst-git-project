# myfirst-git-project
creating first git project 


# mygit-project
my first git project


## master branch name #                                                     feature branches
  
  master(head off all brances)------->develop(base branch)-------------------->1. user1 branch
                                                                              2. user2 branch
                                                                              3.user 3 branch

 # creating a new branch

 git checkout -b <branch-name>    Ex:- git checkout -b develop(note:- here we created base branch develop)

 # Branch nmaing conventions

 1.feature/<feature-name> -->feature/registration-page,feature/prouct-list

 2.fix/<fix-name>--->fix/fixed-login-issue,fix/loading-image-fixed

 3.hotfix/<fix-name> --->hotfix/fixed-login-issue

 ------------------------------------------------------------------------------------
 ex-- c:/REACTPROJECTWORKSPACE/mygit-project>  git checkout -b develop

 ---> git branch
 ---> git add .( sending all files at a time to repository)  
 ----> git add index.html(when we want to send single file just we are passing path after git add)

 ---->git commit -m "initial commit "
 ---->git push -u origin develop

 ## 3 steps
 1) git add<files>
 2) git commit-m <message>
 3)git push -u origin <branch-name> second time git push and later pull request

 new code