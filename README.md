## DRONE RACE MAP 

To add the model to GAZEBO_MODEL_PATH
```
nano ~/.bashrc
```
Add the following line
```
export GAZEBO_MODEL_PATH=[this repository]/models:$GAZEBO_MODEL_PATH
```
If the models still not loaded automatically, try
```
cp -r [this repository]/models/* ~/.gazebo/models/
```
The should show up after typing the following command
```
gazebo [this repository]/worlds//world/drone_race_track_2018.world
```
