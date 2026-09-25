# med-notes

医学生的结构化医学笔记公开版。每篇笔记由两部分组成：

- `note.json` — 结构化源文件（章节、表格、流程图、三色标注）
- `note.html` — 用 [notes-htmlizer](https://github.com/surround-hue/notes-htmlizer) 渲染出的独立网页，双击即可在浏览器阅读，支持搜索、折叠目录、打印（Ctrl+P）

## 篇目

| 目录 | 主题 | 来源 |
|---|---|---|
| [`water-electrolyte/`](water-electrolyte/note.html) | 病理生理学 · 水、电解质代谢紊乱 | 以手写笔记为骨架，对照人民卫生出版社《病理生理学》（第 10 版）补全与订正 |

### water-electrolyte 内容范围

体液与渗透压基础 → 水钠代谢障碍二维分类 → 低渗/高渗/等渗性脱水 → 三类脱水横向对比 → 水中毒 → 水肿 → 钾的正常代谢 → 低钾/高钾血症 → 低钾 vs 高钾对比 → 考点速记 → **完整勘误表**（含原稿知识性错误的订正记录）。

## 复现渲染

```bash
pip 环境无需安装，纯 Python 标准库：
python notes_htmlizer.py note.json note.html
```

渲染器与 JSON 格式说明见 [notes-htmlizer](https://github.com/surround-hue/notes-htmlizer) 仓库。

## 免责声明

本仓库内容为**医学生个人学习笔记**，仅供学习交流。内容可能存在错误或过时之处，不构成任何医疗建议。临床决策请以最新版教材、临床指南与主诊医师意见为准。

## 许可

笔记内容以 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.zh) 提供：署名、相同方式共享。教材相关表述的著作权归原作者与人民卫生出版社所有，本笔记为学习目的的整理与再表达。
