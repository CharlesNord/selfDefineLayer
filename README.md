# selfDefineLayer
通过实现 PReLU, 记录了如何利用 Pytorch 自定义带参数的网络层，尤其是自定义反向传播函数。
本代码对比了 self defined PReLU Pytorch 自带的 PReLU 和 ReLU 在 MNIST 上的表现，~~遗憾地发现 PReLU 并不如 ReLU~~ 发现其实两者差不太多，有时候PReLU 好一点，有时候 ReLU 好一点，看运气。可能是因为 MNIST 数据集太简单的原因。
