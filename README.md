# GitTrainingRepository
## For git training

### **Config:**
git config --global user.name "username"

git config --global user.email "email"

git config --global color.ui true

### **Create project:**
mkdir project_name

cd project_name

git init

### **Commands:**
git add file1 file2

git add .

git add *.java

git add someDir/*.java

git add someDir/

git add "*.java"

git commit -m "Message"

git status

git diff

git diff --staged

git diff COMMIT_ID

git reset --soft/--mixed/--hard HEAD/HEAD^/HEAD^^(~2/~3)

git checkout COMMIT_ID/HEAD^^/HEAD~2

git checkout branch_name

git checkout COMMIT_ID -- file_name

git checkout COMMIT_ID -- .

git commit -a -m "Message"

git commit --amend -m "New commit message"

git clean -n

git clean -f

git remote -v

git remote add REPOSITORY_NAME REPOSITORY_ADDRESS

git remote remove REPOSITORY_NAME

git push REMOTE_REPOSITORY_NAME BRANCH_NAME

git clone REMOTE_REPOSITORY_NAME
