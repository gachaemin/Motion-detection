# Git
---
### Three staes in Git
- Modified : Working Directory
- Staged : Staging Area
- Comitted : .git directory (Repository)
### Git config
- System level :  Affects all uses and repositories on the system (administrative) {file:/etc/gitconfig}
- Global (user) level : Affects all repositories of a current user {file:~/.config/git/config}
- Local level : Specific to the current repository {file:.git/gitconfig}
- **Each level overrides values in the previous level : system -> global -> local**
### How to use
- $ git init : Initializing a Repository in an Existing Directory
- $ git status : Checking Repository Status
- $ git add [file_name] : Adding a new file to be staged (tracked)
- $ git add . : Adding all files to be staged (tracked)
- $ git rm –cached [file_name] : Unstaging a file
- $ git commit -m “commit message” : Commit