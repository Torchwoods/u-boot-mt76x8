# u-boot-mt76x8 for mt76x8 V1.0.0

***
# Download

	# git clone https://github.com/Ying-Yun/u-boot-mt76x8.git

# How to use
* 1.make menuconfig
* 2.select MT7628 board
* 3.select DRAM Tyep -> DDR2
* 4.select DDR Component
* 5.make clean;make

# Note
* Press 'WPS(gpio38)' button when power on, then enter the failsafe web mode.
* change bps to 57600,fix gpio39,40,41,42 low when startup
* web failsafe IP is 192.168.1.1
* DDR2 can be 64MB or 128MB,just select 512Mbit or 1024Mbit in menuconfig
***

# wiki:
[* wiki.yystart.com](http://wiki.yystart.com)
