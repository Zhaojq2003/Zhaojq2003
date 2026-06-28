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

## About Me

- **硕士在读** | 北方工业大学 · 控制工程与科学（2025.09—至今）
- **本科毕业** | 温州大学 · 人工智能（2021.09—2025.06）
- **研究兴趣**：昆虫仿生避障算法 · 无模型自适应控制(MFAC) · 谱分析 · 红外弱小目标识别
- **科研理念**：理论扎实，代码落地，知行合一

---

## 🚀 Open Source

<!-- mfac_toolkit -->

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

PyPI 安装：`pip install mfac-toolkit`

---

## GitHub Stats

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

## Contact

- **Email**: [zhaojq2003@163.com](mailto:zhaojq2003@163.com)
- **Affiliation**: 北方工业大学 · RobotX 实验室
- **GitHub**: [@Zhaojq2003](https://github.com/Zhaojq2003)
- **Location**: 北京，中国

> **合作交流**：欢迎对 MFAC、仿生算法、机器人控制等方向感兴趣的老师同学联系交流！

---

<div align="center">

<!-- 底部横幅 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:36BCF7,50:2E8BFF,100:6366F1&height=120&section=footer" />

</div>
