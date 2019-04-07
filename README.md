# 数据集简介
本数据集为目前已知最大的人像matting数据集，包含34427张图像和对应的matting结果图。  
数据集由北京玩星汇聚科技有限公司高质量标注，使用该数据集所训练的人像软分割模型已商用。  
数据集中的原始图片来源于Flickr、百度、淘宝。经过人脸检测和区域裁剪后生成了600*800的半身人像。  
clip_img目录为半身人像图像，格式为jpg；matting目录为对应的matting文件（方便确认matting质量），格式为png，您训练前应该先从png图像提取alpha图。例如使用opencv可以这样获得alpha图：  
in_image = cv2.imread('png图像文件路径', cv2.IMREAD_UNCHANGED)  
alpha = in_image[:,:,3]  
  
# 数据集下载地址
baidu  
  
# 数据集截图
  ![Image text](https://github.com/aisegmentcn/matting_human_datasets/blob/master/1.jpg)  
  matting图：  
  ![Image text](https://github.com/aisegmentcn/matting_human_datasets/blob/master/2.jpg)
  
# 更多数据集
我们与阿里云市场联合推出的人像分割开放接口拥有数百家客户，人像分割效果超过Face++、Versa、百度，机器之心有相关报道。  
我们的人像分割开放平台每天处理数十万张照片，积累了海量的数据。如果您需要更多训练数据，请与我们联系。  

# 合作
