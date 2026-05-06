# Small_Calib
这是一个可以帮助你完成图像与激光雷达点云标定的程序，你可以使用它来输出标定投影效果，仅改变几个参数和路径。
- 本程序主要适用于室内以及狭窄且纹理明显的场景，如果是宽阔的户外场景请使用无靶方法，参考MARS-LVIG与UAVScenes数据集的方法。
- 本程序所需的文件类型有： 参数txt文件，图像jpg/png文件，点云pcd文件

## 下面是对文件的说明：
- para文件夹中存储的是三个标定内外参TXT文件，分别是相机的内参，畸变系数，外参。
- sample文件夹中存储的是四张样片以及利用pcd2image_lcc程序输出的结果。
- src文件夹中存储的是两个源码，其中pcd2image是将点云投影到图像的原始程序，pcd2image_lcc是对应livox_camera_calib效果的增强版程序。

## sample的下载
文件夹中包含的是原始图像文件，下载pcd文件请使用百度网盘。
通过网盘分享的文件：sample
链接: https://pan.baidu.com/s/1m8XIJP7kh9iu4H2bPg7vsg?pwd=dbug 提取码: dbug 
--来自百度网盘超级会员v6的分享

## 投影效果
原图像：
<img width="1920" height="1080" alt="0" src="https://github.com/user-attachments/assets/a74155c3-8b60-4b00-8434-8da4530cf537" />
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/211ac499-3ffd-4b9b-ab60-b25dac090e5d" />
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/387bed49-4d2c-4866-98fa-1ad2bf18151a" />
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/71e81a9b-360c-4398-80be-8d56f22ebfb6" />

效果图像：
<img width="1920" height="1080" alt="0_result" src="https://github.com/user-attachments/assets/c1e06f65-c541-4f29-b792-ebcef3750e20" />
<img width="1920" height="1080" alt="1_result" src="https://github.com/user-attachments/assets/8e6aa47e-4e61-4c1e-b299-1a98af7e2a09" />
<img width="1920" height="1080" alt="2_result" src="https://github.com/user-attachments/assets/c197c688-7cb5-48a5-b027-5204ef20fc78" />
<img width="1920" height="1080" alt="3_result" src="https://github.com/user-attachments/assets/f8a9b6b4-bc91-4f38-8a23-133cafa23867" />
