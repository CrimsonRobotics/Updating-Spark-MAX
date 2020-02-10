# Updating Spark MAX

Tutorial on how to update the Spark MAX motor controllers

## How to update
First you want to download the [REV Spark MAX Cilent (Latest Version)](http://www.revrobotics.com/sparkmax-software/#spark-max-client-application)

Next, plug the USB-C cable into the Spark Max
![](/pics/IMG_20200208_121705.jpg)

Then open the Spark MAX Cilent and click connect.
![](/pics/Home-Screen.png)

You may have to update the CAN ID if this is a new Spark MAX.
To do this, click the CAN number, which should be 0 if it's not configured.
Change it to a number that is either one above or one below the highest/lowest ID.
The ID cannot be >62

Go to the "Network" tab and then click "Scan Bus"
![](/pics/Network-Tab.png)

Then click the highlighted box to select every Spark MAX connected. If this is on a finished robot, there will be all of the Spark MAX's here.
![](pics/Scanned-Busses.png)

Click "Load firmware"
![](pics/Selected.png)

Click the latest firmware that corresponds to the display on the client.
![](pics/Selecting-Firmware.png)

Click yes and your firmware should be updating.
### Please wait for this process to finish and do not unplug the USB cable.
![](pics/Updating.png)
