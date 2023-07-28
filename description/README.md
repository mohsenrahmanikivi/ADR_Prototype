cd to the parent folder of adr_base
source install/setup.bash
ros2 launch adr_base rsp.launch.py
now you can view model in rviz2
to rotate wheels and fix error with wheel joint
ros2 run joint_state_publisher_gui joint_state_publisher_gui
