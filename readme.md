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
PASSWORD 13  8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL       mkdir /tmp/jn  cp data.txt /tmp /jn    xxd -r ./data.txt data.out  mv data.out data.gz  gunzip data.gz mv data data.tar tar -xf data.tar  tar -xf data5.bin tar -xf data6.bin tar -xf data8.bin  
PASSWORD 14 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e     ssh -i  sshkey.private bandit14@localhost  cat /etc/bandit_pass/bandit14
PASSWORD 15 BfMYroe26WYalil77FoDi9qh59eK5xNr        nc localhost 30000 or telnet localhost 30000
PASSWORD 16 cluFn7wTiGryunymYOu4RcffSxQluehd     openssl s_client -connect localhost:30001 -ign_eof
PASSWORD 17 Private Key                          nmap localhost -p 31000-32000  openssl s_client -connect localhost:31790   mkdir /tmp/passwordword cd /tmp/passwordword touch key.private chmod 600 key.private ssh -i key.private bandit17@localhost 
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----

PASSWORD 18 kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd                diff passwords.old passwords.new  
PASSWORD 19 IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x                ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme  
PASSWORD 20 GbKksEFF4yrVs6il55v6gwY5aVje5f0j                ./bandit20-do cat /etc/bandit_pass/bandit20
