## Hi 👋

### 一、基于 PD 的软体形变模拟


https://github.com/user-attachments/assets/aa255447-32ea-41be-b20d-4766978f2855

**实验数据**
- CPU: AMD Ryzen 9 7945HX
- RAM: 32G
- GPU: RTX 4070 Laptop GPU
- VertCnt: 18k
- TetCnt: 93k
- phyCost: 8.9ms
- fixFps: 60Hz

**技术要点**
1. 基于 Projective Dynamics
2. 引入多分辨率网格加速迭代收敛
3. 约束解算均使用 CUDA 并行加速

### 二、带力反馈的肝脏软体夹取

https://github.com/user-attachments/assets/46018343-563a-4eb6-af59-9ac655f765d4

**工作亮点**
1. PD 框架下实现了夹取拖拽的约束
2. 拖拽过程中支持输出拖拽力

### 三、虚拟现实群组导航

https://github.com/buuugyellow/VR-Group-Navigation/assets/151597014/765f9675-4754-4f9d-aaa4-bc6cc7c75d2e

**工作亮点**
1. 提出视点质量定量刻画参观体验，考虑以下因素
   - 完整度
   - 视野占比
   - 遮挡比例
   - 细节丰富度
2. 自动生成参观队形
   - 自动避障防穿模
   - 最大化群组视点质量
