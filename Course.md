# Git

# Introduction

- Invented to keep track of the change happening in the source code of linux
- Git is a protocole to keep the file and the modification that happened to it through time and people
- GitHub is a web plateform. (recently bought by Microsoft)
  - To host files, and use the git protocole.
  - Central point of the opensource community to get and share code (follow, like, fork, watch)
  - Great visibility as a developper
  - Similar webites exist : GitLab, Bitbucket, your own ?

# Tools

- download git protocol from https://git-scm.com/download/
- create an account on the GitHub plateform website
- download github desktop from https://desktop.github.com/

# Process
0 - Create a git repo
  - command line : git init
  - GitHub Desktop : "Add existing repo"
  - You can create a .gitignore file to specify files/folders to ignore for the sync up

1 - 'Add' (git add *) -> What local files are going to change
2 - 'Commit' (git commit -m 'your comment') -> take a snapshot of your LOCAL modifications and name them
3 - 'Push' (git push master) -> Collects all LOCAL commits and put them ONLINE
4 - 'Deploy' (no CLI / rely on Continuous Integration) -> All change to the source code get built together on the final website (replace the drap on drop on Netlify)

"fetch" is a command to check is their are update on the ONLINE repository
"pull" when you need to download modification from the ONLINE repository