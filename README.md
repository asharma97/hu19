yum install docker* -y
systemctl restart docker 
systemctl enable docker


git clone https://github.com/asharma97/hu19.git 
cd hu19
ls
git checkout -b git-assignment 
git branch 
cd .git


vim secret ------- save username and password
cd ..
git add .
git commit -m "secret"
git push origin git-assignment

vim SECURITY.md 
git add .
git commit -m "security"
git push origin git-assignment



