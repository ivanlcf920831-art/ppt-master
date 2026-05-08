# 代客发声 · PPT Master 可编辑重建项目

本项目按 `skills/ppt-master/SKILL.md` 的思路重新执行：

Source → Project → Strategist → Executor → Export

## 产物

- `source.md`：从用户提供的 10 张页面图中整理出的页面内容
- `design_spec.md`：设计规范
- `spec_lock.md`：执行锁定参数
- `create_pptmaster_editable.py`：本地可运行的可编辑 PPTX 生成脚本

> 说明：由于当前 ChatGPT 容器不能解析 github.com 域名，无法在容器内直接 clone / 执行 GitHub 仓库脚本；已通过 GitHub connector 把项目文本文件写入仓库，并在本地按 PPT Master 的“可编辑元素”要求生成 PPTX。
