```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/christianrauch/uav-ros-deb-builder/noble-jazzy-arm64/ ./" | sudo tee /etc/apt/sources.list.d/christianrauch_uav-ros-deb-builder-noble-jazzy-arm64.list
echo "yaml https://github.com/christianrauch/uav-ros-deb-builder/raw/noble-jazzy-arm64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-christianrauch_uav-ros-deb-builder-noble-jazzy-arm64.list
```
