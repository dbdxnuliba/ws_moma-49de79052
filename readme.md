refer to [https://github.com/ethz-asl/moma](https://github.com/ethz-asl/moma)

roslaunch moma_bringup panda_moveit_gazebo.launch

![image](https://user-images.githubusercontent.com/13350158/169549138-28c8346b-6dc1-4971-bde7-f68993d420f6.png)


![image (1)](https://user-images.githubusercontent.com/13350158/169549254-9b835cc2-8fa6-4550-a9cf-6754a42f2c7f.png)


![image](https://user-images.githubusercontent.com/13350158/169553631-41039513-83e3-45c2-840f-3557d0ca4ad9.png)

 rosparam get /move_group/controller_list
 
- action_ns: follow_joint_trajectory
  default: true
  joints:
  - panda_joint1
  - panda_joint2
  - panda_joint3
  - panda_joint4
  - panda_joint5
  - panda_joint6
  - panda_joint7
  name: effort_joint_trajectory_controller
  type: FollowJointTrajectory
