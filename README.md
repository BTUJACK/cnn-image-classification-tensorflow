# Build-myself-CNN
Build myself CNN and Predictive single picture
<br>
#### 搭建自己的CNN并且预测单张图像
目前很多项目利用CNN进行识别分类都是通过fine-tuning，利用fine-tuning的收敛速度快，而且都是用的大牛的网络结构，识别效果会比自己搭建的网络好。<br>
但个人感觉fine-tuning在拥有大量的训练数据的情况下才能发挥绝对的优势，而针对几k张训练数据，搭建一个很浅的网络就能很好的拟合训练数据。浅层网络结构简单，计算量少，训练速度快。前向传播预测单张图片时计算速度很快。<br>
    
