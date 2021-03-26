# 第三次作业总结

作业地址：https://www.kaggle.com/c/ml2021spring-hw3/

作业介绍：https://speech.ee.ntu.edu.tw/~hylee/ml/ml2021-course-data/hw/HW03/HW03.pdf（不保证不会失效）

参考代码：https://colab.research.google.com/github/ga642381/ML2021-Spring/blob/main/HW03/HW03.ipynb

## 简要说明

- 预测食物图片分类问题
- 目标：
  - 使用CNN
  - 数据增强
  - 处理无标签数据
- food-11数据集（11个类）
  - 训练集： 280 * 11 labeled images + 6786 unlabeled images
  - 验证集： 30 * 11 labeled images
  - 测试集：3347 images
- 要求：不能使用预训练模型（resnet等）
- baseline评判标准：准确度百分比

- 提示：

  - 半监督学习：为无标签数据生成伪标签（pseudo-labels）

    ![image-20210326154911569](https://yumytest.oss-cn-chengdu.aliyuncs.com/img/image-20210326154911569.png)

  - 