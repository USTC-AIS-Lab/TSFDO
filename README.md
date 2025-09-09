# TSFDO

This repository provides the data and selected figures used in the paper *“From Local Odometry to Global Awareness: A Two-Stage Filter-Based Distributed Odometry for Multi-Robot Systems”*, for the convenience of researchers to reference and use.
  

📄 Paper Link: [arXiv / 会议 / 期刊](https://arxiv.org/abs/xxxx)

---

## 📊 Dataset Download

This project provides partial experimental data (in ROS bag format) for reproducing the experimental results in the paper.  

- [Rosbag](https://huggingface.co/datasets/xxx/yyy)  
- [Alternative link (Baidu Netdisk)](https://pan.baidu.com/s/xxxx) Extraction code: `abcd`  

> ⚠️ Note: Please cite this paper when using the dataset and comply with the open-source license.

---

## 🖼️ Related Figures

### 论文中部分关键结果如下：

<p align="center">
  <img src="figures/example_traj.png" alt="Trajectory Example" width="500"/>
</p>

<p align="center">
  <em>图1. 多无人机协同 SLAM 轨迹对比</em>
</p>

---

## 🚀 使用方法

1. 克隆仓库  
   ```bash
   git clone https://github.com/username/repo.git
   cd repo
2. 下载数据集并放入 datasets/ 文件夹。
    ```bash
    rosbag play datasets/uav0_uav1.bag
4. 播放 rosbag：

---

## 📌 引用

如果本仓库和数据集对您的研究有帮助，请引用我们的论文：
```bash
@inproceedings{your_paper,
  title={Paper Title},
  author={Your Name and Others},
  booktitle={Conference},
  year={2025}
}
