# www.aisegment.cn  
# 简介
本数据集为目前已知最大的人像matting数据集，包含34427张图像和对应的matting结果图。  
数据集由北京玩星汇聚科技有限公司高质量标注，使用该数据集所训练的人像软分割模型已商用。  
数据集中的原始图片来源于Flickr、百度、淘宝。经过人脸检测和区域裁剪后生成了600*800的半身人像。  
clip_img目录为半身人像图像，格式为jpg；matting目录为对应的matting文件（方便确认matting质量），格式为png，您训练前应该先从png图像提取alpha图。例如使用opencv可以这样获得alpha图：  
in_image = cv2.imread('png图像文件路径', cv2.IMREAD_UNCHANGED)  
alpha = in_image[:,:,3]  
  
# 下载地址
链接：https://pan.baidu.com/s/1R9PJJRT-KjSxh-2-3wCGxQ 
提取码：dzsn 

other url:  
https://mega.nz/#F!Gh8CFAyb!e2ppUh-copP76GbE8IWAEQ  
https://www.kaggle.com/laurentmih/aisegmentcom-matting-human-datasets/
  
# 数据集截图
  ![Image text](https://github.com/aisegmentcn/matting_human_datasets/blob/master/1.png)  
  matting图：  
  ![Image text](https://github.com/aisegmentcn/matting_human_datasets/blob/master/2.png)
  
# [视频人像分割与抠图SDK，含免费版](https://github.com/aisegmentcn/human-matting-sdk)
[点击了解](https://github.com/aisegmentcn/human-matting-sdk)  


公司官网：www.aisegment.cn ，可体验语义分割效果。  
