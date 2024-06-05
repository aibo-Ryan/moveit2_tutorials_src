# moveit2_tutorials_src
---
## requirement
+ ubuntu20.04
+ ros2 foxy

## build
```
mkdir -p ~/moveit2_ws/src

cd moveit2_ws/src

git clone git@github.com:aibo-Ryan/moveit2_tutorials_src.git

cd ..

colcon build --cmake-args -DCMAKE_BUILD_TYPE=Release 
```




