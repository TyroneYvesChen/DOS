# DOS
## gzip

使用方法
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