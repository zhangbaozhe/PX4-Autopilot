# PX4 Autopilot (modified for customized Gazebo simulation)

See [this link](https://docs.px4.io/main/en/simulation/ros_interface.html) to use the Gazebo classic simulation.

The repo have been modified to use RealSense camera with the Iris model. After the setup in the above link, you may use
```bash
roslaunch px4 px4_mavros_D435i.launch
```
to launch the simulation.

A Livox Mid360 model has been added to this repo for lidar simulation as well.
To use the Iris model with Livox Mid360 lidar simulation, you may use
```bash
roslaunch px4 px4_mavros_livox.launch
```
to launch the simulation.
