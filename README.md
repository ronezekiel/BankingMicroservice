1.)
$ mvn archetype:generate 

version: 1.4
groudId: com.ronezekiel
artifactId: bankingmicroservice

$ cat /home/ubuntu/bankingmicroservice/src/main/java/com/ronezekiel/App.java

2.)
$ cat /home/ubuntu/src/test/java/com/ronezekiel/AppTest.java

3.)

4.)
https://github.com/ronezekiel/BankingMicroservice

5.)
$ git branch dev1
$ git branch dev2
$ git branch

$ git checkout dev1
$ echo "Developed by dev1" >> dev1.txt
$ git add dev1.txt
$ git commit -m "commit by dev1"
$ git push -u origin dev1

$ git checkout dev2
$ echo "Developed by dev2" >> dev2.txt
$ git add dev2.txt
$ git commit -m "commit by dev2"
$ git push -u origin dev2

$ git checkout main
$ git merge dev1
$ git merge dev2
$ git push -u origin main

6.)

7.)
$ echo "BankingMicroservice" >> README.md
$ git add README.md
$ git commit -m "first commit"
$ git push -u origin main

$ git add .
$ git status
$ git commit -m "second commit"
$ git push -u origin main

8.)
https://github.com/ronezekiel/BankingMicroservice/blob/main/README.md

$ vi README.md
$ git status
$ git add README.md
$ git commit -m "documentation"
$ git push -u origin main
