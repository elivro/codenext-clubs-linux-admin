# Welcome

## What you'll Need

1. Your laptop
2. A GitHub account

## Overview

There are 34 levels to the [Bandit](http://overthewire.org/wargames/bandit/)
game. Each level has a specific task to complete. For most earlier levels,
you might have to read a file stored on the computer somewhere. For later
levels, the tasks might involve connecting to a port on a server (I'll
explain what those things are as we go). When you complete the task, you get
the password for the next level. You then login to the next level using the
password.

Note: Every week I'll post solutions before class to the Git repo and we'll review
the previous week's solutions together in class.

## How to play

## Rulez

1. Don't share level passwords or solutions! If someone gives you the
password, ask *how* they solved the problem instead. Try to understand their
approach.

2. I will only provide solutions for non-trivial levels. I reserve the right
to forget how to do stuff :)

3. Document your work. Keep a readme.txt with all your solutions and notes.
This makes it easier to share your thought process (and solution!).

4. Challenge yourself: Are there other solutions out there? Compare your
solution to your lab mate!

## Working with Github

We'll store all of our files on Github both so you get more experience with
Git and so I can give you feedback. In order to do that, you need to fork my
repo. After every class, we'll save all our work on Github for later.

TIP: Check out this [video](https://www.youtube.com/watch?v=f5grYMXbAV0) on
forking

TIP: Check out this [video](https://www.youtube.com/watch?v=-zvHQXnBO6c) on
synching your changes to my Git repository.

## Connecting

The Bandit landing page has all the details on how to login. This section is
just for quick reference.

If you're not logged in, you need to use port `2220`

`ssh $USERNAME@banditlabs.overthewire.org -p $PORT`

Once logged in, you can ssh to any level you know the password for:

`ssh $USERNAME@localhost`

Try to answer the following questions:

1. What is the `ssh` command used for?
2. What is the `-p` flag used for?
3. What is `localhost`?
4. Once you are logged into a level, why don't you have to give the `-p` flag to log into another level?

# HAPPY HACKING!!!
PASSWORD 1 boJ9jbbUNNfktd78OOpsqOltutMc3MY1        cat readme
PASSWORD 2 CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9        cat ./-
PASSWORD 3 UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK        cat spaces\ in\ this\ filename  (use tab to autocomplete)
PASSWORD 4 pIwrPrtPN36QITSp3EQaw936yaFoFgAB        cd ./inhere and then cat./.hidden
PASSWORD 5 koReBOKuIDDepwhWk7jZC0RTdopnAYKh        cat ./-file07
PASSWORD 6 DXjZPULLxYr17uwoI01bNLQbtFemEgo7        find -size 1033c and then cat ./inhere/maybehere07/.file2
PASSWORD 7 HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs        find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null or and then cat /var/lib/dpkg/info/bandit7.password
PASSWORD 8 cvX2JJa4CFALtqS87jk27qwqGhBM9plV        cat data.txt | grep "millionth" or grep "millionth" data.txt
PASSWORD 9 UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR        cat data.txt | sort | uniq -u 
PASSWORD 10 truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk        strings data.txt | grep"="
PASSWORD 11 IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR        base64 -d data.txt
PASSWORD 12 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu        echo "Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh" | tr 'A-Za-z' 'N-ZA-Mn-za-m'
PASSWORD 13 
