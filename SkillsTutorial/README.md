# SkillsTutorial

2026 年秋冬学期浙江大学计算机学院朋辈辅学「技能拾遗」课程仓库。

课程主页：https://learn.auspiow.top/SkillsTutorial/

本课程旨在介绍一些计算机专业学习与开发过程中常用、实用，但传统课程中较少系统讲授的技能，包括 Git、Linux、Markdown 等工具与工作流。

## 课程内容

| 课程 | 主题 | Slides | PDF |
| --- | --- | --- | --- |
| Lec 0 | 课程前瞻 | [Slides](https://learn.auspiow.top/SkillsTutorial/slides/lec0/) | [PDF](https://learn.auspiow.top/SkillsTutorial/pdf/lec0.pdf) |
| Lec 1 | Git 与 GitHub | TBD | TBD |
| Lec 2 | Linux 及其工作流 | TBD | TBD |
| Lec 3 | Markdown 与文档写作 | TBD | TBD |
| Lec 4 | AI | TBD | TBD |

具体课程安排请参见[课程主页](https://learn.auspiow.top/SkillsTutorial/)。

## 构建与部署

课程使用 [reveal-md](https://github.com/webpro/reveal-md) 编写与构建幻灯片。
*特别感谢 [@TonyCrane](https://tonycrane.cc/) 开源的[模板](https://github.com/TonyCrane/slide-template)*

1. Clone 仓库：

   ```bash
   git clone https://github.com/Auspiow/learn.git
   cd learn
   ```

2. 安装依赖：

   ```bash
   npm install
   ```

3. 实时预览：

   ```bash
   npx reveal-md SkillsTutorial/slides-src/lec0.md -w
   ```

## 阅读

幻灯片使用 [reveal.js](https://revealjs.com/) 展示。

- 使用方向键切换幻灯片。
- 按 `Esc` 键进入幻灯片总览。
- 按 `?` 键查看快捷键。

## License

This project is licensed under the MIT License.