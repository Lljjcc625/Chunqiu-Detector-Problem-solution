# Chunqiu Detector-Problem solution / 春秋检测器问题解决方案

[English](README.md) | **中文**

> 您可以在下方选择语言查看此文档，或访问我们的在线交互文档平台（支持实时关键词搜索）。

## 🌐 在线文档（GitHub Pages）

👉 **[https://mingzun09.github.io/Chunqiu-Detector-Problem-solution/](https://mingzun09.github.io/Chunqiu-Detector-Problem-solution/)**

站点使用 **Docsify** 构建（纯前端单页，无构建步骤）：入口为根目录的 `index.html`，侧边栏与导航分别来自 `_sidebar.md` / `_navbar.md`，正文直接读取 `language/answer_zh.md` 与 `language/answer_en.md`（**无需改站点文件**，提交后自动更新）。

- 深浅色主题跟随浏览器 / 系统设置（`prefers-color-scheme`），无需手动切换
- 顶部搜索框只检索**词条标题**，命中后展开对应条目
- 文档内容仍维护在 `language/answer_zh.md` 与 `language/answer_en.md`

本地预览（Docsify 通过 XHR 读取 Markdown，必须走 HTTP，不能直接双击打开 `index.html`）：

```bash
python -m http.server 8000    # 或任意静态服务器，如 npx serve
# 打开 http://localhost:8000/
```

> 发布流程：`.github/workflows/pages.yml` 在 push 到 `main` 后把仓库根目录发布到 GitHub Pages。

---

## 语言选择

请选择以下语言之一来查看解决方案文件。

[中文解决方案](/language/answer_zh.md) | [English Solutions](/language/answer_en.md)

> 文档中包含大量嵌入式链接（蓝色突出显示），点击即可跳转至对应的项目/文件地址。

---

## 依赖与文件说明

仓库中包含了部分自动化修复脚本与 KPM 模块，位于 `/File/` 目录下：

- `/File/Found property.sh` — 修复 Found property 属性检测
- `/File/Tampered Attestation Key(26)Pass.sh` — 修复证书 Patch 标签异常
- `/File/shamiko_Plus.sh` — 隐藏属性区空洞修改
- `/File/Bin/Nohello-v1.8.2.9-83-b3e7d87-release.kpm` — APatch 隐藏 KPM 模块
- `/File/Doc/ksu_kp_sidechannel_zh.md` — KSU/APatch 侧信道检测原理说明
- [`/File/Doc/thanks.md`](File/Doc/thanks.md) — 致谢清单（完整署名）

---

## 反馈与参与贡献

欢迎提交 Issues 或 Pull Requests 补充新的检测项及解决方案！

You can fork and modify the repository, then pull requests. I will check and merge them.

---

## 致谢

完整致谢清单见 **[`File/Doc/thanks.md`](File/Doc/thanks.md)** —— 文档贡献者、特别致谢与工具自动化，每条均附提交/PR 佐证。

- **文档贡献者：** 铭鐏（[@mingzun09](https://github.com/mingzun09)）· [@YiJieqwq](https://github.com/YiJieqwq) · 741afb7 · huoyan1231 · juanma0511 · Young-Six-6 · HongSir6
- **特别致谢：** [Matsuzaka Yuki](https://github.com/matsuzaka-yuki) · [JeTeeZnTmax](https://github.com/jeteezntmax)
- **工具与自动化：** google-labs-jules[bot]

> [@JeTeeZnTmax](https://github.com/jeteezntmax) 提供了 **16 个检测点**的整理与线索，但未在本仓库提交，故不出现在 GitHub 贡献者列表中，已在致谢清单中记录。

---

## 维护者

- [@mingzun09](https://github.com/mingzun09) — 仓库所有者
- [@YiJieqwq](https://github.com/YiJieqwq) — 维护者
