### **Class-Dump -H 报错**  
**Q :** Error:Cannot find offset for address 0xd80000000101534a in stringAtAddress  
**A ：** 由于项目使用了Swift和Oc混编，需要用到处理过的[Class - dump](https://github.com/AloneMonkey/MonkeyDev/blob/master/bin/class-dump?raw=true)，一定要给class-dump文件权限：sudo chmod 777 /usr/local/bin/class-dump
