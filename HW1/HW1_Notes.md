# 可选的提升性能的方式
1. 特征归一化，特征选择（feature selection），如：人工选择一些feature、调用自动化的包（SelectKBest）
2. 选择合适的activation function，如：LeakyRelu
3. 替换优化器，如Adam
4. 调整learning rate，如余弦退火Cosine annealing
5. 尝试使用dropout
6. 正则化regularization
7. 适当增加网络宽度
