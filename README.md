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
git stash save "message"    # Stash with a message
git stash list              # List all stashes
git stash apply             # Apply the most recent stash
git stash apply stash@{0}   # Apply a specific stash
git stash drop stash@{0}    # Drop a specific stash
git stash clear             # Clear all stashes
