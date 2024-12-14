系统安装完毕后，首先以管理员身份打开CMD命令行窗口，按下Win+X，选择命令提示符(管理员)。

说明：kms.xspace.in是kms服务器地址，可能会失效，如果激活失败，可以自行搜索kms服务器地址，将kms.xspace.in替换成新的地址即可，比如换成kms.03k.org，参考可用的kms激活服务器有哪些

win10专业版用户请依次输入：
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
slmgr /skms kms.03k.org
slmgr /ato

win10企业版用户请依次输入：
slmgr /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43
slmgr /skms kms.03k.org
slmgr /ato

win10家庭版用户依次输入：
slmgr /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
slmgr /skms kms.03k.org
slmgr /ato
