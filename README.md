# 具身智能研究成果主页

五篇论文：OmniVLA-RL、EV-WM、Onto-EV-WM、HROS、RegenHarness。
纯静态 HTML/CSS/JavaScript，无外部字体、依赖或构建步骤。可用于 GitHub Pages。

## 本地预览

在此目录运行 `python3 -m http.server 8765 --bind 127.0.0.1`，浏览器打开 `http://127.0.0.1:8765`。
也可直接打开 index.html。

## GitHub Pages 发布

1. 在所选账号创建公开仓库，例如 `embodied-research`。
2. 将本目录的 index.html、style.css、app.js、assets/ 和 .nojekyll 上传到仓库根目录，保留相对路径。
3. 仓库 Settings → Pages → Build and deployment → Source 选择 Deploy from a branch，选择 main 与 /(root)，保存。
4. 等待 Pages 部署完成，以页面实际返回的网址为准。

本项目使用账号 `wang-ship-it` 与仓库 `embodied-research`。
GitHub Pages 配置为从 `main` 分支根目录发布。

## 资料来源与范围

- OmniVLA-RL：https://arxiv.org/abs/2604.17706 ，v2 原论文图1（从 PDF 以 600 DPI 导出）、摘要及表1、表2。
- EV-WM：https://arxiv.org/abs/2606.13053 ，架构与对应仿真设置。
- Onto-EV-WM：https://arxiv.org/abs/2608.13901 ，架构及 LIBERO-Plus 注册任务结果。
- HROS：https://arxiv.org/abs/2609.11225 ，图1由原论文 PDF 高清提取。
- RegenHarness：https://arxiv.org/abs/2609.27612 ，原架构图与真实巡检案例。

五篇论文均展示原论文架构图，可放大或打开原图。OmniVLA-RL 的 97.6% 与 80.3% 分别来自不同基准。
论文数据不可跨实验协议直接排序。未使用“行业首次”或未验证的联合系统结论。
RegenHarness 的配置级 RSI 协议不代表权重级自我改进，也未被呈现为已经验证多轮递归增强。

assets/ 中架构图来自已有论文资产，8段视频由本地论文素材复制，未修改原始视频。
EV-WM 展示示范及候选01/02/03短窗口；Onto-EV-WM展示已有示范回放与本体绑定，不是学习修复试验。
首页背景为 Onto-EV-WM 的仿真展示画面。论文、架构图与八段视频的公开发布已经获得作者确认。

## 展示样式更新

新增实验视频首页、固定导航与阅读进度、架构图细节缩放、八段视频放大播放及论文上一页/下一页切换。每篇完整收录原论文全部表格，注明表号、来源与评价口径；所有原始架构图、结果与视频文件保留。

## 完整原论文表格

直接从 arXiv HTML 提取全部 16 张原论文表格：OmniVLA-RL 2 张、EV-WM 5 张、Onto-EV-WM 7 张、HROS 1 张、RegenHarness 1 张。保留全部行、列、排名、数学符号与原文说明。支持折叠、横向滚动和放大查看。数据源文件为 assets/paper-tables.js。
