# Git_instruction

Adding locally hosted code to GitHub

`git init`

`git add .`

`git commit -m "First commit"`

At the top of your repository on GitHub.com's Quick Setup page, click  to copy the remote repository URL

`git remote add origin  <REMOTE_URL>`

`git remote -v`

`gir config http.postBuffer 524288000` see [this page](https://stackoverflow.com/questions/15240815/git-fatal-the-remote-end-hung-up-unexpectedly/)

`git push --set-upstream origin master`

In case there are large files, this might throws errors: 

Only remving the file from the local repository won't help, 

To remove from git history(details in [this page](https://stackoverflow.com/questions/33360043/git-error-need-to-remove-large-file/)):

`git filter-branch --tree-filter 'rm -rf fallingData_allvar_fullstat.csv' HEAD`

In case enccountered with the following error:

**_"Support for password authentication was removed. Please use a personal access token instead."_**

Follow the instructions at [this page](https://stackoverflow.com/questions/68775869/message-support-for-password-authentication-was-removed-please-use-a-personal/)

Besides reading the instruction for MAC OS, read the instructions for WINDOWS OS as well to get the full idea.
