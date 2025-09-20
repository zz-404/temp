# temp
# ACDC相关工作



# 物品不完整  墙体，地板  哈弗直线检测
# 朝向
# 拥挤
# 资产库小


# observation
- 雷达
  - 自身状态
  - 导航
  - 环境
- 图像观测
    - 语义相机
    - 深度相机
    - rgb
  - **注意 config["image_observation"] = True**
  - 设置cfg文件，包含名称，相机种类，然后传入到env构造器
- 俯视观测
  调整渲染模式


  overflowed_steering = min((allowed_steering - steering), 0)
  
