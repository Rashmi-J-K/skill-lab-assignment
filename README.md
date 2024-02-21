labo1

git clone
git init
create file b=abc.txt
git add abc.txt
git commit -m "initial"


lab02
git clone
cd
git branch
git branch -c feature-branch
git checkout feature-branch
git status
git stash
git push origin feature-branch
git fetch origin
git status

lab04

git clone
cd
create file a.txt
git add a.txt
git commit -m "first"
git push origin main
create b.txt
git add b.txt
git commit -m "second"
git push origin main
git tag v1.0
git tag
git push origin main
git push origin v1.0
create c.txt
git add c.txt
git push origin main
git checkout -b Version v1.0
git push origin Version1


lab05

gti clone
cd
create a.txt
git add a.txt
git commit -m "first"
git push origin main
git checkout -b source-branch
git branch
git add .
create b.txt
git add b.txt
git commit -m "second"
git push origin source-branch
git branch
git add .
git commit -m "third"
git push origin source-branch
git checkout main
git cherry-pick source-branch~2..source-branch
git add .
git push origin source-branch
git push origin main

lab06

git clone
cd
create f1.txt
git add f1.txt
git commit -m "first"
git push
create f2.txt
git add f2.txt
git commit -m "second"
git push
create f3.txt
git add f3.txt
git commit -m "second"
git push
create f4.txt
git add f4.txt
git commit -m "second"
git push
create f5.txt
git add f5.txt
git commit -m "second"
git push
git log
       press enter
git show copy initial git id
git log --author="Rashmi J K" --since="2024-01-30" --until="2025-12-31"


 









































