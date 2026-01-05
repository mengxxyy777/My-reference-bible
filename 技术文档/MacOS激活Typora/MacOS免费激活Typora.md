# MacOS免费激活Typora

​	1、官网下载Typora.

​	2、下载任意文本编辑器，能打开稍后给出的路径即可.

​	3、用文本编辑器打开如下路径：应用程序 -> Contents -> Resources -> TypeMark.

​	4、在目录中找到page-disk -> static -> js -> LicenseIndex.180dd...

​	5、command+f，查找：e.hasActivated="true"==e.hasActivated  改为：e.hasActivated="true"=="true"

​	6、重新打开Typora即可.

