# hosts文件及意义
Hosts是一个没有扩展名的系统文件，可以用记事本等工具打开，其作用就是将一些常用的网址域名与其对应的IP地址建立一个关联“数据库”，当用户在浏览器中输入一个需要登录的网址时，系统会首先自动从Hosts文件中寻找对应的IP地址，一旦找到，系统会立即打开对应网页，如果没有找到，则系统会再将网址提交DNS域名解析服务器进行IP地址的解析。

hosts路径为`/etc/hosts`



# 资源
- iHosts
- [Alfred Workflow](http://www.packal.org/workflow/hosts-file-manager)
- [老D的博客](https://laod.cn/hosts)