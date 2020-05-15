# GitHub-cmd
These are some useful git commands : 

--> To pull an existing repository : 
 ``` 
git clone 'link provided under the clone option in the repository'
```
--> After cloning , some changed are made in your local pc : This provides a summary of the changed files : 
 ``` 
git status
```
To add these changes : This does not completely add them , while sends the instructions . Action gets completed when you commit to the changes.
 ``` 
git add .
```
--> To commit : 
```
git commit -m 'message'.
```
--> To push these changes to your repo : 
```
git push origin master
```

For pulling a single file from git, you can use wget. Note that you can pull raw files only using wget

For pulling a directory e.g. https://github.com/gadepall/control/tree/master/manual,
you can use svn co https://github.com/gadepall/control/trunk/manual
just replace tree/master with trunk.
You can install svn using apt install subversion
