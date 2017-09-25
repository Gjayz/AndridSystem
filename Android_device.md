### 1.串口
1)读取设备文件：/proc/tty/drivers;  
2)类型为Serial的是串口前缀;  
3)扫描/dev目录,获取所有文件,前缀与步骤2的相同就是串口节点;  
4)获取到串口号之后就能进行串口通讯; 

### 2.WIFI信息
1)读取Android设备文件：/data/misc/wifi/*.conf;  
2)可以获取连接过的WIFI密码;

