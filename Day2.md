##http
###content-length range 处理分段下载

###post方法会多一个body信息

###node.js服务器搭载在nginx上的原因，当server挂了 可以挂一个error在nginx上

###请求：1.API  2.static file

###policy:same origin

###linux setting and management:mem cpu storage net(ssh ifconfig ifup/ifdown) process

###NAT ipv4 punchHole

###linux net:ipconfig: 1. eth0 2. lo  	


1. df -h 磁盘分布  （/ == root）
2. ${A} == $A 有空格需要放到大括号中
3. ll == ls	-l
4. lib 和 lib64放 dependency
5. proc：    ll /proc 可以看到正在运行的进程 然后 sudo ps aux可以看到所有的分项运行 
6. ps aux | grep ping     | == pipeline  抓住正在ping的进程
7. kill 2400  （2400是id）
8. ps aux | grep ping | grep -v grep | awk ‘{print $2}’ | xargs kill  （重点了解awk）
9. linux下的默认编辑器（ vi emacs nano gedit） 
10. ！ node %  === node app.js   （%当前编辑文件  ！相当于bash中输入指令）
11. ：%s/"/'/g
12. 在paste 模式下 可以原封不动粘贴过来