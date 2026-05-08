# Design Specification — 代客发声培训 PPT

## I. Canvas
- Format: PPT 16:9
- Size: 13.333 x 7.5 inch
- Page count: 10

## II. Audience
客服座席、客服专人、运营协同岗位与管理人员。

## III. Style Objective
物流企业培训课件风格：蓝白主色、红色强调、清晰层级、可编辑图形元素。

## IV. Color Scheme
- Primary Blue: #003C96
- Secondary Blue: #0A4FB3
- Light Blue: #EAF2FF
- Mid Blue: #B7C9E8
- Accent Red: #D20A1E
- Text Dark: #111111

## V. Typography
- Font family: Microsoft YaHei / SimHei fallback
- Title: 25–44 pt, bold
- Section header: 18–25 pt, bold
- Body: 14–18 pt

## VI. Icon Usage
使用简单可编辑几何图形与 Unicode 符号替代不可编辑图片图标，确保 PowerPoint 中可点击编辑。

## VII. Image Usage
参考图中的物流、货车、道路、扩音器、分拣线等意象均以可编辑形状重绘，不把整页截图作为背景。

## VIII. Layout Plan
1. Cover: 大标题 + 扩音器/传送带示意
2. Background: 左侧双思维卡片 + 右侧路径图
3. Classification: 左漏斗 + 右文本分组
4. Instant voice: 四卡片网格
5. Post-event analysis: 左要点 + 右蜂窝流程
6. Six-dimension model: 左六维清单 + 右分拣设备
7. Phase 1: 左步骤 + 右金字塔
8. Phase 2: 左行动清单 + 右闭环环路
9. System empowerment: 左纸面混乱 + 右系统面板
10. Closing: 左行动清单 + 右开箱起飞

## IX. Editability Requirements
- 文案全部为独立文本框
- 卡片、圆形、箭头、道路、流程框均为 PowerPoint 原生形状
- 不使用整页图片作为幻灯片背景
- 尽量减少不可编辑元素

## X. Deliverables
- Editable PPTX
- Project source markdown and generation script

## XI. Notes
本次重建目标是“支持编辑”，不是像素级复制图片截图。
