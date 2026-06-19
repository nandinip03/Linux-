#LINUX:-
==========


Basics commands for linux:-
==================

pwd:- present working directory
ls:-list of files and directory
mkdir:- make directory
touch:- make empty file
clear:- screen clear
cd:- change directoty
vi:- to make & modify files
grape:- find or search files
wc:- word count
cp:- copy file from one filder to another
scp:- secure copy
mv:- file rename
rm:- file remove
head:- first 10 line shows 
tail:- last 10 line shows
wget:- to download packages
whoami:- to see which user login
shuutdown -r now :- to reboot server
shutdown -h now:- to server shutdown
uptime:- to check  server uptime
sort:- to display alphabetically
find:- to serach file or directory
locate:- to serach file or directory , it faster than find command
echo:- to output print
tty:- display the terminal that user currently logged in
uname -r:- to dispaly kernal version
chmod:- to change permission file or directory
chown:- to chaange the owner or group
lscpu:- memory information
ps -ef:- to check the active process
kill -9 id:- to kill the process

packages install or remove commands:----------------------------------
===================================

yum update:- to update all packages
yum check_update:- to display all the packages avalable on the server
yum updateinfo:- To display all package on the server.
subscription_manger identity:- display the which subscription id is there
yum history:- display yum relayed history
yum update --nobest:- install package without dependancy
yum remove http:- it will remove http


mount:- to mount the file system
unmount:- unmounting connected filesystem
lsscsi:- to lest information about storage devices
lsscsi -9 --scsiid:- to see storage lun id
lvdisply:- to diplay logical volume
vgdisplay:- to display volume group
pvdisplay;- to display physical volume
cat /var/log/messages | grep shutdown:- to check shutdown in var log messages file using pipe grape
cat /proc/meminfo:- to check memory info
lscpu:- to check cpu deatils
reboot:- to reboot the server
df -h:- to check file system usages
ping:- to check network connectivity
nslookup:- to check server
ifconfig:- to check ip adress for the server
rm -rf:- forcefuuly deleted
rmdir:- if directory is emoty then only it will remove
wc:- word count
history:- it will show alln exectued commands
su -:- switch user
cat <filename>:- to open file and see
cat -n:- it will display line numbers
lsblk:- display information about all available block devices
more:- used to view the contents of a text file one screen or apage at a time

*SED COMMANDS:-----------------------------------------
==============







*CRONTAB COMMANDS:-------------------------------------------
==================
croantab -e:- to edit crontab
croantab -l:- how to view your current cron job
crontab -r:- to delete cron


*SYSTEMCTL COMMANDS:--------------------------------------------
====================
sudo systmctl start/stop <service name>:- to use start or stop service
sudo systemctl status <srvice name>:- to check the status
sudo systmectl restart <service name>:- to reasart the service
sudo sysymectl enable <service name>:- to enable whwn server restart
sudo systemctl mask <service name>:-  to prevent the service to start
sudo sysytemctl unmask <service name>:- to check if a service is enable 
sysytemctl poweroff
systmectl reboot
systemctl -i reboot:- forecfully deleted 



df -h:- display sizes in human readable form at ( kb , mb , gb)
df -t:- add a column to the output that shows the type of file system 
df -i :- dispaly inode usages information


USERS COMMANDS:---------------------------------------------------------
--------------
sudo useradd -m <username>:- to crate the user
cat /etc/passwd:- this will check to create user or not
sudo gruoupadd <group name>:- to create the group
sudo passwd <user name>:- it will acess for new pass for user
sudo usermod -ag <group name> < user name>:- add this this user to group
/etc/passwd:- to save the passwd

=======================================================================
LVM:- LOGICAL VOLUME MANAGEMENT:-
----------------------------
lvm organize storage into three main hierarchical 
lvm is a storage mangement system in linux that allow you to create, resize, and manage disk partition

components of lvm:-
1) PV:- PHYSICAL VOLUME
                 physical disk or partition used by lvm
2) VG:- volume group
                  collection of one or more physical volume
                   act like a storage pool
3) LV:- logical volume
                   virtual partition created from a volume group 
COMMANDS :-
       1) pv display
       2) vg display
       3) lv display



