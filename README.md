# WorkFlowScripts
Scripts for create and push branch with github labels support

1. Put scripts in projects directory:
/projects
|__Project1
|__Project2
|__Project999
|__new_feature
|__save_feature

2. Allow to execute:
$ chmod a+x new_feature
$ chmod a+x save_feature

3. Add GitHub auth:
replace:
USER=useremail@mail.com
PASS=******
with your real data

4. check remote source must be origin
$ git remote 
origin

5. RUN
Go to Project1
cd Project1
../new_feature 1234
After this from master create new branch with name 'feature-1234'

... to be continue
