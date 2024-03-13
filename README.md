```bash
echo "deb [trusted=yes] https://github.com/JafarAbdi/franka-humble-packages/raw/stable-2024-02-22/ ./" | sudo tee /etc/apt/sources.list.d/JafarAbdi_franka-humble-packages.list
echo "yaml https://github.com/JafarAbdi/franka-humble-packages/raw/stable-2024-02-22/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-JafarAbdi_franka-humble-packages.list
```
