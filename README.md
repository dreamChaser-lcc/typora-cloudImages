# typora-cloudImages
typora储存的图片

若访问不了图片，或显示失败图片，替换国内dns源
- 进入 IPAddress.com
- 输入 raw.githubusercontent.com 查询真实的IP地址
- 将查到的IP 替换到hosts文件 如IP 185.199.108.133
- hosts目录 C:\Windows\System32\drivers\etc
- hosts文件添加
```
# raw.githubusercontent.com
185.199.108.133 raw.githubusercontent.com
```
- 保存成功后 
打开cmd 执行命令 
```
$ ipconfig /flushdns
```


# jsdelivr 加速访问静态资源
```
https://cdn.jsdelivr.net/gh/用户名称/仓库名称/目录
```
例如：
```
// 加速访问图片
https://cdn.jsdelivr.net/gh/dreamChaser-lcc/typora-cloudImages/typora-icon.png


// 加速访问目录 末尾一定要加/ 否则无效
https://cdn.jsdelivr.net/gh/dreamChaser-lcc/typora-cloudImages/
```
