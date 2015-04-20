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

###local repository
```
git init (folder_name)
```
(with .git)

###create/upload to local repository
```
gedit/vim README.md/SAMPLE.py
git add README.md/SAMPLE.py
```

###attach commend on files(that already upload to local repository)
```
git commit -m "message"
```

(Then create a repository on github.com)

###set the destination of remote repository
```
git remote add origin https://github.com/user_name/Mytest.git
```

###push from local to remote
```
git push origin master
```
