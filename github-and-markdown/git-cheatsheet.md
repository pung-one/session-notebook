## Committing in a local repository

| Git command               | Git task                                         |
| ------------------------- | ------------------------------------------------ |
| `git status`              | List all files that have changed and their state |
| `git add <filename>`      | Add a file to the stage                          |
| `git commit -m "add foo"` | Create a commit including all staged files       |
| `git log --oneline`       | Show the commit history                          |
| `git restore .`           | return to state of last commit with entire repo  |
| `git restore <filename>`  | return to state of last commit with file         |

## Connecting to a remote repository

| Git command                                                               | Git task                                              |
| ------------------------------------------------------------------------- | ----------------------------------------------------- |
| `git remote add origin git@github.com:GitHubUsername/repository-name.git` | point to a specific remote repo on github.com         |
| `git branch -M main`                                                      | ?                                                     |
| `git push -u origin main`                                                 | upload or "push" local files from repo to remote repo |