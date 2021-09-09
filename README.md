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

# To avoid entering Username and Pwd everytime.. during pushing .

If you are using HTTPS instead of SSH , you can follow this :


Find your remote URL (remote.origin.url) with
```
git config -l
```

Your remote URL will be like this : https://{USERNAME}@github.com/{USERNAME}/{REPONAME}.git

Execute this command : PASSWORD here refers to Personal Access Token !!
```
git config remote.origin.url https://{USERNAME}:{PASSWORD}@github.com/{USERNAME}/{REPONAME}.git
```



