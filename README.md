# 3DReconstruction_Animal-body
3D reconstruction of animal body surface information

# 研究主题：牲畜体表信息的三维重建

本文参考Leonid Pishchulinp论文[Building Statistical Shape Spaces for 3D Human Modeling]的方法，使用基于模板的非刚配准来实现三维重建。该方法包括初始化和非刚配准两个步骤。本项目在原有算法的基础上，通过修改其中算法参数和模型，将原有算法从人体转移到牲畜上，并达到一定的精度。

### 5.1 数据准备

模板数据：普通猪的网格数据

扫描数据：第四章获取的归一化后猪的点云数据

另外还需要选取一些特征点，使配准效果更好。因此，我们根据农业上猪的体尺测量，在模板数据和扫描数据上分别选取了37个对应的特征点。
