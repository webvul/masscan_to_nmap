# masscan_to_nmap
用Nmap做全网端全端口安全监控，外网IP有150个，扫描速度慢，每次需要跑2-3个小时，用这个程序，扫描只需要10-20分钟
1、使用masscan把ip端口扫描出来后，保存为json格式
2、将IP和端口提取，输入到nmap中扫描，使用多进程方法扫描
