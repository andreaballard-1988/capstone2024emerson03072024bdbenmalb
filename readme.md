url -sS https://webi.sh/gh | sh

echo "# styled-sandbox" >> README.md 
git init 
git add readme.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/andreaballard-1988/capstone2024emerson03072024bdbenmalb.git
git push -u origin main

test
