# This is the special Repo that will direct peoople on how to connect they are script from Vs code up to it is Github Repository 
   **there ere many kind of senarion that people are facing when they want to push some content from Vs code up to they are Githhub repository**
     The following are kind of way to solve it and to archive you are senarion of pushing you are code base from local machie (Vscode) up to the Git hub repository 
  ## when you are the first o write you are Code as either from scratch or copeid from the other machine but not clone from Github

  open you are Vs code terminal and write 
  ```
     git remote -v
```
 then check who us the owner of you are file of code 
 ## IF 
 1: the answer (return after execution) is become with no anny out put like 

 ```
(.venv) adam@adam-HP-EliteBook-840-G3:~/Downloads/Stackoverflow-Clone-with-django-master/stackprj$ git remote -v
(.venv) adam@adam-HP-EliteBook-840-G3:~/Downloads/Stackoverflow-Clone-with-django-master/stackprj$
```
**that means you are file of code does not have any user so you are good to go with the following instruction**

## Initialize the git repository 
   *type this in you are terminal*

```
 git init

```

## Add all files to the stagging area 
 *type this in you are termianl*

 ```
git add .

```

## Commint the files 
*type this in you are terminal*

```
 git commit -m "you are commit wrrite here"

```

## Add the remote Repository 
*edit with a pure url of you are github repository*

```
(.venv) adam@adam-HP-EliteBook-840-G3:~/Downloads/Stackoverflow-Clone-with-django-master/stackprj$ git remote add origin https://github.com/AdamMashaka/Git_Vs_Code.git
```
## Push to you are Origin master
*if you have master in you are initialize*

```
git push -u origin master

```

    
 

    
