对于zet-e8820v2，谋求原版openwrt自行修改dts不是业余人士能干的，我努力了一个多星期宣告放弃，目前找到的可用代码库是siwind的，他已经增补了dts等文件，虽然代码库不如原始openwrt/openwrt那么新，但好用。

---------------------------------------
目前成果：

master版本编译正常，刷机能启动，运行良好。固件里只安装了uci-app-uhttpd，luci-app-firewall两个，还有kmod-usb-print。

19.07版本编译错误，估计要找到2年前的19.07代码快照才行。

对于zet-e8820s，我也打算再用siwind的库编译下。
