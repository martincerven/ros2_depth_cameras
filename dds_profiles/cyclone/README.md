Set these in `~/.bashrc` 

```
# export ROS_LOCALHOST_ONLY=1 # for localhost
export ROS_DOMAIN_ID=42
export RMW_IMPLEMENTATION=rmw_cyclonedds_cpp
export CYCLONEDDS_URI=<path_to_chosen_xml>
```

If you don't have cyclone installed, use:
```
sudo apt install ros-${ROS_DISTRO}-rmw-cyclonedds-cpp
```