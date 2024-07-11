# RVIZ PLUGIN HUMANS

This plugin can directly visualize ros-messages of the type `concert_msgs/Humans` in RVIZ. 
![rviz-humans](https://github.com/TUM-CONCERT/rviz_plugin_humans/assets/120781514/7f98873d-e7ca-4725-9f6d-9d2b0d709c9f)


## Dependencies
- CONCERT: [concert_msgs](https://github.com/ADVRHumanoids/concert_msgs) : Defines a ros message for Humans, using keypoints 
- Other: None

## Installation
Install this project just like any other ros packages
1. Clone it into `catkin_ws/src` using `https://github.com/TUM-CONCERT/rviz_plugin_humans.git`
2. Build the environment using `catkin build`
3. Source the environment using `source devel/setup.bash`


# Usage
* start RVIZ by `rviz`
* within RVIZ, add the topic as you would do usually. 
![image](https://github.com/TUM-CONCERT/rviz_plugin_humans/assets/120781514/f3ac4888-2991-4e90-93b0-51c0ba637d1e)

* Alternatively, e.g. when no Human topic is published yet, you can press `Add` (1 in the image) then go to the tab `By display type`, select `Humans` and then specify the topic in the left panel.
