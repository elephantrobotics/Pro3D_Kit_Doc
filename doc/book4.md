## 5 案例复现

可参考视频教程中的抓取演示章节：https://www.bilibili.com/video/BV1xxTNzxEL2/?spm_id_from=333.337.search-card.all.click&vd_source=672e3f7240eaaca210b45e7c033dc45f

**注意事项**：4种PVC工件已创建好点云模板，用户无需再创建，直接使用即可

##  5.1 工件摆放
将PVC工件摆放到托盘内,工件之间不能堆叠,必须是平整摆放

<img src="../img/PVC.png" style="zoom: 100%;" />

## 5.2 六自由度抓取案例

**案例说明**：六自由度抓取案例效果是带姿态抓，即抓取时机械臂末端姿态不会和拍照位的机械臂末端姿态完全一致

双击桌面RVS图标后,待RVS打开后,点击加载

<img src="../img/rvs1.png" style="zoom: 50%;" />

然后选择location_demo文件夹下的demo.rvs文件

<img src="../img/rvs2.png" style="zoom: 50%;" />

然后点击运行

<img src="../img/rvs3.png" style="zoom: 50%;" />

等待相机初始化

<img src="../img/rvs4.png" style="zoom: 50%;" />

<br/>

<img src="../img/rvs5.png" style="zoom: 50%;" />


运行location_demo文件夹中的demo_code文件夹中的demo.py文件

<img src="../img/new4.png" style="zoom: 50%;" />

**注意**：
robot_ip要改成机械臂的实际的无线IP

## 5.3 平面抓取案例
**案例说明**：六自由度抓取案例效果是不带姿态抓，即抓取时机械臂末端姿态会和拍照位的机械臂末端姿态完全一致

双击桌面RVS图标后,待RVS打开后,点击加载

<img src="../img/rvs1.png" style="zoom: 50%;" />

然后选择location_demo文件夹下的Plane_grabbing.rvs文件

<img src="../img/new6.png" style="zoom: 50%;" />

然后点击运行

<img src="../img/rvs3.png" style="zoom: 50%;" />

等待相机初始化

<img src="../img/rvs4.png" style="zoom: 50%;" />

<br/>

<img src="../img/rvs5.png" style="zoom: 50%;" />


运行location_demo文件夹中的demo_code文件夹中的Plane_grabbing.py文件

<img src="../img/new5.png" style="zoom: 50%;" />

**注意**：
robot_ip要改成机械臂的实际的无线IP

## 5.4 注意事项

程序运行后，相机回到拍照位置后，不能中途往托盘里面放入工件，避免相机误识别，导致机械臂发生碰撞等风险