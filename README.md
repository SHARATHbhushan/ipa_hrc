# Human Robot Collaboration (in progress)

This Repository uses two realsense camera and publishes the pointcloud into rviz with appropriate transforms

Necessary git repositories to be cloned
- realsense ros: https://github.com/IntelRealSense/realsense-ros

Steps to start the rviz visualization
- change the respective camera serial number and appropriate transforms in rs_multicam.launch
- Add pointcloud_multicam.rviz to rviz folder in realsense repo: https://github.com/IntelRealSense/realsense-ros/tree/development/realsense2_camera/rviz
- Add rs_multicam.lauch to lauch folder in realsense repo
- build and setup ros environment
- launch multicam pointcloud visualizytion ´roslaunch realsense2_camera rs_multicam.launch´ 
