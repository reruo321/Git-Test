# Git Test
The space for testing git

## Clone vs Fork
Both copy Git repository but they are different.
### Clone
* Remote rep. -> Local rep. (Computer)
* Git will add a remote rep. automatically. It points to the cloned rep.
* You can push your local changes to the rep. 
### Fork
* Someone's Git rep. -> Your Git rep.
* Do not affect the original rep.

## Update Only One File in Local Repository
    git fetch
    git checkout YOUR_LOCAL_REPO_NAME/BRANCH_NAME -- YOUR_FILE_PATH
    
### Example
    git fetch
    git checkout origin/main -- .\myProject\README.md

## gh
## List of My Testing Environments
* Ubuntu 22.04 - 2023. 04. 20
