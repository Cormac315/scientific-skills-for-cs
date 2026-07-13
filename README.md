# Scientific Agent Skills（计科 / 网安科研精简版）

本仓库自 [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) 精简而来：**仅保留计算机科学 / 网络安全科研可用的 74 个 skill**，已删除生物、医学、化学、材料、天文、地理等专用技能。

原名后附中文名称，便于检索与安装。

> 说明：原仓库几乎没有渗透测试 / 密码学 / 协议逆向专用 skill。本精简集侧重 **ML 检测、图网络、统计实验、可复现流水线、文献写作与投稿**。

---

## 快速安装

```bash
# 安装本精简集（示例）
npx skills add Cormac315/scientific-skills-for-cs

# 或按需安装单个 skill
gh skill install Cormac315/scientific-skills-for-cs scikit-learn
```

也可将本仓库的 `skills/<name>/` 复制到你的 Agent Skills 目录。

---

## Skill 清单（74）

### 1. 机器学习 / AI

| Skill | 中文名称 |
|-------|----------|
| aeon | 时间序列机器学习 |
| scikit-learn | 经典机器学习 |
| pytorch-lightning | 深度学习训练框架 |
| transformers | Transformers 大模型 |
| torch-geometric | 图神经网络 |
| stable-baselines3 | 强化学习 |
| pufferlib | 高性能强化学习 |
| shap | 模型可解释性分析 |
| umap-learn | UMAP 降维 |
| timesfm-forecasting | TimesFM 时序预测 |
| hypogenic | LLM 假设生成与检验 |
| scikit-survival | 生存 / 时至事件分析 |

### 2. 图网络 / 系统仿真

| Skill | 中文名称 |
|-------|----------|
| networkx | 复杂网络分析 |
| simpy | 离散事件仿真 |

### 3. 统计 / 数学 / 优化

| Skill | 中文名称 |
|-------|----------|
| statistical-analysis | 统计分析指导 |
| statistical-power | 统计功效与样本量 |
| statsmodels | 统计建模 |
| pymc | 贝叶斯建模 |
| sympy | 符号数学 |
| pymoo | 多目标优化 |
| matlab | MATLAB / Octave 数值计算 |

### 4. 数据工程 / 高性能计算

| Skill | 中文名称 |
|-------|----------|
| dask | 分布式计算 |
| polars | 高性能 DataFrame |
| vaex | 超大规模表格分析 |
| zarr-python | 分块数组存储 |
| optimize-for-gpu | GPU 加速计算 |
| modal | Modal 云端 GPU |
| get-available-resources | 计算资源探测 |
| nextflow | 可复现数据工作流 |
| geopandas | 地理空间向量分析 |

### 5. 量子计算

| Skill | 中文名称 |
|-------|----------|
| qiskit | IBM 量子计算 |
| cirq | Google 量子计算 |
| pennylane | 量子机器学习 |
| qutip | 开放量子系统仿真 |

### 6. 可视化 / 示意图

| Skill | 中文名称 |
|-------|----------|
| matplotlib | Matplotlib 绑图 |
| seaborn | 统计可视化 |
| scientific-visualization | 科研级绑图 |
| scientific-schematics | 科研示意图生成 |
| markdown-mermaid-writing | Markdown 与 Mermaid 绘图 |
| infographics | 信息图制作 |
| generate-image | AI 图像生成 |

### 7. 文献检索 / 科研方法 / 写作投稿

| Skill | 中文名称 |
|-------|----------|
| literature-review | 文献综述 |
| paper-lookup | 学术论文检索 |
| paperzilla | Paperzilla 论文助手 |
| bgpt-paper-search | BGPT 论文检索 |
| research-lookup | 科研信息检索 |
| exa-search | Exa 网页学术搜索 |
| parallel-web | Parallel 网页学术检索 |
| citation-management | 引用管理 |
| pyzotero | Zotero 引用库操作 |
| peer-review | 同行评审 |
| scholar-evaluation | 学术评价 |
| scientific-writing | 科研写作 |
| scientific-brainstorming | 科研头脑风暴 |
| scientific-critical-thinking | 科学批判性思维 |
| hypothesis-generation | 假设生成 |
| experimental-design | 实验设计 |
| research-grants | 科研基金申请 |
| venue-templates | 会议期刊投稿模板 |
| what-if-oracle | 情景推演分析 |
| consciousness-council | 多视角审议 |
| dhdna-profiler | 认知模式分析 |
| autoskill | 工作流技能自动起草 |
| arbor | 假设树自主优化 |
| open-notebook | 开源研究笔记本 |

### 8. 文档 / 幻灯片 / 海报

| Skill | 中文名称 |
|-------|----------|
| pdf | PDF 处理 |
| docx | Word 文档处理 |
| xlsx | Excel 表格处理 |
| pptx | PowerPoint 幻灯片 |
| pptx-posters | PPT 科研海报 |
| latex-posters | LaTeX 科研海报 |
| scientific-slides | 科研幻灯片制作 |
| liteparse | 本地文档解析 |
| markitdown | 文档转 Markdown |

---

## 目录结构

```
skills/
  <skill-name>/
    SKILL.md          # 主文档（Agent 自动发现）
    references/       # 可选参考资料
    scripts/          # 可选脚本
```

---

## 许可

继承上游仓库许可证，详见 [LICENSE.md](LICENSE.md)。各 skill 自身许可见对应目录内声明。

上游项目请引用：

```bibtex
@software{kdense2025scientificagentskills,
  author = {{K-Dense}},
  title = {Scientific Agent Skills},
  year = {2025},
  url = {https://github.com/K-Dense-AI/scientific-agent-skills}
}
```
