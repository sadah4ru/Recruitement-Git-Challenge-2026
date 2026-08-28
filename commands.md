**#1**
```bash
git clone https://github.com/sadah4ru/Recruitement-Git-Challenge-2026.git # Clones the repository to your PC
cd Recruitement-Git-Challenge-2026 # Changes the current directory to the newly cloned repository folder
```

**#2**
```bash
echo "28/08/2026" > AashmanMenon.txt # Creates a new text file named AashmanMenon.txt with the date written in it
git add AashmanMenon.txt # Stages the .txt file to be included in the next commit
git commit -m "28/08/2026" # Commits the staged changes to the repository with the message "28/08/2026"
``` 

**#3**
```bash
git branch AashmanMenon # Creates a new branch named AashmanMenon
```

**#4**
```bash
git checkout AashmanMenon # Switches to the AashmanMenon branch
echo "I love playing video games, watching movies and shows and listening to music." > AM.SC.U4CYS26002.md # Creates a new markdown file with a brief description of myself.
```

**#5**
```bash
git log # Displays the commit history with the hash and commit message
echo "Commit hash of the text file: df65c4279cc00d1f44dd9004d47ff21d3c582869" >> AM.SC.U4CYS26002.md # Appends the commit hash text to the markdown file
git add AM.SC.U4CYS26002.md # Stages the markdown file
git commit -m "Commited hash and brief description" # Commits the staged file to the branch with the given string as the commit message
```

**#6**
```bash
git checkout main # Switches back to the main branch
git merge AashmanMenon # Merges all the changes and commits from the AashmanMenon branch into the main branch
```

**#7**
```bash
echo "Aashman Menon" >> README.md # Appends the text "Aashman Menon" to the README.md file
git add README.md # Stages the modified markdown file
git commit -m "Added my name to the README file" # Commits the markdown file 
```

**8**
```bash
echo "Favourite dish: Pizza" >> README.md # Appends the favourite dish text to the README.md file but it is an uncommitted change
git reset --hard HEAD # Discards all uncommitted changes, resetting files to the last commit
```
