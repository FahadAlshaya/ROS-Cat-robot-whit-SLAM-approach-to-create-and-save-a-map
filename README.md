# ROS-Dpoom-robot-whit-SLAM-approach-to-create-and-save-a-map

i use Ros Melodic and ubuntu-18.04 to SLAM approach to create and save a map

- This reopsitory contains Gazebo simulation of Dpoom, based on turtlebot3 simulation


## Dpoom in real world
![sdvsdvsdv](https://user-images.githubusercontent.com/60845044/125338951-7c2f4800-e359-11eb-9343-9381a8e8aa5b.png)


## Installing

- `$catkin_ws/src `
- `$git clone https://github.com/SeunghyunLim/Dpoom_gazebo.git`
- `$cd ~/catkin_ws && catkin_make`

## Run
- `$export TURTLEBOT3_MODEL=dpoom`
- `$roslaunch dpoom_gazebo dpoom.launch`

  ![wefwgg32323](https://user-images.githubusercontent.com/60845044/125339428-f4960900-e359-11eb-833f-02a697086ef1.png)

## For teleop keyboard
- `$export TURTLEBOT3_MODEL=waffle_pi`
- `$roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch`

## To add tutlebot3_world
- `$ export TURTLEBOT3_MODEL=burger`
- `$$ roslaunch turtlebot3_gazebo turtlebot3_world.launch`

![wg2333333333333333333333333](https://user-images.githubusercontent.com/60845044/125339803-5ce4ea80-e35a-11eb-90b2-408da8179d61.png)
