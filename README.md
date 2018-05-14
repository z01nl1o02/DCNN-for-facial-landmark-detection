# DCNN-for-facial-landmark-detection
利用mxnet实现 "Deep Convolutional Network Cascade for Facial Point Detection" 中的脸部特征点定位


# 进度
* level 1 和 level 2 [完成]
* Level 3
* 调参

# 实验结果

$err = \sqrt{(x-x')^2 + (y-y')^2}$  

if err > 0.05, it is one failure


|网络名|error|failure|  
|-----|-----|-----|  
|F1   |0.0357   | 0.2047  |  
|L1   |0.0332   | 0.1739  |  
|L1+L2   | 0.0250  | 0.0891 |  
