# 3rd-Repo
The third one

FROM LOCAL REPOSITORY TO REMOTE REPOSITORY

Making changes on my local VS code before staging them with the git add command

First step was to create this Repository on github
Second step was to clone it using SSH key
Third was to run the git init command to initialize it. I did this in the terminal using the git init command. 
To run the git init command, I had to be in the correct directory where the repository is stored

I have made this few edifications on VS code which I intend to stage them using git add.
Before staging them, I had to first save them in the VS code
After saving them, I used the terminal to view and stage them.

I was having a hard time finding this README on the terminal, but it was hidden inside the 'main' branch which was inside the 'master' branch

After finishing the edits and saving them in VS Code, I staged them using the 'git add README.md' comand to add them to the terminal, then I used the 'git status' to view before using the 'git commit -m' command with a "brief description of what I had done.

The final step was to push to the remote repository. For this I used the "git push origin main" command 

FROM REMOTE REPOSITORY TO LOCAL REPOSITORY

Now I am making these edits in the remote repository then I will push them to the local repository.
I will start by editing the necessary changes in the necessary branch and then preview to see the progress
Once satisfied, I then commit the changes 

After committing the changes, I then used the "git fetch origin" command to pull the changes I made into the terminal
From there, I used the "git log" to see the changes I made in the remote repository
To compare the local branch and the remote branch, I used the command "git diff origin/main"

After fetching the changes into the terminal, I used the "git pull origin main" command to send the changes to the local repository
