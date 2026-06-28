<div align="center">

<!-- Capsule Render 动态横幅 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:36BCF7,50:2E8BFF,100:6366F1&height=200&section=header&text=Jiqian%20Zhao&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Control%20Theory%20%7C%20MFAC%20%7C%20Bionic%20Algorithms&descSize=16&descAlignY=55" />

<!-- 打字机效果 -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Model-Free+Adaptive+Control+%7C+MFAC;Bionic+LGMD+%7C+Infrared+Small+Target;Control+Science+%26+Engineering;Passionate+about+Research)](https://git.io/typing-svg)

<!-- 访客计数 & 社交徽章 -->
<img src="https://komarev.com/ghpvc/?username=Zhaojq2003&label=Profile%20Views&color=36BCF7&style=flat" alt="Profile Views" />
&nbsp;
<a href="mailto:zhaojq2003@163.com"><img src="https://img.shields.io/badge/Email-zhaojq2003@163.com-EA4335?logo=gmail&logoColor=white&style=flat" /></a>
&nbsp;
<a href="https://github.com/Zhaojq2003"><img src="https://img.shields.io/badge/GitHub-Zhaojq2003-181717?logo=github&logoColor=white&style=flat" /></a>

</div>

---

## 🎓 About Me

> 热爱科研，深耕控制理论与仿生算法。从大一进组至今已积累两段科研经历，致力于将理论方法转化为可落地的工程工具。

- 🏫 **硕士在读** | 北方工业大学 · 控制工程与科学（2025.09—至今）
- 🎓 **本科毕业** | 温州大学 · 人工智能（2021.09—2025.06）
- 🔬 **研究兴趣**：昆虫仿生避障算法 · 无模型自适应控制(MFAC) · 谱分析 · 红外弱小目标识别
- 🐝 **科研理念**：理论扎实，代码落地，知行合一

---

## 🔬 Research & Publications

| 类型 | 论文/项目 | 状态 |
|:----:|-----------|:----:|
| 🥇 **一作** | HERA: A Hopfield-Enhanced Reflexive Framework for Risk Assessment in Hazardous Environments（TIP, **IF: 13.7**） | 在投 |
| 🥇 **一作** | 红外弱小目标识别 | [arXiv](https://arxiv.org/html/2402.18003v1) |
| 🥈 **二作** | Singular Spectrum Analysis Based Model-Free Adaptive Control with Variable Memory Depth for Air–Ground Robots（**IF: 3.2**） | 在投 |
| 🥉 **三作** | Tensor completion via leverage sampling and tensor QR decomposition for network latency estimation（**IF: 3.4**） | [已发表](https://doi.org/10.1007/s10489-025-06573-4) |

**科研经历**：
- 浙江省自然科学基金项目 · **研究助理**
- 广州大学 · **科研助理**

---

## 🚀 Open Source

<!-- 只展示公开仓库，mfac_toolkit -->

### [`mfac_toolkit`](https://github.com/Zhaojq2003/mfac_toolkit) — 无模型自适应控制 Python 工具包

<p>
  <img src="https://img.shields.io/badge/Python-3.12%2B-3776AB?logo=python&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat" />
  <img src="https://img.shields.io/badge/SISO%2FMIMO-Supported-blueviolet?style=flat" />
</p>

面向 SISO/MIMO 离散时间系统的 **MFAC（无模型自适应控制）** Python 工具包，底层核心采用 Rust 编写，提供高性能的计算效率。支持 CFDL / PFDL / FFDL 三种动态线性化格式，统一 `controller.update(y, yd)` 接口，YAML 配置驱动。

```python
from mfac_toolkit import MFACConfig, create_controller

config = MFACConfig.from_yaml("siso_config.yaml")
controller = create_controller(controller)
u = controller.update(y=0.0, yd=1.0)  # 下一时刻控制输入
```

📦 PyPI 安装：`pip install mfac-toolkit`

> 🔧 **Rust 底层源码**：如有学术研究或工程定制需求，欢迎联系课题组获取底层源码。Python 层已完全开源可扩展。

---

## 🛠️ Tech Stack

<!-- 技能徽章 -->
**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white&style=flat)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?logo=mathworks&logoColor=white&style=flat)
![C++](https://img.shields.io/badge/C++-00599C?logo=c%2B%2B&logoColor=white&style=flat)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white&style=flat)

**Control & Robotics**

![Control Theory](https://img.shields.io/badge/MFAC-FF6B6B?style=flat)
![Adaptive Control](https://img.shields.io/badge/Adaptive%20Control-4ECDC4?style=flat)
![Robotics](https://img.shields.io/badge/Robotics-45B7D1?style=flat)
![PX4](https://img.shields.io/badge/PX4-333333?logo=px4&logoColor=white&style=flat)

**AI & Data Science**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white&style=flat)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=flat)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white&style=flat)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=flat)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black&style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visual-studio-code&logoColor=white&style=flat)

---

## 🏆 Awards & Honors

| 年份 | 竞赛/荣誉 | 奖项 |
|:----:|-----------|:----:|
| 2026 | 第十六届 MathorCup 数学应用挑战赛（研究生组） | 🥇 **国奖** |
| 2026 | 挑战杯课外学术科技作品竞赛 | 🥈 **国奖**（第三位次）|
| 2024 | 浙江省大学生高等数学竞赛 | 工科类 **三等奖** |
| 2024 | 温州大学第十一届"挑战杯" | **金奖** |
| 2023 | 美国大学生数学建模竞赛 MCM/ICM | **H 奖** |
| 2023 | 高教社杯全国大学生数学建模 | **省三等奖** |

---

## 📊 GitHub Stats

<div align="center">

<!-- GitHub 奖杯 -->
[![GitHub Trophy](https://github-profile-trophy.vercel.app/?username=Zhaojq2003&theme=algolia&column=7&margin-w=10&margin-h=10&no-frame=true)](https://github.com/ryo-ma/github-profile-trophy)

<!-- GitHub 统计卡片 -->
<table>
<tr>
<td>
<img src="https://github-readme-stats.vercel.app/api?username=Zhaojq2003&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=36BCF7&icon_color=36BCF7&text_color=C9D1D9" height="170" />
</td>
<td>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zhaojq2003&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=36BCF7&text_color=C9D1D9&langs_count=6" height="170" />
</td>
</tr>
</table>

<!-- 贡献热力图 -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Zhaojq2003&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=36BCF7&line=2E8BFF&point=6366F1" width="95%" />

</div>

---

## 📫 Contact

- 📧 **Email**: [zhaojq2003@163.com](mailto:zhaojq2003@163.com)
- 🏫 **Affiliation**: 北方工业大学 · RobotX 实验室
- 🌐 **GitHub**: [@Zhaojq2003](https://github.com/Zhaojq2003)
- 📍 **Location**: 北京，中国

> 💡 **合作交流**：欢迎对 MFAC、仿生算法、机器人控制等方向感兴趣的老师同学联系交流！

---

<div align="center">

<!-- 底部横幅 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:36BCF7,50:2E8BFF,100:6366F1&height=120&section=footer" />

</div>
