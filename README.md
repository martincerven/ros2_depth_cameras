  ## RMW Performance 
- ROS2 Humble
- Nvidia Jetson Orin Nano, JP 6.0
- Realsense D455


|  | FastDDS | CycloneDDS | Cyclone+Zenoh | Cyclone+Iceoryx | Cyclone+Iceoryx+Zenoh bridge |
|---|---|---|---|---|---|
| Image | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| PointCloud2 | :white_check_mark: | :woozy_face: | :woozy_face: | :white_check_mark: | :white_check_mark: |
| Multi Interface | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Complex Data Processing | :woozy_face: | :cursing_face: | :cursing_face: | :white_check_mark: | :white_check_mark: |
| Wifi + Image | :woozy_face: | :cursing_face: | :white_check_mark: | :question: | :white_check_mark: |
| Wifi + Pointcloud | :cursing_face: | :cursing_face: | :woozy_face: | :question: | :white_check_mark: |