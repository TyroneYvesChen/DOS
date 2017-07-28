# DOS
## 常用

``` 常用
	1、git remote rm origin  删除远程路径
	2、git remote add origin [url]   添加远程路径
	3、git remote origin set-url [url]   修改远程路径
	4、git fetch 是从远程获取最新版本到本地，不会自动merge
	5、git log -p master..origin/master 比较本地的master分支和origin/master分支的差别
	6、git merge origin/master   进行合并
	7、git add -A 提交所有变化
	8、git commit -m "test" 提交到本地仓库
	9、git push origin master 提交到远程git仓库
```









## gzip

使用方法 将对应exe文件放到C:\Windows\System32目录下
``` gzip
	1、gzip *   该文件夹目录下的每个文件都压缩成.gz
	2、gzip -dv * 该文件夹目录下的每个文件解压缩
	3、gzip -l * 详细显示例1中每个压缩的文件的信息，并不解压
	4、gzip -r log.tar 压缩一个tar备份文件，此时压缩文件的扩展名为.tar.gz
	5、gzip -rv test 递归的压缩目录
	6、gzip -r . 递归的压缩目录
	7、gzip -dr test 递归的解压缩目录
	8、gunzip -r . 递归的解压缩目录
```