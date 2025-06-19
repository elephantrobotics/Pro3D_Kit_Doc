# 2 硬件安装

可参考视频教程中的硬件安装章节：https://www.bilibili.com/video/BV1xxTNzxEL2/?spm_id_from=333.337.search-card.all.click&vd_source=672e3f7240eaaca210b45e7c033dc45f

根据文字提示，将相应的物品放置在底板上。

<img src="../img/back.png" style="zoom: 20%;" />

# 2.1 机械臂安装
先将罩壳的螺丝拆卸下来

<img src="../img/r1.png" style="zoom: 20%;" />

用螺丝将底板与机器人固定,然后用G型夹将底板固定在桌面边缘

<img src="../img/r2.png" style="zoom: 50%;" />

<br/>

<img src="../img/r3.png" style="zoom: 20%;" />

在电源适配器断电的情况下，将适配器输出端与机械臂电源处连接

<img src="../img/dianyuan.png" style="zoom: 50%;" />

然后将急停旋钮接入后，顺时针旋开急停旋钮

<img src="../img/stop.png" style="zoom: 40%;" />

准备好配件中的显示器连接线

<img src="../img/Drawing 24.png" style="zoom: 40%;" />

HDMI接头与电脑相连，micro HDMI接有与机器人相连,连接好后给机器人上电即可显示。

<img src="../img/Drawing 25.png" style="zoom: 40%;" />

按下电源开关即可

<img src="../img/botton.png" style="zoom: 30%;" />

机器人上电开机后,登录RoboFlow操作系统，密码为elephant

<img src="../img/p0.png" style="zoom: 40%;" />

进入配置中心，点击启动机器人按钮

<img src="../img/p1.png" style="zoom: 40%;" />

<br/>

<img src="../img/p2.png" style="zoom: 40%;" />

<br/>

<img src="../img/p3.png" style="zoom: 40%;" />

<br/>

<img src="../img/p4.png" style="zoom: 40%;" />

长按住回零按钮，机械臂每个关节会回到对应的零点

<img src="../img/zero1.png" style="zoom: 40%;" />

机械臂的每个关节到位后会有弹窗提醒，此时可松开回零按钮

<img src="../img/zero3.png" style="zoom: 40%;" />

<br/>

<img src="../img/zero2.jpg" style="zoom: 30%;" />

<br/>

选择你要连接的wifi热点，输入密码连接后，查看机器人的无线IP，客户使用的电脑必须连接和机器人同一个wifi热点，打开vnc，输入机械臂的无线IP及用户名和密码

<img src="../img/wifi1.png" style="zoom: 30%;" />

<br/>

鼠标只需移动到WiFi图标，即可显示无线IP

<img src="../img/wifi2.png" style="zoom: 30%;" />

## 2.2 相机&吸泵安装

先将相机法兰古固定到相机上

<img src="../img/c1.jpg" style="zoom: 20%;" />


用roboflow将J3关节调到90度

<img src="../img/j3.png" style="zoom: 50%;" />


然后参考图片的方式，将相机和吸泵安装到机械臂末端法兰，相机的安装姿态务必要和图片中保持一致

<img src="../img/c_pose.jpg" style="zoom: 20%;" />


给相机接上通信线，通信线一端是航空插，一端是网线头，航空插上有缺口，按照缺口插入后拧紧，带网线头的一端接到电脑上

<img src="../img/c3.jpg" style="zoom: 20%;" />

给相机接上电源线，电源线一端是航空插，一端是8根散线，航空城上有缺口，按照缺口插入后拧紧

<img src="../img/c2.jpg" style="zoom: 20%;" />

<br/>

<img src="../img/c4.jpg" style="zoom: 20%;" />

然后将电源线散线的一端，找出棕色和绿色两根线，之后再将两根线接到端子上

<img src="../img/c5.jpg" style="zoom: 20%;" />

然后将端子插到机械臂的输入端，注意插入前要观察，棕色对应24V，绿色对应GND，不能接反，否则会造成相机损坏

<img src="../img/c6.jpg" style="zoom: 20%;" />

观察相机的灯有无亮起

<img src="../img/c8.jpg" style="zoom: 20%;" />

最后将吸泵盒的控制线接到机械臂的输出端，即整体安装流程结束，相机线和气管可用魔术贴固定在机械臂上

<img src="../img/c7.jpg" style="zoom: 20%;" />


安装完的效果图

<img src="../img/show.png" style="zoom: 50%;" />
