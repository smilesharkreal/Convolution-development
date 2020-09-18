# Convolution-development
卷积神经网络笔记整理
## 时间线上整理 
2012 AlexNet 网络   运用ReLu、Dropout 分组卷积 
2014 VGG网络 
       GoogleNet 多过滤器结合  
2015 inception V2 :使用了batch Normalization 使用两个3*3 代替5*5 
         inception V3： 先Pooling 再使用inceotion 
2015 ResNet :使用残差结构 
2016 ResNet V2: ReLU和BN 在residual分支位置摆放 
         Inception V4 和resNet 结合 使用trick 减少计算量并取得不错的效果 
使用并行结构 
使用不对称的卷积 
 使用1*1的卷积进行维度变换 
2016 Xception :先 使用1*1 卷积 再对每个通道使用3*3 卷积 然后concat  是基于ResNet 
2017 mobileNet :先使用深度可分离卷积， 
2017 SeNet 使用squee 和 excess机制 
2017 ResNext 使用cardinary   
2017 ShuffleNet 加入通道混洗 
2018 mobileNetV2  “扩张”→“卷积提特征”→ “压缩” 
