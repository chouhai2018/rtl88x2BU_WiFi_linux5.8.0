#安装准备

sudo apt install build-essential cmake

#安装
git clone https://github.com/chouhai2018/rtl88x2BU_WiFi_linux5.8.0.git

cd rtl88x2BU_WiFi_linux

sudo make

sudo make install

重启系统，插上usb网卡就可以使用了

#系统支持 
ubuntu 20.10 kennel 5.8.0+

相应ubuntu派生版本同支持

树梅派支持同ubuntu core版本

修改自官方驱动
