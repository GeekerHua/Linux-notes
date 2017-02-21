# 安装zsh及oh-my-zsh
## 查看已安装shell
```bash
$ cat /etc/shells
```

```bash
$ sudo apt-get install zsh
$ 		git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh $ cp ~/.zshrc ~/.zshrc.orig
$ cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
$ chsh -s /bin/zsh	# 切换到zsh
```
- 重启终端生效

