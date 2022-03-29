# carla_autoware_simulation
This is a carla's simulation that integrated autoware. 
# 操作步骤
  1.mkdir -p catkin/src    
  2.cd catkin/src  
  3.git clone https://github.com/yizhiweimengxiangfendoudefeifei/carla_autoware_simulation.git  
  4.cd ..  
  5.安装依赖并编译  
    rosdep update  
    rosdep install --from-paths src --ignore-src -r  
    catkin_make  
  6.在bsahrc中加入source,记得换用户名navigation  
    source /home/navigation/catkin/devel/setup.bash
