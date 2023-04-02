# bibtex4word手动加bst样式文件

有时攒到的bst样式文件在那几个映像站上没有，比如Wiley的MSP.bst，自动安装就搜索不到它，这时就需要手动安装。

## 1.检查
C:\Users\user_name\AppData\Local\Programs\MiKTeX
该目录在miktex的已知路径下。检查方法
MiKTeX Console -> 设置 -> 目录，那里有一列表，里面应该有上面的目录，若没有则添加

## 2.添加
在路径
C:\Users\user_name\AppData\Local\Programs\MiKTeX\bibtex\bst
下新建
XXX文件夹
然后拖入
XXX.bst
样式文件

## 3.刷新
MiKTeX Console -> 任务 -> 刷新文件名数据库

这时XXX样式应该就能在bibtex4word里使用了
