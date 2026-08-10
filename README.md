```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/christianrauch/uav-ros-deb-builder/resolute-lyrical-arm64/ ./" | sudo tee /etc/apt/sources.list.d/christianrauch_uav-ros-deb-builder-resolute-lyrical-arm64.list
echo "yaml https://github.com/christianrauch/uav-ros-deb-builder/raw/resolute-lyrical-arm64/local.yaml lyrical" | sudo tee /etc/ros/rosdep/sources.list.d/1-christianrauch_uav-ros-deb-builder-resolute-lyrical-arm64.list
```
