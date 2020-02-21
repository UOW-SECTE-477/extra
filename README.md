# extra
Extra files for the Turtlebot3s.

`turtlebot3_realsense.launch` should be moved to `~/catkin_ws/src/turtlebot3/turtlebot3_bringup/launch/` to replace the existing launch file there. Likewise, `turtlebot3_robot.launch` should be moved to `~/catkin_ws/src/turtlebot3/turtlebot3_bringup/launch/` to replace the existing launch file there.

`range-detector` can be moved to anywhere, such as a `~/Scripts/` folder. It should be run explicitly so as to not conflict with the `range-detector` installed on the path with the `imutils` pip package. Run using `./range-detector -f HSV -r -p`.
