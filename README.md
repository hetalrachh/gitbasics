#git basics oreilly training by Daniel Chen - Git lesson

- `init`: This creates/initializes a git repository in the current directory
        - You should do this only once (no nested git repositories)
- `status`: This gives the current status of the git repository
- `add`: add the file to the staging area
- `commit`: commit the file to the repository
         - `commit -m` - commits a file with a commit message without opening a vi editor
- `log`: look at all the commit history that you have been doing
       -`log --oneline` - simple one line log view
- diff: view the difference between current state and what git knows
- `checkout`: moving our head
       - `checkout <hash> <file>`: restores file from <hash>
       - `checkout <hash>`: moves to that location
       - `git checkout master`: go back to our original place
- `HEAD`: place where we are looking at right now on our computer
- `remote`: a place where git repository is stored e.g Github
        `git remote add origin <URL>` add a remote
- `git push origin master`: to push the master branch on our local computer to a remote
- editing lines in different place is okay. you might get a merge conflict if you edit the same line/location

