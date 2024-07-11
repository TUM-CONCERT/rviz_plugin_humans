# RVIZ PLUGIN HUMANS

This plugin can directly visualize ros-messages of the type `concert_msgs/Humans` in RVIZ. 
![image](https://github.com/manuelvogel12/rviz_plugin_humans/assets/120781514/14527d0a-df68-42d1-aaf1-7af969d06114)

## Dependencies
- CONCERT: [concert_msgs](https://github.com/ADVRHumanoids/concert_msgs) : Defines a ros message for Humans, using keypoints 
- Other: None

## Installation
Install this project just like any other ros packages
1. Clone it into `catkin_ws/src` using `https://github.com/TUM-CONCERT/rviz_plugin_humans.git`
2. Source the environment using `source devel/setup.bash`


# Usage
* start RVIZ by `rviz`
* within RVIZ, add the topic as you would do usually. 

* Alternatively, e.g. when no Human topic is published yet, you can press `Add` (1 in the image) then go to the tab `By display type`, select `Humans` and then specify the topic in the left panel.
