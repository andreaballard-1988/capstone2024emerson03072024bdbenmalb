url -sS https://webi.sh/gh | sh

echo "# styled-sandbox" >> README.md 
git init 
git add readme.md
git config user.name "andreaballard-1988"
git config user.email "dreaball28@gmail.com"
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/andreaballard-1988/capstone2024emerson03072024bdbenmalb.git
curl -sS https://webi.sh/gh | sh
gh auth login
git push -u origin main

test
