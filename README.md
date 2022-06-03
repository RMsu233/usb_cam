# usb_cam
It was created for rosbag record the usb_camera dates  
Videocapture (usb_camera) transport to  Ros( noetic )  
## How to use it   
```shell
#clone it to your workspace   
`git clone https://github.com/RMsu233/usb_cam.git`   
#Recompile it   
#Start the ros   
`roscore`   
#Update your ros environments   
`source /opt/ros/noetic/setup.bash`   
#Start the program   
`rosrun usb_camera`   
```
## about 
you can type `roscore` && `rostopic list` to watch the image node   
for the less space to keep it in your disks ,you can `rosbag record ` the topic `usb_cam/image_raw/theDepthCompress`
