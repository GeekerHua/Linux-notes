# 恢复默认英文
修改Ubuntu的配置文件`/etc/default/locale`
将原来的配置内容修改为
```bash
LANG=”en_US.UTF-8″
LANGUAGE=”en_US:en”
```

再在终端下运行：
```bash
$ locale-gen -en_US:en
```

注销或重启后，Ubuntu Server真正服务器实体终端就恢复成了英文的语言环境。

# service
- service --status--all
    - 显示Ubuntu下启动的程序。

