hello fellow robotics enthusiast.
I have tried to make a ros2 based joystick controlling the turtlesim.
the project is a part of examples which we will build over to further expand this functionality into controlling a rover.

steps to use this project yourself:
1) create a src folder using "mkdir src" inside of which again run "mkdir rover_cotrol_py"
2) git clone this repo inside the rover_control_py
3) now use "colcon build" in the main folder by coming back to main folder where your src folder lies.
4) "source install/setup.bash" to be used in every terminal you open
5) Connect your controller in usb port
6) Then use "ros2 run joy joy_node" and check if your controller is listed in the terminal
6) In a new terminal again use source from step 4 and then use "ros2 run rover_control_py turtlesim_joy_node"
7) In a new terminal first soruce using step 4 and use "ros2 run turtlesim turtlesim_node"

Using the above 7 steps you must be successfully be able to use your controller to control the turtlesim

For fun purpose i have programmed LT trigger to allow the turtle to speed upto 4 times, you can configure different buttons for different functionalities and enjoy tweaking around the turtle movement.

I hope you liked this project let me know about any improvements in this project till then happy learning.
