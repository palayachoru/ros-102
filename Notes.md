RViz (Robot Visualization)
---------------------------
* 3D visualization tool to display robot model

TF (TransForm)
--------------



```sh
sudo apt install ros-jazzy-tf2-tools

# run this while the model is running, this command will capture all the tf data
# and generate a tf tree of how each link is connected as a pdf file
ros2 run tf2_tools view_frames

# if we move one link(node) in the tf tree, then all the child links will move

# all installed packages are found at location
/opt/ros/jazzy/share

sudo apt install ros-jazzy-urdf-tutorial

# run a urdf tutorial to view robot in RViz
ros2 launch urdf_tutorial display.launch.py model:=/opt/ros/jazzy/share/urdf_tutorial/urdf/08-macroed.urdf.xacro
```
