Файл для изучения git
git config --global user.name "Lepelbva"
git config --global user.email "lepelbva@tut.by"

git remote add origin https://github.com/lepelbva/gittest.git

git config --list
git init
git add .
git commit -a -m "Измен2 _21-17 "
git commit -m "Git-test comment 1 ...."
git push -u origin master
изменение в 20-05 на ПК
git help # справка по всем командам     если поместить 
git clone
git status
git branch
git checkout
git merge
git remote
git fetch
git push
git pull
====  Ctrl + S  сохранить
Мои Алиасы (C:\Users\папка_вашего_пользователя\.gitconfig):
s = status --short
st = status
l = log --oneline --graph --decorate --all
g = log --graph --abbrev-commit --decorate --all --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)'
br = branch
co = checkout
