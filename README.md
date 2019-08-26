# Image-style-transfer

小组分工：<br>
时俊鹏：forward.py+backward.py<br>
孙思慧：环境搭建+generateds.py<br>
郝宇：测试+test.py<br>
张腾辉：app.py+main.py<br>

## Instruction
### 一、core文件夹
##### 项目核心代码<br>
generateds：生成tfrecords训练集<br>
forward：前向传播过程，包括图像生成网络、损失函数网络和loss的计算<br>
backward：主要训练过程<br>
test：测试部分，完成图像风格融合和快速迁移<br>
app：JS网页应用调用test的接口文件

### 二、main.py
运行JS网页应用的入口，在网页上完成可视化操作

