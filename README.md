# Git

## One Time Setup

`git config --global user.name "Tim Padjen"`
`git config --global user.email "tpadjen@gmail.com"`



## Project Setup

`git init`


## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage related changes
3. Commit changes with a message


## Commands

* status -> tell me what files have been staged or committed
* add -> add a file to the stage
* git commit -m "Present tense description of what changed"

## Problems
* commit without -m "Message" => Stuck in Vim => Esc :wq
* commit with wrong message => git commit --amend -m "New message"