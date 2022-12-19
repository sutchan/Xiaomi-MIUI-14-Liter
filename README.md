//  小米手机 小米盒子 内置 App 可精简清单工具

// Xiaomi Phone and AndroidBox MIUI App Liter

//用CMD连接上手机，无线连接用IP形式连接，数据线连接可跳过此步。

adb connect 192.168.10.250:5555		// 连接手机

adb devices		//查看可连接设备

adb shell pm list package	//查看已安装app

//更多命令查看页面尾部


//以下为adb常用命令，仅供备用，不用执行。

adb shell pm list packages -[option] 命令查看已经安装的应用，列出包名，后面加不同的后缀输出不同信息。

adb shell pm list packages     ####查看当前连接设备或者虚拟机的所有包

adb shell pm list packages -d    #####只输出禁用的包。

adb shell pm list packages -e    #####只输出启用的包。

adb shell pm list packages -s    #####只输出系统的包。

adb shell pm list packages -i   #####只输出包和安装信息（安装来源）。

adb shell pm list packages -u   #####只输出包和未安装包信息（安装来源）。

adb shell pm list packages -i   #####只输出包和安装信息（安装来源）。

adb shell pm list packages -f   #####输出包和包相关联的文件

adb shell pm list packages -3   #####输出所有第三方包。

adb shell pm list packages -[option] "sina"   #####按照要求搜索包。
