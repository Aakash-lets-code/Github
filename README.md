# Github
This is where you will add the description of the repository.
<br>
Author - Aakash

I am assuming you have set up your Github. Just by signing with your email.

Now, head over to this link - https://git-scm.com/downloads/win & install git and git bash to your system. If you are coder you will have vs code in your system that we are gonna use. 
<br>
After installing , open git bash.
<br>
Run git --version (to chech the verion and confirm you have installed it)
<br>
Set up your github credential in git bash , open git bash and type 
<br>
git config --global user.name "your name which you have used to create github account."
<br>
git config --global user.email "your email which you have used to create github account."(this --global means you are defining you credential to global level on your pc.)
<br>
git config --list (to check just your user name and user eamil.) 
<br>

Open vs code 

create any folder in vs code , open vs code run 
<br>
git --version (just for confirming)
head over to git hub repository. find the code button click on it , copy the HTTPS. 
<br>
head back to vs code open terminal run 
<br>
git clone "HTTPS" (That you have cloned just now, this will clone the repository you have opened in github to vs code)
<br>
In terminal type 
<br>
ls (list)
<br>
ls -a (this will show all the hidden files name, if there is .git in hidden names it means git is tracking that file for version control system)
<br>
cd (which means change directory to) "name of your file"
<br> 
pwd (present working directory to check location of the file)
<br>
run 'git status' to check the status of the file
<br>
there are four changes basically. first one untracked which means there is new file, Second modified means there is no update in a file , Third staged means the code is added and Fourth unmodified means there is update in a file.
<br>
When creating any file made changes in files you will add those changes and commit them
<br>
git add . (this will add all the changes you have made in your file)
<br>
git add "the individual file name"  
<br>
git commit -m "your message" (this will commit the changes you have made in your file)
<br>

Stast 

using stash you can temporarly remove changes and head back to your previous commit , use below codes
<br>
git stash                  # Stash all changes
<br>
git stash save "message"    # Stash with a message
<br>
git stash list              # List all stashes
<br>
git stash apply             # Apply the most recent stash
<br>
git stash apply stash@{0}   # Apply a specific stash
<br>
git stash drop stash@{0}    # Drop a specific stash
<br>
git stash clear             # Clear all stashes

Push changes

To update the code in github with changes you have made in vs code this far.
<br>
git add .
<br>
git commit -m "your message"
<br>
git push origin main ( imagin this origin as your file or repository and main refer to the branh name of repository)
<br>

Create a new repository through the vs code

If you want to create a new repository through vs code you need to run 
<br>
first 'cd ..' to exit current directory 
<br>
second mkdir "Name of directory, it will create the file"
<br>
third 'cd "Name of directory"' to enter the directory   
<br>
Now the file is created in vs code to add in the git hub create a github repository in and copy link of repo.   
<br>
Now in vs code run the below commands to link the repository with the file in vs code
<br>
git init  (this will make your vs code folder in git versoin control system)
<br>
git remote add origin "link of repository"
<br>
git remote -v (to verify the remote you just add)