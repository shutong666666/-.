# 如何使用 PYCHARM

1.点 venv,再点 new 即可创建一个 python 脚本

2.用 control+shift+F10 可执行当下程序，用 shift+F10 可执行主要程序

3.命令行编程：

如：import sys

&#x20; print(sys.argv)

4.引入第三方库：点 file,再点 settings,再点 python interpreter python,点加号找自己所需要的第三方库，并下载。或者使用命令指令符来下载第三方库

<http://mirrors.aliyun.com/pypi/simple/> 阿里云镜像服务器

5.pychram 中快捷键整理

&#x20; 打开 settings:control+slt+s

&#x20; 运行当前代码：conrtrol+shift+F10

&#x20; 运行当前脚本：control+F10

&#x20; &#x20;

&#x20; 查找：ctrl+F

&#x20; 替换：ctrl+R

&#x20; 全局查找：ctrl+shift+F

&#x20; 全局替换：ctrl+shift+R

&#x20; 撤销：ctrl+z

&#x20; 反撤销：ctrl+shift+z

&#x20; 缩进：tab

&#x20; 反缩进：shift+tab

&#x20; 翻页：pgup/pgdn

&#x20; 行首：home

&#x20; 行尾：end

&#x20; 快速修正：alt+enter

&#x20; 快速注释：ctrl+/

&#x20; 复制代码：ctrl+D

&#x20; 删除代码：ctrl+Y

&#x20; 复写代码：ctrl+O

&#x20; 选中单词或代码块：ctrl+W

&#x20; 快速查看文档：ctrl+Q

&#x20; 模块或项目重命名：shift+F6

&#x20; 向下插入：shift+enter

&#x20; 向上插入：ctrl+alt+enter

&#x20; 查看项目视图：alt+1

&#x20; 查看结构视图：alt+7

&#x20; 切换视图：ctrl+tab

&#x20; 快速进入代码：ctrl+左键 or ctrl+B

&#x20; 快速查看历史：alt+左右方向 返回

&#x20; 快速切换方法：alt+上下

&#x20; 查看资源文件：two shift

&#x20; 查看方法从哪里被调用：ctrl+alt+H

&#x20; 查看父类：ctrl+U

&#x20; 查看继承关系：ctrl+H

6.程序调试 debug

def fun(a):

&#x20; flagflag\=2 将这行点红即设置断点后在用 debug 执行即可调试此行程序，再用 F8 一行行来调试 t

&#x20; a1\=1

&#x20; b\=1 + 2

&#x20; print(a1,b)

先下载 TDDU 库

7.TODO 注释

&#x20; def fun(a):

&#x20; flagflag\=2

&#x20; a1\=1

&#x20; b\=1 + 2

&#x20; \#TODO（“这里有一段未完成功能代码”）

&#x20; print(a1,b)
