# Creating a New Repository
First, start by creating a new repository on https://github.com.  Once it's created the files it generated will need to be brought down to your local workspace.  You will need to clone the repository.  
**Important - Run the command below in the c:\gitRepo directory since it will create the folder.**
```
$ git clone https://github.com/mspiker/myrepo.git
```
Check what branch you are using at this point (it should be the master branch):
```
$ git branch    
* master
```
Check out the branch you want, in my case it is called 'arcified':
```
$ git checkout -b arcified origin/arcified
 Branch arcified set up to track remote branch arcified from origin.
 Switched to a new branch 'arcified'
```
Confirm you are now using the branch you wanted:
```
$ git branch    
* arcified
  master
```
If you want to update the code again later, run git pull:
```
$ git pull
Already up-to-date.
```
