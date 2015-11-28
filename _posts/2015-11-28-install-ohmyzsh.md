---
layout: post
tags: 
  - Ubuntu
  - Linux
published: false
---

# Oh-my-zsh 설치하기

## 1. Ubuntu 업데이트
```
	sudo apt-get update
    sudo apt-get upgrade
```

## 2. zsh 설치
```
	sudo apt-get install zsh
```

## 3 . oh-my-zsh 설치 및 설정
```
	sudo curl -L http://install.ohmyz.sh > install.zsh
    sh install.sh
    sudo chsh -s $(which zsh) $(whoami)
    sudo vi /etc/passwd
```

> 참고: [궁극의 vimrc](https://amix.dk/vim/vimrc.html)