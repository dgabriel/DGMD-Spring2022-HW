# DGMD-Spring2022-HW
## Getting started with this repo

This documentation is in no way exhaustive, and almost certainly contains errors or bad ideas.  Feel free to suggest improvements as you find mistakes!

Make sure you have github set up.  I use ssh because once it’s set it makes managing your repo very simple (if you have your own way that’s obviously fine; this documentation is geared to people with little or no experience using github, so it has some 101 stuff).  If you’re using a Raspberry PI/dedicated laptop, virtual box or AWS EC2, etc., you should only have to do it once. If you’re running ROS/etc in docker, don’t forget that everything dissapears when you shut down the container & you’ll have to regen a key.

1. Follow these instructions to get yer key set up.  The Github docs are pretty thorough, so you probably don’t need me to elaborate (but ask for help if you need it) https://docs.github.com/en/authentication/connecting-to-github-with-ssh *(hint: when you initially type ssh -T git@github.com , you’ll be prompted to enter a password; this is the passphrase you used to create your ssh key)*.
2. Set up your account to avoid issues:
```bash
git config --global user.email "<your email here>"
git config --global user.name “<your github username here>”
```
3. Go to your terminal and engter the following command to get the code: 
```bash
git clone git@github.com:dgabriel/DGMD-Spring2022-HW.git
```

