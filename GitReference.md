 # <u> This file created in local and pushed to git </u>

Create a file in local

* GitReference Files is created

* File name U means unmodified 

--------------------------------------------------



`PS D:\Dev\Python\gitdumps> git status`

Untracked files:

  (use "git add <file>..." to include in what will be committed)
    GitReference.md


nothing added to commit but untracked files present (use "git add" to track)

PS D:\Dev\Python\gitdumps>




#### Untracked File U

* File created in local and present in work directory not in git


___________________________________________________


#### <u> To add file in git from local </u>

`git add [File Name]` ---->  `git add GitReference.md`

**check status again**

PS D:\Dev\Python\gitdumps> `git status`

On branch main

Your branch is up to date with 'origin/main'.

Changes to be committed:

  (use "git restore --staged <file>..." to unstage)

        new file:   GitReference.md


* File waits in Staging Area

-----------------------------------------------------------------


#### <u>Commit Files to Git</u>

`git commit -m 'New file added in git named GitReference.md'` ---> -m is message

PS D:\Dev\Python\gitdumps> `git commit -m 'New file added in git named GitReference.md'`

[main 39bcfb0] New file added in git named GitReference.md

 1 file changed, 0 insertions(+), 0 deletions(-)

 create mode 100644 GitReference.md



* Still file is not added in git next step need push file
 -----------------------------------------------------------------------------------------


 #### <u>Push File</u>


Here we can push file to specfic branch 

`PS D:\Dev\Python\gitdumps> git push origin main`

Enumerating objects: 4, done.

Counting objects: 100% (4/4), done.

Delta compression using up to 12 threads

Compressing objects: 100% (2/2), done.

Writing objects: 100% (3/3), 353 bytes | 353.00 KiB/s, done.

Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

To https://github.com/kishorevv1207/gitdumps.git

   ba59fa6..bc073a3  main -> main


* Now local file added to github page it could be visbile 


------------------------------------------------------------------------


PS D:\Dev\Python\gitdumps> git status

On branch main

Your branch is up to date with 'origin/main'.

Changes not staged for commit:

  (use "git add <file>..." to update what will be committed)

  (use "git restore <file>..." to discard changes in working directory)

        modified:   GitReference.md


no changes added to commit (use "git add" and/or "git commit -a")



-------------------------------------------------------------------------


<u>Qucik Review</u>


* File created Locally  ---> Check status    `git status`
* Add   `git add [File Name]` ---->  `git add GitReference.md` 
* Commit  `git commit -m 'New file added in git named GitReference.md'`
* Push  `git push origin main`
* check status


---------------------------------------------------------------------------


#### <u>Working on Existing Cloned Repo </u>

Working on Existing file alredy Cloned repo steps to  flowwed to push the file after changes done

* Add   `git add [File Name]` ---->  `git add GitReference.md` 
* Commit  `git commit -m 'New file added in git named GitReference.md'`
* Push  `git push origin main`
* check status



--------------------------------------------------------------------------


#### <u> File Delete</u>

Same if the file deleted locally and need change same in git same steps followed

* Delete File locally
* Add   `git add [File Name]` ---->  `git add GitReference.md` 
* Commit  `git commit -m 'New file added in git named GitReference.md'`
* Push  `git push origin main`
* check status


------------------------------------------------------------------------------------




