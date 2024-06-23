# Git and Git hub


This is me following through on the process of using git and git hub for my data science projects. 

### Where am I learning from?

The processes is from Krish Naik Git and Git Hub Series. 

### The Tutorials Steps

1. First we need to move to the directory containing the files we want to commit to git hub using "cd (directory path)"

2. Secondly we need to initialize git by using "git init"

3. Thirdly we need to set up our basic configuration. This configuration is in respect to your user.username and user.emailid so that it will know where to commit it. We do this using:

 *git config --global user.name "John Doe"

 *git config --global user.email johndoe@example.com

4. We can check git status using "git status"

5. We'll see untracked files that is files not yet recognized by git hub

6. We use "git add" to add these files


7. The next thing is to commit it by using "git commit -m "first commit"

8. It is then moved to the staging environment. It is from this staging environment it is pushed to the repository. 

9. We use the command "git branch" to know the where it's being staged. If it's other than main, we use "git branch -M main" to turn it to main. 

10. We connect our local repository to the main repository using "git remote add origin (link)"

11. Use git remote -v to view repository

12. Lastly we push our code to the repository using "git push origin main"

13. If we have more than one file, we could add them by using "git add ."
