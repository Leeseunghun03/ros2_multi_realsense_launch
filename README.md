# ros2_multi_realsense_launch

If you have different type of realsense, you can use this command. (without serial number)

```
ros2 launch realsense2_camera rs_multi_camera_launch.py camera_name1:=my_D435 device_type1:=d435 camera_name2:=my_d455 device_type2:=d455
```


If you have same type of realsense or already know serial numbers, you can use this command. (using serial number)

```
ros2 launch realsense2_camera rs_multi_camera_launch.py serial_no1:=_036522070660 serial_no2:=_725112060349
```
