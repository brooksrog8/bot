ros2 launch nav2_bringup navigation_launch.py use_sim_time:=true
rviz2
ros2 launch brooks_bot launch_sim.launch.py world:=./worlds/obstacles.world
ros2 launch slam_toolbox online_async_launch.py slam_params_file:=config/mapper_params_online_async.yaml use_sim_time:=true
