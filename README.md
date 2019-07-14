# Tello-animal_detect
- 在Tello_Video_With_Pose_Recognition项目的基础上进行了改进，更换了新的神经网络模型，能够根据识别结果向飞行器发送指令，完成特定的任务。

## 运行说明
- 1、运行环境和Tello_Video_With_Pose_Recognition项目一致，详情参考README_OLD.md
- 2、需要新建img文件夹，作为拍照的图片保存位置
- 3、model/googlenet文件夹下应有synset_words.txt，bvlc_googlenet.prototxt，bvlc_googlenet.caffemodel文件。
模型文件下载地址
链接：https://pan.baidu.com/s/1MaGl599Lqztma8ECRUfK8g
提取码：2wj1

## 调整说明
- 1、现在的功能为模拟野外拍摄哺乳动物，即遇到tiger,leopard,lesser panda就拍照，遇到蛇后空翻并降落，其他动物不断左移识别下一个。
- 2、主要的调整部分请查看todo列表

## reference
- 1、https://zhuanlan.zhihu.com/p/28703867

## possible error
- 如果注释中有中文导致报错，在文件头加入#-*-coding:UTF-8-*-

## others
- 这里的GoogleNet.py为单独的测试程序

