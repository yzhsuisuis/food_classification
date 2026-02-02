# food_classification
基于CNN的食物图像分类

# 项目启动流程
```shell
训练模型并保存到model_save 目录下
1. python simple_class_semi_fixed.py

运行验证脚本
2.python predict.py validation_sample.jpg --model_path model_save/best_model_semi_fixed.pth --model_name resnet18 --device  cuda
```
