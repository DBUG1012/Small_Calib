# Small_Calib
这是一个可以帮助你完成图像与激光雷达点云标定的程序，你可以使用它来输出标定投影效果，仅改变几个参数和路径。
本程序仅适用于室内以及狭窄且纹理明显的场景，如果是宽阔的户外场景请使用无靶方法，参考MARS-LVIG与UAVScenes数据集的方法。

## 下面是对文件的说明：
- para文件夹中存储的是三个标定内外参TXT文件，分别是相机的内参，畸变系数，外参。
- sample文件夹中存储的是四张样片以及利用pcd2image_lcc程序输出的结果。
- src文件夹中存储的是两个源码，其中pcd2image是将点云投影到图像的原始程序，pcd2image_lcc是对应livox_camera_calib效果的增强版程序。

## sample的下载
文件夹中包含的是原始图像文件，下载pcd文件请使用百度网盘。
、、、
通过网盘分享的文件：sample
链接: https://pan.baidu.com/s/1m8XIJP7kh9iu4H2bPg7vsg?pwd=dbug 提取码: dbug 
--来自百度网盘超级会员v6的分享
、、、
