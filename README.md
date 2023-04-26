
# TRACLabs version:

## Install
To use the Rviz simulation of Perseverance/Ingenuity in ROS1:

1. Download this repository in a craftsman workspace.
2. Use the **noetic-devel** branch.
3. Build workspace as usual.

```
source /opt/ros/noetic/setup.bash
cd ~/ros/craftsman/src
git clone git@github.com:traclabs/m2020-urdf-models m2020_urdf_models
cd m2020_urdf_models
git checkout noetic-devel
cd ..
catkin build
```

## Use

There are launch files for Ingenuity, Perseverance (single and dual):

### One Perseverance Rover:

```
 roslaunch m2020_urdf_models perseverance_demo.launch
 ```

### Dual Perseverance Rovers:

```
 roslaunch m2020_urdf_models dual_perseverance_demo.launch
 ```

### One Ingenuity Drone:

```
 roslaunch m2020_urdf_models ingenuity_demo.launch
 ```

### Dual Ingenuity Drones:

```
 roslaunch m2020_urdf_models dual_ingenuity_demo.launch
 ```
 
 
### Perseverance + Ingenuity:

```
 roslaunch m2020_urdf_models perseverance_ingenuity_demo.launch

# Original  README:

![](./docs/m20-urdf-banner.png)


M2020 Perseverance Rover and Helicopter URDF models used for operations visualization. Models courtesy of the Mars 2020 Perseverance and Ingenuity teams and URDF conversion by JPL RSVP team.

This work was carried out at the Jet Propulsion Laboratory, California Institute of Technology, under a contract with the National Aeronautics and Space Administration

Released June 10th, 2022

Release Ids URS307049, URS309682

Credit NASA/JPL-Caltech

Rover modeling and texturing by Zareh Gorjian

