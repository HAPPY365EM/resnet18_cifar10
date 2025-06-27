# resnet18_cifar10
简介  
本仓库主要包含使用 ResNet - 18 模型在 CIFAR - 10 数据集上进行图像分类任务的相关代码和实验。同时，还探索了在 ResNet - 18 模型中引入 CBAM（Convolutional Block Attention Module）注意力机制，以提升模型的性能。  
目录结构  
cifar_resnet.ipynb：使用原始 ResNet - 18 模型在 CIFAR - 10 数据集上进行训练和评估的 Jupyter Notebook 文件。  
cifar_resnet_cbam.ipynb：在 ResNet - 18 模型中引入 CBAM 注意力机制，并在 CIFAR - 10 数据集上进行实验的 Jupyter Notebook 文件。  
环境要求  
Python 3.x  
PyTorch  
Torchvision  
NumPy  
Matplotlib  
Jupyter Notebook  

你可以使用以下命令安装所需的依赖：  

bash  
pip install torch torchvision numpy matplotlib jupyter  
使用方法  
1. 克隆仓库  
bash  
git clone https://github.com/your_username/resnet18_cifar10.git  
cd resnet18_cifar10  
2. 运行 Jupyter Notebook  
bash  
jupyter notebook  

在浏览器中打开 Jupyter Notebook 界面，找到 cifar_resnet.ipynb 或 cifar_resnet_cbam.ipynb 文件，依次运行其中的代码块。  
4. 代码说明  
cifar_resnet.ipynb：  
数据加载：使用 torchvision 加载 CIFAR - 10 数据集，并进行预处理。  
模型定义：定义 ResNet - 18 模型。 
训练模型：使用交叉熵损失函数和随机梯度下降（SGD）优化器对模型进行训练。  
评估模型：在测试集上评估模型的准确率。 
cifar_resnet_cbam.ipynb：  
与 cifar_resnet.ipynb 类似，但在 ResNet - 18 模型的基础上引入了 CBAM 注意力机制。  
实验结果  
在运行代码后，你可以在 Jupyter Notebook 中查看模型的训练过程、损失曲线和测试准确率。通过对比 cifar_resnet.ipynb 和 cifar_resnet_cbam.ipynb 的实验结果，你可以分析引入 CBAM 注意力机制对模型性能的影响。  
贡献  
如果你对本仓库有任何改进建议或发现了 bug，请提交 issue 或 pull request。  
许可证  
本项目采用 MIT 许可证。  
