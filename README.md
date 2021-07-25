//  小米手机 小米盒子 内置 App 可精简清单工具

// Xiaomi Phone and AndroidBox MIUI App Liter

//用CMD连接上手机，无线连接用IP形式连接，数据线连接可跳过此步。

adb connect 192.168.10.250:5555		// 连接手机

adb devices		//查看可连接设备

adb shell pm list package	//查看已安装app

//更多命令查看页面尾部
