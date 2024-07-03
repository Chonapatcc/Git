# easy git flow
```https://danielkummer.github.io/git-flow-cheatsheet/```

# easy push
`git add .`

`git commit -m "say hello git in C"`

`git push origin main`
# if error try
`git push -f origin main`

`git push -u origin main`
# easy pull
`git pull`

# easy clone
`git clone <git-url>`

# remove git file
`rm -rf .git`

# remove file in git repo and in filesystem
`git rm *.exe`


# cd your path
`git init`

# git config
### lab
`git config user.name "Your Name"`

`git config user.email "YourEmail@ku.th"`
### personal
`git config **--global** user.name "Your Name"`

`git config **--global** user.email "yourmail@ku.th"`

# git status 
`git status`

# git commit
`git commit -m "say hello git in C"`

`git add name.c`

`git add .` add all files :ambulance:

`git log --all --decorate --oneline --graph` to see log

# git remote add
`git remote add origin <git-url>`

`git remote remove origin` to change git url

# git push
`git branch -M main`

`git push origin main` first push need token

# git checkout

`git checkout <commit-id>` all files

`git checkout <commit-id> <filename>` some files


# git clone 
`git clone <git-url>`

# git branch
`git branch <branch-name>`
### see branch
`git branch`
### switch branch
`git checkout feature`

# git merge
### to merge feature to main
`git checkout main`

`git merge feature`

`git push origin main`

# create branch without parent history

`git checkout --orphan assets`

# delete branch

`git branch -d <branch>`

[Read more1](https://saacsos.notion.site/Git-101-212b336c391446b4a3025ac51111bd54#09066f57efea4c1288123a83bcca2619)

[Read more2](https://saacsos.notion.site/Git-102-8077dc32f73d429c94ff7fef48723281#3137c92ac1394e5293862feb8046542e)

[Read more3](https://saacsos.notion.site/git102-kasetfair-c0374f5504e7471698ec813959de3e52)

