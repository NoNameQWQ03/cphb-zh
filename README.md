# 竞赛程序员手册（中文翻译版）

> 原书：[Competitive Programmer's Handbook](https://cses.fi/book/) by Antti Laaksonen（源码仓库：[pllk/cphb](https://github.com/pllk/cphb)）

本书是《Competitive Programmer's Handbook》的中文翻译版（基于原书内容进行中文化与排版调整）。原书是竞赛编程的现代入门读物，讨论了竞赛编程中相关的编程技巧和算法设计技术。

## 编译说明

本项目使用 XeLaTeX 编译，需要安装 LaTeX 发行版（如 [MiKTeX](https://miktex.org/) 或 TeX Live）。

```bash
xelatex book.tex
xelatex book.tex
makeindex book.idx
xelatex book.tex
```

需要运行 `xelatex` 与 `makeindex` 以正确生成目录、交叉引用与索引。

## CSES 题目集

CSES 题目集包含一系列竞赛编程题目。你可以通过解题来练习书中介绍的技术。

https://cses.fi/problemset/

## 许可证

本书遵循知识共享 署名-非商业性使用-相同方式共享 4.0 国际许可协议（[Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)），中文翻译版本同样按该协议发布。

## 相关书籍

《Guide to Competitive Programming》是基于本书的印刷版，由 Springer 出版。还有俄语版 Олимпиадное программирование 和韩语版 알고리즘 트레이닝: 프로그래밍 대회 입문 가이드。

https://cses.fi/book/

## 致谢

- 原作者：Antti Laaksonen
- 中文翻译：AI 辅助翻译

## 问题反馈

如发现中文翻译、公式或排版问题，欢迎直接在本仓库的 [Issues](https://github.com/NoNameQWQ03/cphb-zh/issues) 中反馈，请勿就译文相关问题发送邮件打扰原作者。
