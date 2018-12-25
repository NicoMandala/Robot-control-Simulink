# Robot-control-Simulink
This simulink model connects to Gazebo simulator for simple kinematic control.
This model is created from MATLAB tutorials and can also be accessed with the command 'open_system('robotROSConnectToRobotExample');' in MATLAB.
It requires Gazebo and ROS to simulate a virtual robot or a physical robot.

It will send velocity commands to the robot in Gazebo even if you are using Simulink in a different computer.

For configuration of simulation make the following changes:

Click on Simulation > Model Configuration Parameters. In the Solver pane, set Type to Fixed-step and Fixed-step size to 0.01.
Set simulation Stop time to inf.
Click the Play button to start simulation. An XY plot will appear. In both the simulator and XY plot, you should see the robot moving in a circle.
While the simulation is running, change the values of Slider Gain blocks to control the robot. If the robot moves out of range in the XY plot, double-click on the XY Graph block and change the X and Y axis limits (you can do this while the simulation is running).
To stop the simulation, click the Stop button.
