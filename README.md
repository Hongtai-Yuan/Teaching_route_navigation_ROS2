# Teaching_route_navigation_ROS2

##  colcon build
##  . install/setup.bash
## ros2 run route_record_replay_cpp route_record_replay_node

## ros2 service call /start_stop_recording std_srvs/srv/SetBool "{data: true}"
## ros2 service call /start_stop_recording std_srvs/srv/SetBool "{data: false}"
## ros2 service call /load_trajectory std_srvs/srv/Empty "{}"
## ros2 service call /replay_trajectory std_srvs/srv/Empty "{}"
