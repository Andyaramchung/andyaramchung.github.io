# Instructions for building/maintaining site

1. Download [Hugo](https://gohugo.io/getting-started/installing/)
2. Navigate to site directory in PowerShell or a Bash-compatible shell
3. Build site: `hugo` (hint: append flag `-D` to build drafts)
4. Serve site: `hugo server` You can also use the `-D` flag here.

#### Other Things
You might want [Visual Studio Code](https://code.visualstudio.com) to edit your
files.

To upload your files to GitHub, use [Git for Windows](https://gitforwindows.org/) and
[GitHub CLI](https://cli.github.com/).

To login to GH CLI, use `gh auth`. 

To clone your repo to your local machine, use `gh repo clone <repo>`.

To upload your files nicely and easily, use the version control tab 
(it looks like a fork) in VS Code.

You may have to run `git pull` to sync your local machine to repository in the
cloud.


To upload the changes on this website, type in "git add *"
then "git commit -m "<description of changes>"
then "git push"