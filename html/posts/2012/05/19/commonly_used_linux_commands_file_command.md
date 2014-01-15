## linux 常用命令——文件处理命令

分类：后台技术 | 标签：linux | 发布时间：2012-05-19 00:00:00

___

命令：ls (list)

功能：显示目录文件

权限：所有用户

语法：ls 选项[-ald] [文件或目录]

-a 显示所有文件，包括隐藏文件

-l 显示详细信息

-d 查看目录属性

___

命令：cd (change directory)

功能：切换目录

权限：所有用户

语法：cd [目录]

说明：. 和 .. 表示为两个特殊的目录，分别是当前目录和父目录

___

命令：pwd (print working directory)

功能：显示当前所在的工作目录

权限：所有用户

语法：pwd

___

命令：touch

功能：创建空文件

权限：所有用户

语法：touch [文件名]

___

命令：mkdir (make directories)

功能：创建新目录

权限：所有用户

语法：mkdir [目录名]

___

命令：cp (copy)

功能：复制文件或目录

权限：所有用户

语法：cp 选项[-R] [源文件或目录][目的目录]

-R 复制整个目录

___

命令：mv (move)

功能：移动文件、更改文件名（重命名）

权限：所有用户

语法：mv [源文件或目录][目的目录]

___

命令：rm (remove)

功能：删除文件

权限：所有用户

语法：rm 选项[-rf][文件或目录]

-r 删除目录

-f --force 强制删除，不提示确认

___

命令：cat (noncatenate and display)

功能：显示文件内容

权限：所有用户

语法：cat [文件名]

___

命令：more

功能：分页显示文件内容

权限：所有用户

语法：more [文件名]

操作：空格 或 f —— 显示下一页

enter —— 显示下一行

q 或 Q —— 退出

___

命令：head

功能：查看文件的前几行

权限：所有用户

语法：head 选项[-num] [文件名]

-num 显示文件的前 num 行

___

命令：tail

功能：查看文件的后几行

权限：所有用户

语法：tail 选项[-num/-f] [文件名]

-num 显示文件的后 num 行

-f 动态显示文件的内容

___

命令：ln (link)

功能：产生链接文件

权限：所有用户

语法：ln 选项[-s] [源文件][目标文件]

不加参数 表示创建硬链接

-s 创建软链接

说明：软链接相当于快捷方式，硬链接相当于拷贝+同步