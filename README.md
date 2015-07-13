robot_pose_ekf
==============

To estimate 3D pose of a robot


说明：

command:
rqt
   + plugins / visualization / tf tree   (***做里程计数据融合时用得到**)
   + plugins / topics / topic monitor

rostopic list
rostopic hz /odom


/odom 与  /imu_data 的融合
