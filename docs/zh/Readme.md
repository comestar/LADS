<h2 align="center">LADS</h2>

该 Git 仓库包含 LADS数据集描述，以及数据集论文中使用的四个遥感模型——Mask2Former、U-Net、DeepLabV3+ 和 Mask R-CNN——的实现代码。

## Dataset Details

该数据集包含1275张地物场景，每个场景的地面分辨率为每像素 0.1米。对于每个场景，都有对应的 “image”（图像）和“label”（标签）。

images是PNG图像，labels 是 PNG 掩码。单个images 对应多个labels，根据文件后缀区分为耕地和建筑 2个类别（如下文所述）。

下面是其中一幅带标签场景的示例：

<img src="..\..\img\18759_yxtdt.png" width="600">

更多示例可从[lads](..\..\dataset)查看

## Dataset 

[Google Drive](https://drive.google.com/drive/folders/118O4RAGCpa9bAgH0_kk5HCoD7P_xpGjP?usp=sharing)
