Git - Beginner's Guide

[toc]



- Git

Git is version control system used to handle small to very large projects efficiently. 

Git helps in tracking changes in the source code, enabling multiple developers to work together on non-linear development.



## Installing git on ubuntu

- Update packages

```powershell
sudo apt update
```

- Install git

```powershell
sudo apt install git
```

- Confirm that you have installed Git correctly by running the following command :

```powershell
git --version
```



## Push your first project folder to git server

- How to initialiaze git in local system

After this command it will create empty git directory under current directory.

```powershell
init git
```

- Staging

After initiate git, now check what files are there for stating area.  File have have added or not.  If file not added to staging it will show filename as red color. 

```powershell
git status
```

- Add to staging

```powershell
#### to add single file or folder
git add filename
```

```powershell
#### to add all file and folder
git add .
```

After adding you can check status by git status,  file is added to staging or no.

And then now we need to commit changes.

Note:.  Add will only add in the queue,  it will not be added to versioning,  after commit it will be added to version control.

- Commit

```powershell
git commit -m "this helps to track changes readble easy,  so write what changes you made"
```
