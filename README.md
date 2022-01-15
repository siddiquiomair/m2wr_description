# m2wr_description
Simulation of a wheeled robot in a Gazebo virtual environment to move to a specified location
## Installation
#### Repository
```python
-cd ~
-mkdir coursework1_ws
-mkdir coursework1_ws/src
cd ~/coursework1_ws/src
catkin_init_workspace
cd ~/coursework1_ws
catkin_make
```
#### Cloning
```python
cd ~/coursework1_ws/src
git clone https://github.com/siddiquiomair/m2wr_description.git
cd ~/coursework1_ws
catkin_make
```
#### Lanching Gazebo simulation
##### Open a terminal and execute the command written below which will open gazebo simulation
```python
roslaunch m2wr_description gazebo.launch
```
#### Launching Rviz
##### Open a second terminal while keeping the first open and enter
```python
roslaunch m2wr_description gmapping_demo.launch
```
#### MAP in Rviz
##### Open a third terminal while keeping all the terminal opened before and enter
```python
roslaunch m2wr_description amcl_demo.launch
```
#### Python scirpt
##### Again open a terminal and start ro run the python script goal.py having waypoints by entering 
```python
roslaunch m2wr_desription goal.py 
```
