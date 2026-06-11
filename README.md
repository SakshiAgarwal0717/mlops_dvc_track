First create code file
run it in terminal
track it wih git 
pip install dvc
dvc init
mkdir s3
dvc remote add -d myremote s3
dvc add data 
remove it from git 
again dvc add data 
dvc commit and dvc push
commit it with git
make changes in code 
tack with dvc status - dvc commit and dvc push 
again git commit 
the cycle continues

git log --oneline
git checkout <hash>
dvc status , dvc pull
