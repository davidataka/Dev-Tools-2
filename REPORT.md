# Команды использованные в лабороторной и скриншоты результатов
## Задание №1
>- git instaweb
>- nano .git/description
>- docker run --name devtools-db -p 5432:5432 -e POSTGRES_USER=blackbox -e POSTGRES_PASSWORD=123456 -e POSTGRES_DB=postgres -d postgres
>- npx prisma generate && npx prisma db push
>- npx ts-node prisma/seed.ts
![avatar](docs/1.png)
![avatar](docs/2.png)
## Задание №2
>- git rebase -i HEAD~4
>- git cherry-pick 32098a
>- git branch -d ci
![avatar](docs/3.png)
![avatar](docs/4.png)
![avatar](docs/5.png)
![avatar](docs/6.png)
![avatar](docs/7.png)
## Задание №3
>- git reflog
>- git branch old-master f95dd
![avatar](docs/8.png)
![avatar](docs/9.png)
![avatar](docs/10.png)
![avatar](docs/11.png)
## Задание №4
>- git blame -L 32,32 prisma/seed.tr
![avatar](docs/12.png)
## Задание №5
>- npm run test
>- git bisect start
>- git bisect bad
>- git bisect good 15d2a
![avatar](docs/13.png)
![avatar](docs/14.png)
![avatar](docs/15.png)
![avatar](docs/16.png)
## Задание №6
>- git filter-branch --index-filter 'git rm -cached --ignore-unmatch .env' HEAD
>- git blame .env
![avatar](docs/17.png)
![avatar](docs/18.png)
## Задание №7
>- git rebase -r 15d2a11 --exec 'git commit --amend --author="David Atakishiev" <davidatak@icloud.com>'
>- git blame .env
![avatar](docs/19.png)
![avatar](docs/20.png)
## Задание №8
>- git config --global rerere.enable true 
>- git merge feature
>- git rerere status 
>- git rerere diff
>- git merge --continue
>- git commit -m 'chore:update README,md'
>- git reset --hard HEAD~1
![avatar](docs/21.png)
![avatar](docs/22.png)
![avatar](docs/23.png)
## Задание №9
>- git log --all --graph
![avatar](docs/24.png)
## Задание №10
>- sudo du -sh .git
>- git gs
![avatar](docs/25.png)
## Задание №11
>-git add -p
>-git commit -m
>-git add .
![avatar](docs/26)
