#### 员工门禁卡模板示例

> Foxconn富士康



附录：[git教程](https://www.runoob.com/git/git-create-repository.html)

Git基础命令：

1. 查看当前remote个数
```
git remote -v
```
2. 添加新的remote
```
git remote add origin git@github.com:local-host-8080/EmployeeregisterExample.git
```
3. 删除一个remote
```
git remote rm origin
```
4. 项目所有文件添加到缓存区
```
git add .
```
5. 提交更改
```
git commit -m "这里填提交的描述"
```
6. 上传、下载远程代码并合并
```
git push -u origin master
git push -u origin main

git pull origin main            ---拉代码
git clone <repo> <directory>    ---克隆/下载
```
7. 设置提交代码时的用户信息
```
git config --global user.name 'local-host-8080'
git config --global user.email test@qq.com
```