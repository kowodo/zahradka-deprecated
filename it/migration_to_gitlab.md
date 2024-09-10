# Migration to Gitlab
### Step 1: Create a Gilab account
### Step 2: Create a repository on Gitlab.com
### Step 3: Git magic
1. > git clone <url-of-gitLab-repo>
2. > cd gitlabRepo
3. > git checkout main
7. > git remote add githubRemote <url-of-github-repo>
5. > git fetch githubRemote
6. > git merge githubRemote/main --allow-unrelated-histories
7. > git remote rm githubRemote
