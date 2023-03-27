## Create an initial respository

Use the command in the terminal `git init`. YOU MUST BE IN THE DIRECTORY YOU ARE WANTING TO TRACK.

- In VS Code you can right click the folder you want to start tracking and choose `Open in Integrated Terminal`


## List all the changes that Git is tracking.

Use the command in the terminal of `git status`

## Adding files to the Staging Area

Use the command in the terminal: `git add .`

## Commiting our changes and adding a message

Use the command in the terminal `git commit -m "YOUR MESSAGE HERE"`

## Setting username and email in git
`git config --global user.name "Mona Lisa"`
`git config --global user.email "MY_NAME@example.com"`
`git config --list` will allow you to verify your git settings


## Github
1. Create a respository and give it a unique name. EX:sdb-mar-2023-unit-1
2. Copy and paste the last option "push an existing respository..." into the terminal.

# Already have a repo or a github repo and you want to update with changes.

1.`git add .`
2. `git status` - to verity (optional)
3. `git commit -m "ADD NEW MESSAGE HERE"` - EX: "added styling", "fixed bug", "fixed typo"
4. `git push origin master`

