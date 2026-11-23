# 001｜Family tree: a guide to the Chinese kinship system｜树状图案例分析报告

## 1. 案例定位
- **原图标题：** Family tree: a guide to the Chinese kinship system
- **媒体/日期/作者：** South China Morning Post；2024-02-14；Kaliz Lee
- **本目录分析角度：** 世代层级与分支布局
- **主类型归属：** 关系图；本报告作为树状图辅助分类案例
- **工作簿结构：** 4张表，分别为称谓词汇表、家族树关系结构、读图规则与使用说明、来源与元数据。

## 2. 树状层级
工作簿将图形概括为7个世代/关系层级：
1. 高祖辈/曾祖辈；
2. 祖父母辈；
3. 父母辈；
4. 同辈（兄弟姐妹/堂表亲）；
5. 本人及配偶；
6. 子女辈（子女及侄甥/外甥）；
7. 孙辈。
另以父系（Paternal）和母系（Maternal）作为横向谱系维度，分别使用棕色与紫色。

## 3. 树状结构的特征与边界
图中通过由上至下的世代排列和分支连接形成树状阅读骨架；本人位于中部，祖辈向上、后代向下，旁系亲属从父母及祖辈节点向两侧展开。

但这不是纯粹的严格树：配偶关系、姻亲关系及旁系亲属引入跨分支关联。严格树要求除根节点外每个节点只有一个父节点且不存在环；此图表达的是多关系亲属网络，树状布局只是组织与阅读方式。因此树状图仅为辅助类型，关系图才是主分类。

## 4. 数据结构建议
- 层级节点表：node_id、label、generation_level、branch_side。
- 关系边表：edge_id、source_node、target_node、relation_type、lineage_side、direction。
- 称谓表：term_id、English relation、粤语汉字、romanisation、gender、seniority、affinity_type。
- 注释表：rule_id、symbol_rule、reading_instruction、source_note。
将“节点层级”与“关系边”分表，避免树状布局掩盖网络关系。

## 5. 视觉编码与阅读
- 纵向位置：表示世代层级。
- 横向位置：区分父系/母系分支及旁系展开。
- 棕色/紫色线路：分别标示父系/母系。
- 中央YOU / YOUR SPOUSE：定位读者的参照位置。
- 曲线连接：展示亲属关系路径。
- 圆形/星形符号：工作簿说明分别表示男性/女性。
- 英文、繁体中文及粤语罗马拼写：形成关系解释与称谓对照。

## 6. 适用价值
适用于展示家族谱系、组织层级、分类系统、继承路径等具有明显层级主轴的内容。若存在大量跨层级、跨分支关系，建议使用关系网络图或混合树网结构，而非强行转化为纯树。

## 7. 本案例数据盘点
- 称谓词汇表：47条。
- 家族树关系结构：9条。
- 读图规则与使用说明：14条。
- 来源与元数据：10项。
以上是工作簿记录数，不是人口样本量。

## 8. 来源与限制
原图为South China Morning Post 2024-02-14 A12版，作者Kaliz Lee。工作簿记录两项参考来源：Association for Conservation of Hong Kong Indigenous Languages、Cantonese Museum。当前未提供原始文章URL。对称谓表中英文与汉字对应疑点不作擅自修正，具体见关系图主报告。
