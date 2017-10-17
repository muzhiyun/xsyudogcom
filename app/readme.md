
该文件夹下存在两个apk文件，主要用于在安卓平台运行Python脚本，两个软件使用方法略有不同。

①终端模拟器

第一次运行请链接可用的网络保证模拟器安装更新软件包。然后运行更新及安装Python环境。
apt-get update
apt-get install python

模拟器默认安装的是Python3.6版本，因此你需要将该项目中Python3文件夹内的脚本放到一个喜欢的地方，再使用cd命令切换并运行Python脚本。
例如  将Python3.py放到内存卡根目录，运行下列命令
cd /sdcard
python python3.py


②QPython编译器
直接将脚本文件放在sd卡根目录下的qpython/scripts3文件夹下，这个文件夹下主要存放程序的例程。然后打开软件，在首页点击程序找到对应的脚本，选择RUN即可。


当然，这一切都基于你设置好了server ip和username 以及password，这三个数值分别对应认证服务器的ip地址，你的用户名及密码。
