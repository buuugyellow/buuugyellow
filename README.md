## Hi 👋

### 基于 PD 的软体形变模拟


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
