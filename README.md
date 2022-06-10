### Build My Project
- $ mkdir -p ur5_ws/src 
- $ cd ur5_ws/src
- $ git clone git@github.com:suzhenxzhong/ur5_practise.git 
- $ cd ..
- $ catkin_make

### Open a pick and place demo
- $ roslaunch ur5_gripper_moveit_config demo_gazebo.launch
- $ rosrun ur5_simple_pick_and_place pick_and_place
