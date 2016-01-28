# WorkFlowScripts
Scripts for create and push branch with github labels support

Go to projects directory and run
```
~/projects$ git clone git@github.com:basilcool/WorkFlowScripts.git
```

Allow execute and create symlink in /usr/local/bin 
```
chmod a+x WorkFlowScripts/new_feature
chmod a+x WorkFlowScripts/save_feature
sudo ln -s $(pwd)/WorkFlowScripts/new_feature /usr/local/bin/new_feature
sudo ln -s $(pwd)/WorkFlowScripts/save_feature /usr/local/bin/save_feature
```
Add GitHub auth:
replace:
```
USER=useremail@mail.com
PASS=******
```
with your real data

check remote source must be origin
```
$ git remote 
origin
```
Create brunch
```
cd Project1
~/projects/Project1$ new_feature 1234
```

Save brunch
```
~/projects/Project1$ save_feature "comment for issue"
```


... to be continue
