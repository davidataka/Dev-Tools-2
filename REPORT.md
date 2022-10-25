# Команды использованные в лабороторной и скриншоты результатов
## Задание №1
>- git instaweb
>- nano .git/description
>- docker run --name devtools-db -p 5432:5432 -e POSTGRES_USER=blackbox -e POSTGRES_PASSWORD=123456 -e POSTGRES_DB=postgres -d postgres
>- npx prisma generate && npx prisma db push
>- npx ts-node prisma/seed.ts
![avatar](docs/1)
![avatar](docs/2)
## Задание №2
>- git rebase -i HEAD~4
>- git cherry-pick 32098a
>- git branch -d ci
![avatar](docs/3)
![avatar](docs/4)
![avatar](docs/5)
![avatar](docs/6)
![avatar](docs/7)
## Задание №3
>- git reflog
>- git branch old-master f95dd
![avatar](docs/8)
![avatar](docs/9)
![avatar](docs/10)
![avatar](docs/11)
## Задание №4
>- git blame -L 32,32 prisma/seed.tr
![avatar](docs/12)
## Задание №5
>- npm run test
>- git bisect start
>- git bisect bad
>- git bisect good 15d2a
![avatar](docs/13)
![avatar](docs/14)
![avatar](docs/15)
![avatar](docs/16)
## Задание №6
>- git filter-branch --index-filter 'git rm -cached --ignore-unmatch .env' HEAD
>- git blame .env
![avatar](docs/17)
![avatar](docs/18)
## Задание №7
>- git rebase -r 15d2a11 --exec 'git commit --amend --author="David Atakishiev" <davidatak@icloud.com>'
>- git blame .env
![avatar](docs/19)
![avatar](docs/20)
## Задание №8
>- git config --global rerere.enable true 
>- git merge feature
>- git rerere status 
>- git rerere diff
>- git merge --continue
>- git commit -m 'chore:update README,md'
>- git reset --hard HEAD~1
![avatar](docs/21)
![avatar](docs/22)
![avatar](docs/23)
## Задание №9
>- git log --all --graph
![avatar](docs/24)
## Задание №10
>- sudo du -sh .git
>- git gs
![avatar](docs/25)
