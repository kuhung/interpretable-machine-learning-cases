# interpretable-machine-learning-cases
可解释的机器学习实践

- 参考资料：

测试起点：https://christophm.github.io/interpretable-ml-book/counterfactual.html

测试工具包：
    - https://github.com/SeldonIO/alibi
    - https://github.com/interpretml/DiCE
    - https://github.com/interpretml/interpret


数据集类型：
（复杂语义的NLP与图像暂不考虑）

- 回归
- 分类

- 类别特征、数值特征

目前遇到的问题：

1. DiCE 只能处理 NN 模型？
2. DiCE 对于大量数据有性能问题
3. 其他工具不过是 LIME & SHAP 的集成体，它们的不同之处在哪里？