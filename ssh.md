# SSH介绍



# 设置ssh免密登录

核心在于将客户机的`id_rsa.pub`公钥添加到服务器的`~/.ssh/authorized_keys`文件中,且许保证`.ssh`目录权限700，`.ssh/authorized_keys`文件权限600；
步骤如下

Server:
- ssh-keygen -t rsa   # 生成id_rsa和id_rsa.pub私钥和公钥
- 将客户端的id_rsa.pub添加到服务端.ssh/authorized_keys文件中。
- 可以免密登录了

# 基于SSH的服务


