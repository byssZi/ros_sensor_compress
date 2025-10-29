# 说明

此工程为ros下对传感器话题进行压缩传输解压缩，用以减少传感器话题所占带宽

# 使用方法

```bash
catkin_make -DCATKIN_WHITELIST_PACKAGES="msg_all;ros_h264_streamer;rcpcc" -DPYTHON_EXECUTABLE=/usr/bin/python3
```
