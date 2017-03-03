# navigation_test

clone this package to your directory catkin_ws/src

open terminal and run
```bash
cd catkin_ws
catkin_make
```

 After biuld the package, the run
 ```bash
 roslauch navigation_test amcl_demo.launch
 ```
 open a new terminal and run
 ```bash 
 rosrun rviz rviz
 ```
 Then you can pose goal in rviz to see the navigation
