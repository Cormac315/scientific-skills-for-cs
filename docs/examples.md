# 使用示例（计科 / 网安）

以下提示词可直接交给已安装本仓库 skill 的 Agent。

## 流量 / 日志异常检测基线

```
用 scikit-learn 和 shap 对网络流量特征表做二分类异常检测：
划分训练/测试集，比较随机森林与梯度提升，输出 ROC/PR、混淆矩阵，
并用 SHAP 解释最重要的特征。用 scientific-visualization 出出版级图。
```

**常用 skill**：`scikit-learn` `shap` `statistical-analysis` `scientific-visualization`

## 攻击图 / 资产拓扑分析

```
用 networkx 读入主机-服务图，计算中心性、社区划分与关键路径，
可视化关键资产与横向移动路径，结果写入 Markdown + Mermaid。
```

**常用 skill**：`networkx` `markdown-mermaid-writing` `matplotlib`

## 图神经网络恶意软件/流量分类

```
用 torch-geometric 搭建 GCN/GAT，对进程调用图或会话图做图分类，
用 pytorch-lightning 训练，记录验证指标并保存 checkpoint。
```

**常用 skill**：`torch-geometric` `pytorch-lightning` `optimize-for-gpu`

## 文献综述与投稿

```
用 literature-review 和 paper-lookup 检索 IDS / 图神经网络安全 近三年论文，
整理 bib，用 scientific-writing 起草 Related Work，venue-templates 对齐 IEEE/ACM 格式。
```

**常用 skill**：`literature-review` `paper-lookup` `citation-management` `scientific-writing` `venue-templates`
