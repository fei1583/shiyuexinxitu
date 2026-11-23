# 002｜Context-Preserving, Dynamic Word Cloud Visualization｜词云图案例分析报告

## 基本信息与原始来源
Weiwei Cui、Yingcai Wu、Shixia Liu、Furu Wei、Michelle Zhou、Huamin Qu，IEEE PacificVis 2010。Microsoft Research论文页：https://www.microsoft.com/en-us/research/publication/context-preserving-dynamic-word-cloud-visualization-2/；期刊版本DOI：https://doi.org/10.1109/MCG.2010.102。

## 图形结构与类型判定
方法将多个时间点的代表性关键词词云与趋势图结合，表达文档集合的语义演变。趋势图总结整体内容变化，词云呈现各时点关键词；几何网格与自适应力导向布局用于保持相邻时点词云的语义连贯和空间稳定。

## 数据结构与字段建议
将可观察实体拆成独立记录，字段至少包含对象编号、原始标签、规范化标签、类别、属性、单位/时间口径（如适用）、来源位置和识别置信度。关系型内容另设关系边表，不把多条记录塞入同一单元格。

## 视觉编码与信息框架
逐项记录位置、长度/面积、颜色、形状、方向、连线和文字层级的含义。只有原图图例或作者方法明确支持时才将视觉变量解释为数据编码；其余标记为布局或装饰。

## 统计图形应用
数据结构需包含document_id、time_point、keyword、importance_weight、topic/group、layout_position、semantic_similarity。论文示例可分析方法结构，但原始语料/权重若未公开，不构造伪数据。

## 叙事路径与设计评价
说明读者从哪里开始、如何浏览主要信息、如何获得结论；评价图例、标签、可读性、信息密度及潜在误读。

## 图片与工作簿归档状态
- 原图：由资料库维护者手动上传至本报告同编号的案例图片/示例图目录；本报告不嵌入或伪造图片文件。
- Excel：由资料库维护者手动上传；本报告提供字段拆解建议，不将推断数据冒充原始数据。
- 正式计数：原图归档并完成核验后计入已归档案例数量。

## 来源与版权边界
Weiwei Cui、Yingcai Wu、Shixia Liu、Furu Wei、Michelle Zhou、Huamin Qu，IEEE PacificVis 2010。Microsoft Research论文页：https://www.microsoft.com/en-us/research/publication/context-preserving-dynamic-word-cloud-visualization-2/；期刊版本DOI：https://doi.org/10.1109/MCG.2010.102。

## 修订记录
- 2026-11-23：建立基于可核验公开来源的案例研究文字；等待原图/工作簿归档后进行逐项复核。
