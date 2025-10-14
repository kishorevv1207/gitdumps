# <u>Git Hub Reference</u>

#### Advantages CLI 

* You can stage, commit, amend, stash, rebase, cherry-pick, and squash — things the web GUI doesn’t support.

##### <u> Commands to Remember </u>

* `git clone [repo origin url] `
* `git status`
* `git pull`
* `git branch` and `git branch -a`
* `dir -Force`
* `git init`
* `git add .` 
* `git commit -m 'commit message'` 
* `git push orgin [branch name]` 
* `git remote add origin [repo url]`
* `git branch -M main`  --> Remane Branch
* `git branch [new branch name]`
* `git checkout [target branch name]`
* `git merge [from branch]`
* `git pull orgin [source destination] main`



#### <u>Clone Repo</u>

* Create or open a folder in IDE 
* copy repo url from git hub repo
* used command `git clone [repo origin url]`

 #### <u> This file created in local and pushed to git </u>

Create a file in local

* GitReference Files is created
* File name U means unmodified 

--------------------------------------------------

<u>Git Status</u>

`PS D:\Dev\Python\gitdumps> git status`



* nothing added to commit but untracked files present (use "git add" to track)






#### Untracked File U

* File created in local and present in work directory not in git


___________________________________________________


#### <u> To add file in git from local </u>

`git add [File Name]` ---->  `git add GitReference.md`

**check status again**

PS D:\Dev\Python\gitdumps> `git status`




* File waits in Staging Area

-----------------------------------------------------------------


#### <u>Commit Files to Git</u>

`git commit -m 'New file added in git named GitReference.md'` ---> -m is message

PS D:\Dev\Python\gitdumps> `git commit -m 'New file added in git named GitReference.md'`




* Still file is not added in git next step need push file
 -----------------------------------------------------------------------------------------


 #### <u>Push File</u>


Here we can push file to specfic branch 

PS D:\Dev\Python\gitdumps> `git push origin main `


* Now local file added to github page it could be visbile 

-----------------------------------------------------------------------


<u>Qucik Review</u>


* File created Locally  ---> Check status    `git status`
* Add   `git add [File Name]` ---->  `git add GitReference.md` 
* Commit  `git commit -m 'New file added in git named GitReference.md'`
* Push  `git push origin main`
* check status


---------------------------------------------------------------------------


#### <u>Working on Existing Cloned Repo </u>

Working on Existing file alredy Cloned repo steps followed push the file after changes done

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

#### <u> Git Pull </u>

Git pull used to pull chenages made in repo

`git pull`

----------------------------------------------------------------------

#### <u>Create a new Repo from IDE `git init` </u>


* Create a folder
* change dir
* command `git init`
* create a multiple files
* `git add .`  -----------> this command moves all Untracked File to staging
*  `git commit -m 'commit message'` 
* ERROR : `git push orgin main` There is no main or origin branch in new repo
* create a Repo in git:
      `git remote add origin [repo url]`
* `git branch`  -----> display branch name
* RENAME BRANCH -----> `git branch -M main`
* `git push origin main`

-------------------------------------------------------------------------


#### <u> Data changes in branches to main

* Switch work branch
* `git checkout [destination brach]`
* pull recent code from main `git pull origin main`
* usuall :
      change, stage, commit, push
* now merege from work branch to main
  *  `git checkout main`
  * `git merge [work branch]`
  * `git push origin main`



