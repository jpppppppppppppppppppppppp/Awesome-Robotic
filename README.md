# Awesome-Robotic
## Lecture
- [CS 237a: Principles of Robot Autonomy I](https://stanfordasl.github.io/PoRA-I/aa274a_aut2223/)
- [CS 237b: Principles of Robot Autonomy II](http://web.stanford.edu/class/cs237b/)
- [MIT 6.4210: Robotic Manipulation](https://manipulation.mit.edu/index.html)
- [MIT 6.8210: Underactuated Robotics](https://underactuated.csail.mit.edu/index.html)

## CS 237b
- `2008` Robotic Grasping of Novel Objects:
  - Grasping previously unseen objects using only 2D images without 3D meshes [paper](https://proceedings.neurips.cc/paper_files/paper/2006/file/22722a343513ed45f14905eb07621686-Paper.pdf)
- `2017` Dex-Net 2.0 [paper](https://arxiv.org/abs/1703.09312)
- `2017` Planar Pushing:
  - Combining learned and analytical models for predicting action effects [paper](https://www.researchgate.net/profile/Jeannette-Bohg/publication/320344651_Combining_learned_and_analytical_models_for_predicting_action_effects/links/5a1a3b23a6fdcc50adeaec5b/Combining-learned-and-analytical-models-for-predicting-action-effects.pdf)
- `2019` Making Sense of Vision and Touch:
  - Self-Supervised Learning of Multimodal Representations for Contact-Rich Tasks [paper](https://ieeexplore.ieee.org/document/8793485)
## Table-top Manipulation
- [UniFolding](https://unifolding.robotflow.ai/) [paper](https://arxiv.org/abs/2311.01267)
- [DexAIRity: Deformable Manipulation Can be a Breeze](https://dextairity.cs.columbia.edu) [paper](https://arxiv.org/abs/2203.01197)
- [RoboCook](https://hshi74.github.io/robocook/) [paper](https://arxiv.org/abs/2306.14447)
- [PaperBot](https://paperbot.cs.columbia.edu/) [paper](https://arxiv.org/abs/2403.09566)
- [Cloth Funnels](https://clothfunnels.cs.columbia.edu/) [paper](https://ieeexplore.ieee.org/abstract/document/10161546)
- Pancake [paper](https://arxiv.org/abs/2407.01755)
- [GraspNet](https://graspnet.net/anygrasp.html) [paper](https://arxiv.org/abs/2212.08333)
- [RGBGrasp](https://sites.google.com/view/rgbgrasp) [paper](https://arxiv.org/abs/2311.16592)
- [9DTact](https://linchangyi1.github.io/9DTact/) [paper](https://arxiv.org/abs/2308.14277)

## Policy for robotic manipulation

- Q-attention [paper](http://arxiv.org/abs/2105.14829)
- [Diffusion Policy](https://diffusion-policy.cs.columbia.edu/) [paper](http://arxiv.org/abs/2303.04137)
- Low-Cost Hardware for bimanual manipulation [paper](http://arxiv.org/abs/2304.13705)
- Hierarchical Diffusion Policy [paper](http://arxiv.org/abs/2403.03890)
- Perceiver-Actor: Multi-Task Transformer for Robotic Manipulation [paper](http://arxiv.org/abs/2209.05451)
- RVT: Robotic View Transformer for 3D Object Manipulation [paper](http://arxiv.org/abs/2306.14896)

## Imitation Learning
- [DexCap](https://dex-cap.github.io/) [paper](https://arxiv.org/abs/2403.07788)
- `2024` [Im2Flow2Act](https://im-flow-act.github.io/) [paper](https://arxiv.org/abs/2407.15208)
- `2024` [GET-Zero](https://get-zero-paper.github.io/) [paper](https://arxiv.org/pdf/2407.15002)
- `2024` AdaFlow [paper](http://arxiv.org/abs/2306.14896)

## Segment Anything Model
- Grounded-Segment-Anything [paper](https://arxiv.org/abs/2401.14159) [git](https://github.com/IDEA-Research/Grounded-Segment-Anything)
- RWKV-SAM [paper](https://arxiv.org/abs/2406.19369) [git](https://github.com/HarborYuan/ovsam?tab=readme-ov-file)

## NeRF
- NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis [paper](https://dl.acm.org/doi/abs/10.1145/3503250)
  - 体渲染公式
  - 位置编码来让低频信号高频化
  - 分粗采样和细采样

## 3D Gaussian Splatting
- Structure-From-Motion Revisited [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Schonberger_Structure-From-Motion_Revisited_CVPR_2016_paper.html)
- 3D Gaussian Splatting for Real-Time Radiance Field Rendering [paper](https://arxiv.org/abs/2308.04079)
  - 高斯椭球
  - 球谐函数参数估计
  - 自适应控制以避免对SFM生成点云的强依赖
- 4D-Rotor Gaussian Splatting: Towards Efficient Novel View Synthesis for Dynamic Scenes [paper](https://arxiv.org/abs/2402.03307)
  - 引入时间，在 4D 椭球上做变换
- Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis [paper](https://arxiv.org/abs/2308.09713)
  - 同时场景重建和每个高斯球的6DoF跟踪
