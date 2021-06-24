# robot-map
to creat map of a robot using Turtlebot3 and slam do the following:
1-go to the site:
https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/ 
then choose the right version of your ros then do the steps
*if you alrady install ros start from "Install TurtleBot3 Packages" step
*you don't need to do "Network Configuration" step
2-go to the site:
https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/#gazebo-simulation
and do the steps.
3-go to the site:
https://emanual.robotis.com/docs/en/platform/turtlebot3/slam_simulation/
and do the steps.
4- if you want to save the map put the command:
$ rosrun map_server map_saver -f ~/map
<img width="960" alt="smultion pic" src="https://user-images.githubusercontent.com/85635608/123314935-d5167800-d533-11eb-847c-4ea236b7d580.png">
