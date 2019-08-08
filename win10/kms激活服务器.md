# kms激活服务器
[TOC]
> 现在kms激活方式非常流行，主要用于激活win8、win10、office2010、office2013和office2016等微软系统和办公软件，kms服务器多数是由个人或组织搭建的，可能会失效，所以我们用kms服务器激活之前，需要判断能不能正常使用。
## 测试原理:
1. 用ping命令，Ping命令是对一个网址发送测试数据包，看对方网址是否有响应并统计响应时间，以此测试对方网络是否可以连接。
2. 通用方法：直接用Windows+R组合键打开运行，输入cmd打开命令提示符，输入命令 ping+kms服务器，按回车执行。其中windows是徽标键，在ctrl和alt中间。 
3. 通过ping命令的返回，判断kms激活服务器的可用性。
4. 在slmgr中设置kms服务器
   > slmgr /skms kms.03k.org \
   > slmgr /ato 
