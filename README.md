# cordova-plugin-bluetooth-print
蓝牙打印插件

## 安装插件
clone代码到本地后，把demo文件夹删除，就是插件了。
安装命令 cordova plugin add cordova-plugin-bluetooth-print

## demo使用
ionic项目，
首先运行bower install，安装ionic，jquery等的库文件
然后运行cordova platform add android，添加安卓环境和插件
cordova build android，打包apk
## 参考项目
http://blog.csdn.net/reality_jie_blog/article/details/11895843
基本思想就是通过蓝牙地址建立socket连接，然后通过流发送打印指令的字符串给打印机

## 打印指令
条码机编程手册
http://download.csdn.net/detail/superjunjin/9743834
