# hackoctober
free for contributions 

# Information about git and gitHub  and commands

					Open source contribution
if you want to contribute then you have to know git basic command.



what is git?
git is a basically version control system. tracks the history of changes as people and teams collaborate on projects together. As the project evolves,teams can run tests,fixs bugs and contribute new code with thw confidence that any version can be recovered at any time.Developers can reviw projecrt history to find out
  . Which changes were made?
  . who made changes?
  . when were the changes made?
  . why were chnages needed? 

What is gitHub?
Github is a basically cloud based web platform where basically used for management our projects.
lets took an example, let suppose i worked in a whatsapp project and i uploaded it on github. then contributer all over the glob can can download it in their local computer and make some schanges or contribute some code and then attached to the main project. 


What is repository?
repositry or repo is basically we can floder where  we can store all project documentation, code readme file.


what is branch?
Branch is a series of code changes.



git init :to create a blank repository


git clone : create a local copy of project that exist remotely
ex: git clone https://github.com/udacity/course-git-blog-project


note:
want to create a blank repository then use git init and if you want to work with existing project then use git clone. git clone basically create a clone project in your local computer 



Git Status:
git status is see the which file you made change. if you made no changes then "Your branch is up to date with origin/master" 
if made any changes then , modified: fileName.



Git diff:
it is for  what changes do you made or where the changes happend.
example: 
	1)Git diff filename.extension (to see perticular file changes made by you )
	2)git diff (to see the changes the whole directory changes )




Note: after changing the file if the file name shown in red that means that is not in staging so, to stage we have to use git add

Git add filename (for perticular file)
git add . (for all the changes made in directory)



Git log:
 through this command you can see all changes made by other contributer made comid in this project.
to see specif number of log then we can use
git log -5(to the last 5 line changes)



Git branch:
to see the current branch you are in.


To change your create a new branch then we use,
git checkout -b newBranchName

To Delete branch: Git branch -d new BranchName(if you are in current branch then it will give you error so to delete newBranchName first change the branch by" git checkout master" . Now you can delete the newBranchName by "git branch -d newBranchName" and to see the current branch "Git branch")



Note :
 to create a new branch : git branch banchName or git checkout - b newBranchName
 to see the current branch: git branch
 to move current braanch to another branch :  git checkout targetBranch
 to delete branch: git branch -d branchname



to remove lastest commit made :
git reset --hard HEAD^

to remove just commit but not changes:
git reset --soft HEAD^


Want to sync your local repo to web repo 
git pull


Want to add our local repo to web repo
git push



########################################################################################################################
# steps:
1. fork a project
2. clone and copy the link
3. open your local desktop create a floder and right click open git bash> git clone "paste the copy link"
4. make cahnges in project or do contribute something
5. now open git commandline> write git status
6. git add . or git add filename.extensiton
7. git statu(check for staging area)
8. git commit - m "comment what you change in 3/4 words"
9. now git push (for local to remote )
10. open github create pull request
11. and your job is done

 
