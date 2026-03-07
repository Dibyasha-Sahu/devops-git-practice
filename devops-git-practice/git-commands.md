~ Challenge Tasks
    
    Task 1: Install and Configure Git
           - Verify Git is installed on your machine
           - Set up your Git identity — name and email
           - Verify your configuration

    Task 2: Create Your Git Project
           - Create a new folder called devops-git-practice
           - Initialize it as a Git repository
           - Check the status — read and understand what Git is telling you
           - Explore the hidden .git/ directory — look at what's inside

   Task 3: Create Your Git Commands Reference
         - Create a file called git-commands.md inside the repo
         - Add the Git commands you've used so far, organized by category:
         - Setup & Config
         - Basic Workflow
         - Viewing Changes
         For each command, write:
         - What it does (1 line)
         - An example of how to use it
   Task 4: Stage and Commit
         - Stage your file
         - Check what's staged
         - Commit with a meaningful message
         - View your commit history



# For setup and config commands

~ For setup the git

I check the version of git or it installed in my machine
or not :-  git --version

Then I did the SSH key connection that I walk through the step-by-step process to connect my GitHub account to Git using SSH keys on Ubuntu.






Add the key to GitHub
- Go to GitHub → Settings → SSH and GPG keys.
- Click New SSH key.
- Paste the copied key.
- Save.

Test the connection :- ssh -T git@github.com


~ For Config the commands were:-

- git config --global user.name "your name"
- git config --global user.email "your email"
- git config --list

~ Basic Workflow of git commands:-

   Create Project
      ↓
   git init (git init)
      ↓
   Edit Files
      ↓
   git add (git add filename)
      ↓
   git commit -m "message"
      ↓
   git push (git push -u origin main)

~ Viewing Changes in git

- In Git, viewing changes means checking what files were modified, added, or deleted in your project.

   => git status (shows modified files , new files(untracked) , files ready to commit.
   
   => git diff  (shows the line-by-line differences between the last commit and current commit.

   => git diff --staged (shows the changes that are ready to be committed.)

   => git log (Displays all commits with commit ID , author , date , message)
   
   => git log --oneline (Short commit history) 
  
