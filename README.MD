gi
git config --list
git config --global user.name “имя”
git config --global user.email “почта”


git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main # Ветка по умолчанию
git config --global core.autocrlf true
git config --global core.autocrlf inputc
git init
git add .
git commit -m "описание" # сделать коммит
git status -
git diff -