项目名称：侦测走神司机

数据集：https://www.kaggle.com/c/state-farm-distracted-driver-detection/data

文件说明：
train_validation_split.ipynb : 分割数据集
simple_cnn.ipynb             ：训练一个简单的CNN模型
VGG16_FC.ipynb               ：训练VGG16_FC模型
VGG19_FC.ipynb               ：训练VGG19_FC模型
VGG16_GAP.ipynb              ：训练VGG16_GAP模型
VGG19_GAP.ipynb              ：训练VGG19_GAP模型
model_merge.ipynb            ：模型集成
report.pdf                   ：项目报告


用到的Python库：Keras(Tensorflow后端)、Sklearn、Numpy、Pandas、h5py


程序说明：
1、下载本项目的数据集并解压；
2、首先运行train_validation_split.ipynb把数据集分为训练集和验证集；
3、运行训练模型的.ipynb；
4、对模型进行集成，则运行model_merge.ipynb文件
