Scenarios

1/ Clone the repository to start working
git clone https://github.com/juanonsoftware/GitCommon.git

2/ Create a branch and commit a file then push the changes to remote server
git branch -m main
git add README.md
git commit -m "Adding file README.md"
git push -u origin main

3/ Create a new branch then push to remote server
git branch -m dev-for-week1
git push -u origin dev-for-week1

4/ Create a new file on the new branch and push to the server
git add CodeForWeek1.txt
git commit -m "Adding file CodeForWeek1.txt"
git push -u origin dev-for-week1

git add README.md
git commit -m "Update file README.md"
git push -u origin dev-for-week1

5/ To check status of working folder
git status

6/ To merge a dev branch with the main in Local
git checkout main
git merge dev-for-week2
git push -u origin main