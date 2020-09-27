# reporip
This tool is solely for illustrating how stupidly easy it is to fake your GitHub profile.

## Usage
1. Clone the repo you wanna rip.
2. Create a new repo under your GitHub account.
3. Reset the remote URL of the cloned repo to your new repo.
```
git remote set-url origin URL_OF_YOUR_NEW_REPO
```
4. 
```
./rip.sh YOUR_NAME YOUR_GITHUB_EMAIL
```
5. `git push -f`
