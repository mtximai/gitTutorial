# gitTutorial
<strong>Principais comandos para o Git</strong>

<h4>Como gerar uma chave ssh:</h4>
 > ssh-keygen -t rsa -b 4096 -C "seu.email@email.com"


<h3>Basic working principles</h3>
<img src="./images/git-diagram.png" />

(1) The user edit and save Readme.txt file.
    You can check the state using:
    > git status    : the file is diplayed as "Untrack"

(2) Now we need do send to staging (a packaging procedure for future commit)
    > git add Readme.txt
    
(3) The file is now is Staging.

(4) To save to Loca repository use:
    > git commit -m "Any comment"
    
(5) The file is now saved in your local repostitory

(6) To update the Remote Repository, use:
    > git push
    
(7) Now your remote repository is updated.
    You can check in your git hub account (https://github.com/yourUserName)
    
That's all.
