# usb_cam
It was created for rosbag record the usb_camera dates  
Videocapture (usb_camera) transport to  Ros( noetic )  
## How to use it   
`git clone https://github.com/RMsu233/usb_cam.git` to your ros workspace   
`cd` to your path (workspace) and `catkin_make `   
`roscore`   
`source /opt/ros/noetic/setup.bash` source your ros environments      
`rosrun usb_camera`      
## about 
you can type `roscore` && `rostopic list` to watch the image node   
for the less space to keep it in your disks ,you can `rosbag record ` the topic `usb_cam/image_raw/theDepthCompress`
