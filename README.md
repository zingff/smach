# Smach

An updated version to suppress some error and modify the log information to be more striking.

## Modifications

- state_machine.py: modify the color of state machine starting, transitioning and terminating line
- userdata.py: modify the userdata attribute getter

## Others

With default installation:

```bash
apt install ros-noetic-smach
```

the package location is `/opt/ros/noetic/lib/python3/dist-packages`, one can replace the package after running the above line to use the custom state machine or just place the code at the supposed location.
```bash
cd smach
sudo mv ./* /opt/ros/noetic/lib/python3/dist-packages/smach/
```
