# 002｜Infographic: Extradition in Canada｜流程图案例分析报告

## 基本信息与原始来源
Department of Justice Canada官方页面：https://canada.justice.gc.ca/eng/cj-jp/emla-eej/desc_extradition.html；文字版流程说明与PDF入口：https://www.justice.gc.ca/eng/cj-jp/emla-eej/extradition.html。官方文字版列出三个阶段和各分支。

## 图形结构与类型判定
流程分为Authority to Proceed、Judicial、Ministerial三个阶段。阶段一包含紧急临时逮捕、正式请求、是否签发Authority to Proceed；阶段二为引渡听证，法官决定是否移交，并包含释放、上诉和司法复核；阶段三由司法部长决定是否移交，并有司法复核及向加拿大最高法院申请许可上诉等路径。

## 数据结构与字段建议
将可观察实体拆成独立记录，字段至少包含对象编号、原始标签、规范化标签、类别、属性、单位/时间口径（如适用）、来源位置和识别置信度。关系型内容另设关系边表，不把多条记录塞入同一单元格。

## 视觉编码与信息框架
逐项记录位置、长度/面积、颜色、形状、方向、连线和文字层级的含义。只有原图图例或作者方法明确支持时才将视觉变量解释为数据编码；其余标记为布局或装饰。

## 统计图形应用
节点表记录阶段、步骤号、责任主体、判断条件、结果和官方文本段落；边表记录yes/no/if条件。将流程图文字版逐项拆成节点，不补写个案结论。

## 叙事路径与设计评价
说明读者从哪里开始、如何浏览主要信息、如何获得结论；评价图例、标签、可读性、信息密度及潜在误读。

## 图片与工作簿归档状态
- 原图：由资料库维护者手动上传至本报告同编号的案例图片/示例图目录；本报告不嵌入或伪造图片文件。
- Excel：由资料库维护者手动上传；本报告提供字段拆解建议，不将推断数据冒充原始数据。
- 正式计数：原图归档并完成核验后计入已归档案例数量。

## 来源与版权边界
Department of Justice Canada官方页面：https://canada.justice.gc.ca/eng/cj-jp/emla-eej/desc_extradition.html；文字版流程说明与PDF入口：https://www.justice.gc.ca/eng/cj-jp/emla-eej/extradition.html。官方文字版列出三个阶段和各分支。

## 修订记录
- 2026-11-23：建立基于可核验公开来源的案例研究文字；等待原图/工作簿归档后进行逐项复核。
