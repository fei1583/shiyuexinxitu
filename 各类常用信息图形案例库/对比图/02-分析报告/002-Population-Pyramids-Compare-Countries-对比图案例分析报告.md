# 002｜Compare Population Pyramids of Any Two Countries｜对比图案例分析报告

## 基本信息与来源
PopulationPyramids.org，作者/维护者Marko Visic。交互页面：https://www.populationpyramids.org/compare。页面标明数据来自联合国World Population Prospects 2024，并说明可并列、叠加比较两国人口金字塔及年龄/性别差异。

## 图形结构与类型学
交互工具将两个国家的人口金字塔并列或叠加，并提供差异图。年龄组以五岁分组；男性与女性分列；差异图中颜色区分哪一国家在相应性别/年龄组人数更多。主类型为对比图，内部图形为双人口金字塔和差异条形图。

## 数据结构
字段：country_id、country_name、reference_date、age_group、sex、population、population_share、difference_value、data_variant、source_revision。须记录选定国家和年份；2026年页面展示的数值含UN中方案预测，不能误写为已观测人口。

## 统计图形应用
人口金字塔适合比较年龄与性别构成；差异图直接呈现各年龄组人数差。绝对人数与占比回答不同问题，比较前必须确认所选模式和单位。

## 视觉编码
金字塔横向长度编码人口数量或比例；左右侧区分性别；年龄组纵向排列；差异图颜色编码哪一国家较高，条长编码差额。颜色映射以页面图例为准。

## 信息框架与叙事
用户先选择两个国家与年份，再读取并列金字塔/叠加图，最后用差异图定位差距最大的年龄组。它是可交互比较工具而非单张固定海报。

## 证据边界
页面数据源为UN WPP 2024；年份与估计/预测状态须随用户选择记录。图片/截图与Excel由用户手动上传；若导出数据，应保留筛选条件和下载日期。
