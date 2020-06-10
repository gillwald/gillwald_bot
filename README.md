# gillwald_bot
Gazebo model for a simple differential drive robot

# Getting Started

1) Clone the repo in a catkin workspace
2) Run catkin_make in the root directory
3) Move file 'maze.dae' to '~/.gazebo/models/mazes/meshes/'
4) From the terminal run 'roslaunch gillwald_bot spawn_small.launch' to launch a small robot in an empty world
5) From the terminal run 'roslaunch gillwald_bot maze_with_robot_small.launch' to launch a small robot in a maze