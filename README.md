# EP008-Demo
树莓派连接 SIM800C 开发板 Python 演示脚本
拨打电话命令改用如下
播放命令，音频文件路径，主频道，音量
AT+CMEDPLAY=1,C:\\to_play.amr,0,100
由于多次上传测试音频文件会产生文件垃圾，删除文件方法如下：
删除命令=路径
AT+FSDEL=C:\\User\\to_play.amr

上传ARM文件还有个官方Windos下小工具
Sim800 Series ArmFile Download v1.00
只能上传上去不能删除远程文件。。。
