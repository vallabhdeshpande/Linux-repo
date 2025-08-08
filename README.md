# Linux-repo

Steps to Upload File through PUTTY(Windows) or Terminal(Linux)

Step 1: Install  Git 
        dnf install git -y

Step 2: Set configuration with git
        1. git config --global user.name "Your username"
        2. git config --global user.mail "Your Email ID"

Step 3: Create Token key for GitHub Login
        
        open GitHub > Settings > Developer settings > Persnal access tokens         > Tokens(classic) > Generate new token > classic > Done

Step 4: Clone your Repository in your system
        1. git clone "Your Repo URL"

Step 5: Go to that Path 
        1. cd "Your Repo path"

Step 6: Create/ Copy your Source file which want to upload on GitHub
        1. vi Demo.txt

Step 7: Add those files to the staging area
        1. git add Demo.txt (for select single file)
        2. git add . (for select all files)

Step 8: Commit the staged files:
        1. git commit -m "Your descriptive commit message"

Step 9: Push the commits to the remote repository:
        1. git push "Your descriptive commit message" <branch-name>
        
        ex: git push origin main

Your file has been uploaded successfully...!!!
