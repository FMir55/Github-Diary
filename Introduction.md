###Install git on linux/ubuntu
```
sudo apt-get install git
```

###Configuration(Only once)
```
git config --global user.name "user_name"
git config --global user.email "email_id"
```

###Configuration(Only once)
```
git config --global user.name "user_name"
git config --global user.email "email_id"
```

###Local repository
```
git init (folder_name)
```
(with .git)

###Create/Upload to local repository
```
gedit/vim README.md/SAMPLE.py
git add README.md/SAMPLE.py
```

###Attach commend on files(& upload to local repository)(neccessary)
```
git commit -m "message"
```

(Then create a repository on github.com)

###Set the destination of remote repository
```
git remote add origin https://github.com/user_name/Mytest.git
```

###Push from local to remote
```
git push origin master
```
