# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

To link a local repo to a remote repo, you must click on the green 'Code' button on the remote repo's Github page. This will show you the SSH code to put into the terminal command which links the two repositories:
```git remote add origin [SSH code]```
After that, run these two commands:
```
    git branch -M main
    git push -u origin main
```

# Essential GitHub notes
Don't panic!
The SSH code IS NOT the SSH key! The SSH code is meant for cloning and connecting repositories. It is your friend. The SSH part comes in because the SSH key on your computer is what allows the code to work without needing to put in your username and password.
