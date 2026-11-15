# 学习记录 / Study Notes

个人学习记录仓库：用 LaTeX（XeLaTeX + ctexart）整理课程与教程笔记，边学边记。

## 笔记列表

| 笔记 | 说明 | PDF |
| --- | --- | --- |
| [Git 项目管理笔记](./Git笔记/main.pdf) | 从日常提交到科研复现：四区域模型、日常工作流、分支与冲突、撤销、大文件管理、实验复现 | [Git笔记/main.pdf](./Git笔记/main.pdf) |

## 课程资料

cs336 课程章节原版 PDF（仅个人学习使用）：

- [第一章](./cs336章节/第一章.pdf) · [第二章](./cs336章节/第二章.pdf) · [第三章](./cs336章节/第三章.pdf)

## 目录结构

每个笔记一个子文件夹，包含：

- `main.tex` — 笔记源码
- `preamble.sty` — 全局样式（Nord 配色，自定义 定理 / 例子 / 避坑 / 代码块 环境）
- `main.pdf` — 编译产物

## 如何编译

需要 TeX Live（含 `ctex`、`tcolorbox`、`tikz` 等宏包）：

```bash
cd Git笔记
xelatex main.tex   # 编译两遍以生成正确的书签
```

## 来源声明

《Git 项目管理笔记》整理自 Foundation of Embodied AI 课程讲义
《Git 使用教程：30 分钟必学与科研进阶参考》
（CC BY-NC-SA 4.0 · Xiong Zeng and contributors），仅作个人学习用途。
