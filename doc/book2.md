# 2 Hardware Installation

Please refer to the hardware installation section in the video tutorial: https://www.bilibili.com/video/BV1xxTNzxEL2/?spm_id_from=333.337.search-card.all.click&vd_source=672e3f7240eaaca210b45e7c033dc45f

Place the corresponding items on the bottom plate according to the text prompts.

<img src="../img/back.png" style="zoom: 20%;" />

# 2.1 Robot arm installation

First remove the screws of the cover

<img src="../img/r1.png" style="zoom: 20%;" />

Fix the bottom plate to the robot with screws, and then fix the bottom plate to the edge of the desktop with a G-type clamp

<img src="../img/r2.png" style="zoom: 50%;" />

<br/>

<img src="../img/r3.png" style="zoom: 20%;" />

When the power adapter is powered off, connect the adapter output to the power supply of the robot arm

<img src="../img/dianyuan.png" style="zoom: 50%;" />

Then connect the emergency stop knob and turn it clockwise to open it

<img src="../img/stop.png" style="zoom: 40%;" />

Prepare the display cable in the accessories

<img src="../img/Drawing 24.png" style="zoom: 40%;" />

The HDMI connector is connected to the computer, and the micro HDMI connector is connected to the robot. After the connection is completed, power on the robot to display.

<img src="../img/Drawing 25.png" style="zoom: 40%;" />

Press the power switch

<img src="../img/botton.png" style="zoom: 30%;" />

After the robot is powered on, log in to the RoboFlow operating system with the password elephant

<img src="../img/p0.png" style="zoom: 40%;" />

Enter the configuration center and click the start robot button

<img src="../img/p1.png" style="zoom: 40%;" />

<br/>

<img src="../img/p2.png" style="zoom: 40%;" />

<br/>

<img src="../img/p3.png" style="zoom: 40%;" />

<br/>

<img src="../img/p4.png" style="zoom: 40%;" />

Press and hold the return to zero button, and each joint of the robot arm will return to the corresponding zero point

<img src="../img/zero1.png" style="zoom: 40%;" />

A pop-up window will appear after each joint of the robot arm is in place, and you can release the return to zero button at this time

<img src="../img/zero3.png" style="zoom: 40%;" />

<br/>

<img src="../img/zero2.jpg" style="zoom: 30%;" />

<br/>

Select the wifi hotspot you want to connect to, enter the password to connect, and check the robot's wireless IP. The computer used by the customer must be connected to the same wifi hotspot as the robot, open vnc, enter the robot's wireless IP and username and password

<img src="../img/wifi1.png" style="zoom: 30%;" />

<br/>

Just move the mouse to the WiFi icon to display the wireless IP

<img src="../img/wifi2.png" style="zoom: 30%;" />

## 2.2 Camera & suction pump installation

First fix the camera flange to the camera

<img src="../img/c1.jpg" style="zoom: 20%;" />

Use roboflow to adjust the J3 joint to 90 degrees

<img src="../img/j3.png" style="zoom: 50%;" />

Then refer to the picture to install the camera and suction pump to the end flange of the robot arm. The installation posture of the camera must be consistent with the picture

<img src="../img/c_pose.jpg" style="zoom: 20%;" />

Connect the communication cable to the camera. One end of the communication cable is an aviation plug and the other end is a network cable head. There is a notch on the aviation plug. Insert it according to the notch and tighten it. Connect the end with the network cable head to the computer

<img src="../img/c3.jpg" style="zoom: 20%;" />

Connect the power cable to the camera. One end of the power cable is an aviation plug and the other end is 8 loose wires. There is a notch on the aviation plug. Insert it according to the notch and tighten it

<img src="../img/c2.jpg" style="zoom: 20%;" />

<br/>

<img src="../img/c4.jpg" style="zoom: 20%;" />

Then find the brown and green wires at one end of the loose wire of the power cable, and then connect the two wires to the terminal

<img src="../img/c5.jpg" style="zoom: 20%;" />

Then plug the terminal into the input end of the robot arm. Note that you should observe before inserting. Brown corresponds to 24V and green corresponds to GND. Do not connect them in reverse, otherwise the camera will be damaged.

<img src="../img/c6.jpg" style="zoom: 20%;" />

Observe whether the camera light is on.

<img src="../img/c8.jpg" style="zoom: 20%;" />

Finally, connect the control line of the suction pump box to the output end of the robot arm. The overall installation process is completed. The camera line and air pipe can be fixed on the robot arm with Velcro.

<img src="../img/c7.jpg" style="zoom: 20%;" />

The effect picture after installation

<img src="../img/show.png" style="zoom: 50%;" />