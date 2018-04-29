# distracted_driver_detection
该项目为优达学城机器学习（进阶）纳米学位毕业项目。

项目主要基于Keras内置的ResNet50, InceptionResNetV2, InceptionV3, Xception和VGG16模型进行模型训练，训练过程中使用了迁移学习、模型微调和模型融合技术。

模型训练平台为EC2 p2.xlarge, 最终基于Xception, InceptionResNetV2和InceptionV3模型的融合模型在测试集上的预测结果在Kaggle上的Private score得分为0.23244，排名110名。

项目用到的主要开发工具包括python 3.5.2, opencv-python 3.4.0.12, Keras 2.1.3, tensorflow-gpu 1.5.0, pandas 0.22.0, numpy 1.14.0, seaborn 1.0.0, matplotlib 2.1.2。
