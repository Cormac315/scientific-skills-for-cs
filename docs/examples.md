# 使用示例（计科 / 网安）

以下提示词可直接交给已安装本仓库 skill 的 Agent。

## 流量 / 日志异常检测基线

```
用 scikit-learn 和 shap 对网络流量特征表做二分类异常检测：
划分训练/测试集，比较随机森林与梯度提升，输出 ROC/PR、混淆矩阵，
并用 SHAP 解释最重要的特征。用 scientific-visualization 出出版级图。
```

**常用 skill**：`scikit-learn(经典机器学习)` `shap(模型可解释性分析)` `statistical-analysis(统计分析指导)` `scientific-visualization(科研级绑图)`

## 攻击图 / 资产拓扑分析

```
用 networkx 读入主机-服务图，计算中心性、社区划分与关键路径，
可视化关键资产与横向移动路径，结果写入 Markdown + Mermaid。
```

**常用 skill**：`networkx(复杂网络分析)` `markdown-mermaid-writing(Markdown与Mermaid绘图)` `matplotlib(Matplotlib绑图)`

## 图神经网络恶意软件/流量分类

```
用 torch-geometric 搭建 GCN/GAT，对进程调用图或会话图做图分类，
用 pytorch-lightning 训练，记录验证指标并保存 checkpoint。
```

**常用 skill**：`torch-geometric(图神经网络)` `pytorch-lightning(深度学习训练框架)` `optimize-for-gpu(GPU加速计算)`

## 文献综述与投稿

```
用 literature-review 和 paper-lookup 检索 IDS / 图神经网络安全 近三年论文，
整理 bib，用 scientific-writing 起草 Related Work，venue-templates 对齐 IEEE/ACM 格式。
```

**常用 skill**：`literature-review(文献综述)` `paper-lookup(学术论文检索)` `citation-management(引用管理)` `scientific-writing(科研写作)` `venue-templates(会议期刊投稿模板)`
