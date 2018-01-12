# LinuxCommands
This is a project containing Linux commonly used commands and descriptions.

#=========================================================
# when starting a termnial session, the current working directory is set to home directory

date                #current date and time
cal                 #calendar of the current month
df                  #free space on disk drive
free                #free memory
exit                #end the terminal session
clear               #clear all the content shown on the window
pwd                 #print name of current working directory
cd                  #change directory
ls                  #list files and directories in the current working directory
ls -a               #list files and directories including those hiden contents
ls -l               #long list with more details of files and directories
.                   #current working directory
..                  #parent directory
cd                  #change working directory to home directory
cd -                #change working directory to previous working directory
cd ~user_name       #change working directory to the home directory of usr_name, e.g. ~bob
file                #determine file type, e.g.file test.img
less                #view file contents, e.g.less /etc/password
mkdir               #create directories, e.g. mkdir dir1_test, mkdir dir1_test dir2_test dir3_test
cp                  #copy single file 'dir1_test' to 'dir2_test'
mv                  #move file from first one to second one, e.g. mv dir1_test dir2_test




##==============================================
ls 选项：
ls -a               #list all files including those hidden files starting with "."
ls -d               #list the content of directory, use with the -l option to see details about directory
ls -F               #append an indicator character to the end of each listed name, e.g.directory has indicator /
ls -h               #display file size in human readable format rather than in bytes
ls -l               #display results in long format
ls -r               #display the results in reverse format, normally results in ascending alphabetical order
ls -S               #sort results by file size
ls -t               #sort by modification time
##==============================================


##==============================================
cp 选项：
cp file1 file2      #copy file1 to fil2 (but it doesn't work for directory)
cp -i file1 file2   #if file2 exists, system will ask whether file2 will be rewrite
cp file1 file2 dir1 #
cp dir1/* dir2      #
cp -r dir1 dir2     #










##==============================================


less filename       #examine text files
cp                  #copy files and directories
mv                  #move/rename files and directories
mkdir               #make directories
rm                  #remove files and directories
ln                  #create hard and symbolic links







#==============================================
#Shell

*系统信息：
arch                         #显示机器的处理器构架（1）
uname -m                     #显示机器的处理器构架
uname -r                     #显示正在使用的内核版本
dmidecode -q                 #显示硬件系统部件（SMBIOS/DMI）
cat/proc/cpuinfo             #显示CPU info信息
cat/proc/interrupts          #显示中断
cat/proc/meminfo             #校验内存使用
cat/proc/swaps               #显示哪些swap被使用
cat/proc/version             #显示内核的版本
cat/proc/net/dev             #显示网络适配器及统计
cat/proc/mounts              #显示已加载的文件系统
date                         #显示系统日期
cal 2007                     #显示2007年的日历表
date 041217002007.00         #设置日期和时间 - 月日时分年秒
clock -w                     #将时间修改保存到BIOS


*关机：
shutdown -h now              #关闭系统（1）
poweroff                     #关闭系统
init 0                       #关闭系统（2）
telinit 0                    #关闭系统（3）
shutdown -h hours:minutes    #按预定时间关闭系统
shutdown -c                  #取消按预定时间关闭系统
shutdown -r now              #重启（1）
reboot                       #重启（2）
logout                       #注销


*挂载一个文件系统：
mount/dev/hdat2/mnt/hda2     #挂载一个叫做hda2的盘
umount/dev/hda2              #卸载一个叫做hda2的盘


*磁盘空间：
df -h                        #显示已经挂载的分区列表
du -sh dir1                  #估算目录‘dir1’已经使用的磁盘空间


*文件和目录：


*文件搜索：


*查看文件内容：


*文件的权限（使用"+"设置权限，使用"-"用于取消）：



