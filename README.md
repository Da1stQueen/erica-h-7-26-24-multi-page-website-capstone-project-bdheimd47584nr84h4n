echo "# erica-h-7-26-24-multi-page-website-capstone-project-bdheimd47584nr84h4n" >> README.md
git init
git add README.md
git config user.name "Da1stQueen"
git config user.email "da1stqueen@gmail.com"
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Da1stQueen/erica-h-7-26-24-multi-page-website-capstone-project-bdheimd47584nr84h4n.git
curl -sS https://webi.sh/gh | sh

//Press enter to select all the defaults. Remember to copy device link and enter the code.
gh auth login

git push -u origin main

//ADD CHANGES OF ALL FILES
git add .

//ADD USER INFORMATION TO README FILE
 git commit -m "enter a commit"
 
 //ATTACHED DESCRIPTON TO THE SAVE POINT -MEMO
 "i added user info to readme"

//SYNC CHANGES TO GITHUB
git push origin main

//VIEW THE VALUE OF ORIGIN
git remote -v

//ASSISGNS A URL TO THE ORIGIN VARIABLE
git remote add origin https://github.com/Da1stQueen

//CHANGE THE VALUE OF THE ORIGIN VARIABLE
git remote add origin https://github.com/Da1stQueen

//ACTIVATE OR INTIALIZE GIT SOURCE CONTROL
git init

//RENAMES THE CURRENT BRANCH TO MAIN
git branch -M main