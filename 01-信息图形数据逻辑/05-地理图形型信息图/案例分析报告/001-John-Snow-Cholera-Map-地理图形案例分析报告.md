# 001｜Plan Showing the Ascertained Deaths from Cholera｜地理图形型信息图案例分析报告

## 基本信息与原始来源
John Snow，1855年报告地图。Wellcome Collection原始藏品页：https://wellcomecollection.org/works/dx4prdbj。该页提供全尺寸JPG并标记Public Domain Mark，可按其署名说明使用。

## 图形结构与类型判定
地图标示1854年伦敦Soho地区霍乱死亡位置，并呈现Broad Street公共水泵及街道空间。死亡标记与水泵位置构成空间分布分析。需根据原图图例辨认每个标记代表的死亡数/住户等单位，不得在未核图例前推断单个短线的精确计数。

## 数据结构与字段建议
将可观察实体拆成独立记录，字段至少包含对象编号、原始标签、规范化标签、类别、属性、单位/时间口径（如适用）、来源位置和识别置信度。关系型内容另设关系边表，不把多条记录塞入同一单元格。

## 视觉编码与信息框架
逐项记录位置、长度/面积、颜色、形状、方向、连线和文字层级的含义。只有原图图例或作者方法明确支持时才将视觉变量解释为数据编码；其余标记为布局或装饰。

## 统计图形应用
建议空间事件表：case_id/mark_id、map_location、street、death_count（仅在图例确认时）、water_pump_id、source_page、transcription_confidence。无可恢复坐标时不制造经纬度。

## 叙事路径与设计评价
说明读者从哪里开始、如何浏览主要信息、如何获得结论；评价图例、标签、可读性、信息密度及潜在误读。

## 图片与工作簿归档状态
- 原图：由资料库维护者手动上传至本报告同编号的案例图片/示例图目录；本报告不嵌入或伪造图片文件。
- Excel：由资料库维护者手动上传；本报告提供字段拆解建议，不将推断数据冒充原始数据。
- 正式计数：原图归档并完成核验后计入已归档案例数量。

## 来源与版权边界
John Snow，1855年报告地图。Wellcome Collection原始藏品页：https://wellcomecollection.org/works/dx4prdbj。该页提供全尺寸JPG并标记Public Domain Mark，可按其署名说明使用。

## 修订记录
- 2026-11-23：建立基于可核验公开来源的案例研究文字；等待原图/工作簿归档后进行逐项复核。
