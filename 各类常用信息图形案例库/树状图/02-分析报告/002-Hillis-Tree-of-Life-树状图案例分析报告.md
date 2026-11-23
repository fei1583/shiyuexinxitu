# 002｜The Hillis Plot / Tree of Life｜树状图案例分析报告

## 基本信息与来源
David M. Hillis、Derrick Zwickl、Robin Gutell，University of Texas。原始下载页：https://sites.utexas.edu/antisense/download-hillis-plot-tree-of-life/；PDF：https://sites.utexas.edu/antisense/wp-content/uploads/sites/5922/2025/01/tree.pdf。作者说明基于约3,000个物种的小亚基rRNA序列分析，允许非商业教育用途，其他用途需联系作者。

## 树状结构判定
作品以根部和分支表达系统发育关系，末端节点对应采样物种/分类群。严格树状结构的父子关系应无环且每个节点（根除外）仅一个父节点；该图符合树状/系统发育树组织语法。分支长度是否代表遗传距离或其他量值，必须依据配套方法和图例，不可仅凭视觉长度判断。

## 数据结构
节点表node_id、taxon_label、taxonomic_rank、parent_id、sample_status；边表edge_id、parent_node、child_node、branch_length、branch_length_unit；来源表sequence_id、gene_region、reference。约3,000个物种是样本规模，不代表全部物种。

## 统计图形应用
本图为系统发育树，不是常规统计图。可描述节点/末端分类群数量和层级深度；分支长度若有方法定义才可定量解释。不可从画面比例反推未给出的物种丰度。

## 视觉编码与叙事
根部到末端的分支路径表示谱系分化；标签提供物种/分类群识别。阅读从共同祖先沿分支逐步向末端展开。树的视觉简洁性不能掩盖采样不均衡：作者明确说明物种样本受可获得性影响，部分大类群可能过度或不足代表。

## 图片与工作簿
原图由用户手动上传；若原始序列数据未公开，不制作伪造的序列Excel。可建立图像转录字段表并标注“图面转录”。
