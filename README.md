Command line instructions


Git global setup

git config --global user.name "Cesar Coelho"
git config --global user.email "cesaraug@gmail.com"

Create a new repository

git clone https://CesarCoelhoApp@gitlab.com/CesarCoelhoApp/Aula_React.git
cd Aula_React
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder

cd existing_folder
git init
git remote add origin https://CesarCoelhoApp@gitlab.com/CesarCoelhoApp/Aula_React.git
git add .
git commit
git push -u origin master

Existing Git repository

cd existing_repo
git remote add origin https://CesarCoelhoApp@gitlab.com/CesarCoelhoApp/Aula_React.git
git push -u origin --all
git push -u origin --tags