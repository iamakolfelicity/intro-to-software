initialize a local repository 
<git init>
make commits along the way as you make the changes
< git add .>
<git commit -m"....."" >

create a remote repository
connect your local repo to the remote repo
    git remote add origin <the link of your online repo>

push-from the local repo to the remote repo
for the first time do a 'git push --setupstream origin master'
after that do 'git push origin'
    git push origin
fetch-from the remote repo to local repo
    git pull origin
