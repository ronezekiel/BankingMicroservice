# GIT Requirement
### The project is maven based microservice, which has a main file App.java.
```sh
$ mvn archetype:generate 
```

> version: 1.4
> groudId: com.ronezekiel
> artifactId: bankingmicroservice
> 
```sh
$ cat /home/ubuntu/bankingmicroservice/src/main/java/com/ronezekiel/App.java
```

### This project has a unit test program that is available in src/test/ folder
```sh
$ cat /home/ubuntu/src/test/java/com/ronezekiel/AppTest.java
```

### Create a GitHub Repository BankingMicroservice.
```sh
https://github.com/ronezekiel/BankingMicroservice
```

##### On this project there are multiple developers are working so as a Code reviewer create each branch for each developer and once they finish their development then they push the code to their own branch and you have to review the code and merge it into Master branch (A branch which has the latest code)

```sh
$ git branch dev1
$ git branch dev2
$ git branch
```
```sh 
$ git checkout dev1
$ echo "Developed by dev1" >> dev1.txt
$ git add dev1.txt
$ git commit -m "commit by dev1"
$ git push -u origin dev1
```
```sh
$ git checkout dev2
$ echo "Developed by dev2" >> dev2.txt
$ git add dev2.txt
$ git commit -m "commit by dev2"
$ git push -u origin dev2
```
```sh
$ git checkout main
$ git merge dev1
$ git merge dev2
$ git push -u origin main
```

##### You should record all the commits into local repository and once the changes are done it should be pushed to Remote GitHub Repository BankingMicroservice.

```sh
$ echo "BankingMicroservice" >> README.md
$ git add README.md
$ git commit -m "first commit"
$ git push -u origin main
```

```sh
$ git add .
$ git status
$ git commit -m "second commit"
$ git push -u origin main
```

##### On Remote Repository Create a Readme.md file which is documentation of your project.

```sh
https://github.com/ronezekiel/BankingMicroservice/blob/main/README.md
```

```sh
$ vi README.md
$ git status
$ git add README.md
$ git commit -m "documentation"
$ git push -u origin main
```
