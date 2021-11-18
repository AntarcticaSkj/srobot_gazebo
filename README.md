# srobot_gazebo
Make a simple robot in Gazebo


## Start simulation
~~~shell
$ roslaunch srobot_gazebo simulation_robot.launch 
$ sudo apt-get install ros-melodic-teleop-twist-keyboard
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py 
~~~
## Cartographer 3D
~~~shell
roslaunch cartographer_ros srobot.launch
~~~

## Result
The coordinate system of the wheel moves back and forth.
The other coordinate systems stay put. 


<p>
   <a align="left" href="https://github.com/AntarcticaSkj/srobot_gazebo/blob/main/bad_result_rviz.png" target="_blank">
   <img width="800" src="https://github.com/AntarcticaSkj/srobot_gazebo/blob/main/bad_result_rviz.png"></a>
</p>

Mapping failed.
