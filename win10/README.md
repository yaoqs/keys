# Win10 keys
[TOC]
## win10密钥须知：
win10激活码都有激活次数的限制，而且容易被官方封禁，所以不能保证100%可用，win10序列号不能用时，大家可以用激活工具来激活，市面上的激活工具都是KMS激活，KMS是180天激活，到期后可反复激活进行续期，或下载安装ghost Windows10免激活系统。

## 密钥更新：win10企业版(政府版)400年期限密钥
* 【EnterpriseG】FV469-WGNG4-YQP66-2B2HY-KD8YX
* 【EnterpriseGN】FW7NV-4T673-HF4VX-9X4MM-B4H4T
* 【gvlkEnterpriseG】YYVX9-NTFWV-6MDM3-9PT4T-4M68B
* 【gvlkEnterpriseGN】44RPN-FTY23-9VTTB-MP9BX-T84FV
> 说明：
> 1. 现有的Win10中文版要升级为企业G版，不需要重装系统，一个密钥即可搞定，开始--设置--更新和安全--激活--更改产品密钥。
> 2. 更改产品密钥（比如使用YYVX9-NTFWV-6MDM3-9PT4T-4M68B）后就能自动升级成为企业版G。
> 3. 激活期限为15万天（400年），基本上算是永久激活了。
> 4. G表示政府，N表示无捆绑软件版，gvlk表示用于KMS激活的批量激活码。【win10企业版G kms激活400年方法(提供镜像下载)】


## 激活方法：
系统安装完毕后，首先以管理员身份打开CMD命令行窗口，按下Win+X，选择命令提示符(管理员)。\
说明：kms.xspace.in是kms服务器地址，可能会失效，如果激活失败，可以自行搜索kms服务器地址，将kms.xspace.in替换成新的地址即可，比如换成kms.03k.org\
win10用户请依次输入：
```
slmgr /ipk 产品密钥 
slmgr /skms 服务器地址
slmgr /ato
```
slmgr的其他使用方法：
* slmgr /upk
* slmgr /xpr
