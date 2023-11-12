# Object-Thereafter
使用指南
##为系统安装git组件
git是用于项目合作和管理的基础工具。具体安装方法因系统而不同，请自行查找教程。
附官网指南链接https://git-scm.com/book/zh/v2/起步-安装-Git

##使用git所需的基本配置
打开终端（terminal），输入命令git --version，出现git版本号即说明安装成功。
输入命令git config --global user.name "你的用户名"，设置你中意的用户名。
输入命令git config --global user.email 你的电子邮件地址，设置你的可用电子邮件地址。
这些信息会在合作时作为你的身份标识符，并且可以通过再次输入命令更改。输入命令git config --list以查看已有的设置。
输入命令后回车以执行，注意使用英文标点符号。

##拉取仓库至本地
选取你中意且方便找到的的个人文件夹，在文件管理器复制其路径。
打开终端输入命令cd 刚刚复制的路径，换行后命令行开头应显示文件夹的名字。
输入命令git clone https://github.com/Astra-Glow/Object-Thereafter.git,命令执行后文件夹“Object Thereafter”应出现在先前选中的个人文件夹中。
此时
