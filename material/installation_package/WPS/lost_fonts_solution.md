WPS for Linux安装以及字体缺失问题的解决
一、安装
1.1 官网下载wps的deb包；
1.2 下载依赖工具gdebi-core
命令：$ sudo apt-get install gdebi-core
1.3 解压
命令：$ sudo gdebi ***.deb
1.4 启动即可
方式一：查找
方式二：sh /usr/bin/wps
方式三：wpp PPT
wps word
et excel


二、字体缺失问题解决
2.1 下载字体包
2.2 新建并安装到
/usr/share/fonts/wps_symbol_fonts目录下
