# SolveSessionProblems

[![All Contributors](https://img.shields.io/badge/all_contributors-1-red.svg?style=flat-square)](#contributors-)


<p align="center">
  <a href="https://docs.microsoft.com/en-us/learn/paths/azure-fundamentals/ "Azure fundamentals">
    <img alt="Gatsby" src="https://i.imgur.com/jm1e5Hk.jpg" width="300" />
  </a>
</p>
<h1 align="center">
  Solution to each problem
</h1>

### About

This repo for 1337 students where they can find solutions of every session problem 



# SolveSessionProblems

<img src="https://images.yourstory.com/cs/wordpress/2018/02/image_2.png" width="400" height="200">



**Problem List:**

- [x] Problem 1 : Full disk
- [x] Problem 2 : ctkahp quit unexpectedly
- [x] Problem 3 : iscsi-target problem
- [x] Problem 4 : install brew 
- [x] Problem 5 : No more .DS_Store
- [x] Problem 6 : Norminete Time-out


## Solutions : 


### Problem 1 : Full disk

easy, use this tool **[Cclean](https://github.com/su-omb/Cleaner_42)** developed by the student : Omar Bouykourne.

### Problem 2 : ctkahp quit unexpectedly

You have to remake the symbolic links to goinfre directories and also clean the Chrome cache.

### Problem 3 : iscsi-target problem 

New service is deployed **[iscsi-tools](https://iscsi-tools.1337.ma)** , so you could by yourself fix iscsi-target problems, first you have to login in intra (using your mobile phone or your peer computer) and click on fix iscsi.

### Problem 4 : install brew 

script :
```sh

#!/usr/sh 
rm -rfv $HOME/.brew && git clone --progress --verbose --depth=1 https://github.com/Homebrew/brew $HOME/.brew && echo 'export PATH=$HOME/.brew/bin:$PATH' >> $HOME/.zshrc && source $HOME/.zshrc && brew update -v 
```

### Problem 5 : No more .DS_Store

script :
```sh
  find ~Desktop -name .DS_Store -depth -exec rm {} \; 
```
### Problem 6 : Norminete Time-out

<img src="https://thijsdejong.gallerycdn.vsassets.io/extensions/thijsdejong/codam-norminette/19.10.1/1572359486186/Microsoft.VisualStudio.Services.Icons.Default" width="100" height="100">

Use this tool **[codam-norminette-plus](https://github.com/thijsdejong/codam-norminette-plus)** and you can also use this extension **[Codam Norminette](https://marketplace.visualstudio.com/items?itemName=thijsdejong.codam-norminette)**
