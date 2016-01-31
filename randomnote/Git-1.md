#First Glance at Git and Github

###1. Install git
		just choose default all the way.
		
###2. Generate SSH Key
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

###3. Add SSH Key to SSH-Agent
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

###4. Add SSH Key to github
```
clip < ~/.ssh/id_rsa.pub
```
Paste it in Settings->[SSH Keys](https://github.com/settings/ssh)

###5. Configure user information
```
git config --global user.name "____"
git config --global user.email "your primary email of github"
```

###6. Create a [new](https://github.com/new) repo in guthub
###7. Init a repo in a local folder
###8. Add origin
```
git remote add origin _____
```
###9. etc
```
git pull _______
git add .
git commit -m "_____"
git push _______
```

