<div align="center">

<a href="https://stardreamfly.com/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./banner-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./banner-light.svg" />
    <img alt="星梦科技 StarDreamTech — 让梦想像星星一样闪亮" src="./banner-dark.svg" width="100%" />
  </picture>
</a>

<br />

<p>
  <a href="https://stardreamfly.com/"><img src="https://img.shields.io/badge/官网-stardreamfly.com-6b56ff?style=flat-square&logo=sparkles&logoColor=white" alt="官网 stardreamfly.com" /></a>
  <a href="https://stardreamfly.com/projects/starlock/demo/"><img src="https://img.shields.io/badge/在线试玩-星锁%20StarLock-a78bfa?style=flat-square" alt="星锁在线试玩" /></a>
  <a href="https://github.com/StarDreamTech/homebrew-tap"><img src="https://img.shields.io/badge/Homebrew-stardreamtech%2Ftap-f2c879?style=flat-square&logo=homebrew&logoColor=140f2a" alt="Homebrew Tap" /></a>
  <a href="mailto:hi@stardreamfly.com"><img src="https://img.shields.io/badge/联系-hi%40stardreamfly.com-2cb8e6?style=flat-square" alt="联系邮箱 hi@stardreamfly.com" /></a>
</p>

<p>
  专注 <strong>本地优先（Local-first）</strong> 桌面工具、AI 对话档案与智能体、网页监控与人机验证基础设施。<br />
  把已发布应用与正在演进的想法放在同一片星图里，真实展示进度，欢迎试用、提 Issue 与参与贡献。
</p>

</div>

---

## ✨ 已发布 · 开箱即用

<table>
  <tr>
    <td width="33.3%" valign="top">
      <strong>星笺 <a href="https://github.com/StarDreamTech/StarClip">StarClip</a></strong> &nbsp;<code>v0.2.7</code><br />
      <sub>Rust · Tauri 2 · SQLite</sub>
      <p>本地优先剪贴板管理器，支持历史检索、星码集代码片段与星绘坊分享卡片。</p>
      <sub>macOS (Apple Silicon) · Windows x64</sub><br />
      <a href="https://stardreamfly.com/projects/starclip/">介绍页</a> &nbsp;·&nbsp; <a href="https://github.com/StarDreamTech/StarClip/releases/latest">下载安装包</a>
    </td>
    <td width="33.3%" valign="top">
      <strong>星镜 <a href="https://github.com/StarDreamTech/StarShot">StarShot</a></strong> &nbsp;<code>v0.3.3</code><br />
      <sub>Rust · Tauri 2 · Vue 3</sub>
      <p>桌面截图、标注、置顶贴图与图片美化工具，支持本地敏感信息一键打码。</p>
      <sub>macOS 12+ (Apple Silicon) · Windows x64</sub><br />
      <a href="https://stardreamfly.com/projects/starshot/">介绍页</a> &nbsp;·&nbsp; <a href="https://github.com/StarDreamTech/StarShot/releases/latest">下载安装包</a>
    </td>
    <td width="33.3%" valign="top">
      <strong>星匣 <a href="https://github.com/StarDreamTech/StarVault">StarVault</a></strong> &nbsp;<code>v0.1.4</code><br />
      <sub>Python · Desktop / CLI / MCP</sub>
      <p>本地优先的 AI 对话增量档案，支持附件与 Skill 迁移，并通过 MCP 检索记忆。</p>
      <sub>macOS (Apple Silicon) · Linux CLI</sub><br />
      <a href="https://stardreamfly.com/projects/starvault/">介绍页</a> &nbsp;·&nbsp; <a href="https://github.com/StarDreamTech/StarVault/releases/latest">下载安装包</a>
    </td>
  </tr>
</table>

### 🍺 一行命令安装（Apple Silicon Mac）

```bash
brew install --cask stardreamtech/tap/starclip   # 星笺 · 剪贴板管理器
brew install --cask stardreamtech/tap/starshot   # 星镜 · 截图 / 标注 / 贴图
brew install --cask stardreamtech/tap/starvault  # 星匣 · AI 对话档案桌面端
brew install stardreamtech/tap/starvault         # 星匣 · 仅 CLI / MCP
```

> Windows 安装包与校验和（`SHA256SUMS`）请在各项目 Release 页面获取。

---

## 🛠️ 开发中 · 已有代码实现

<table>
  <thead>
    <tr>
      <th align="left">项目</th>
      <th align="left">核心能力</th>
      <th align="center">状态</th>
      <th align="center">入口</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td nowrap><strong>星锁</strong><br /><sub><a href="https://github.com/StarDreamTech/StarLock">StarLock</a></sub></td>
      <td>开源人机验证 SDK 与 FastAPI 服务，内置 8 种题型，提供 Vue / React 与 Python / Go SDK</td>
      <td align="center" nowrap><code>v0.8.0</code></td>
      <td align="center" nowrap><a href="https://stardreamfly.com/projects/starlock/demo/">在线试玩</a>&nbsp;·&nbsp;<a href="https://stardreamfly.com/projects/starlock/">详情</a></td>
    </tr>
    <tr>
      <td nowrap><strong>星哨</strong><br /><sub><a href="https://github.com/StarDreamTech/StarWatch">StarWatch</a></sub></td>
      <td>可自托管的网页与接口定时监控平台，支持字段提取、接口断言与历史内容逐行 Diff</td>
      <td align="center" nowrap><code>开发中</code></td>
      <td align="center" nowrap><a href="https://stardreamfly.com/projects/starwatch/">详情</a></td>
    </tr>
    <tr>
      <td nowrap><strong>星使</strong><br /><sub><a href="https://github.com/StarDreamTech/StarEnvoy">StarEnvoy</a></sub></td>
      <td>按地区、关键词与薪资筛选 BOSS 岗位，集中查看结果与沟通记录（PySide6）</td>
      <td align="center" nowrap><code>源码版</code></td>
      <td align="center" nowrap><a href="https://stardreamfly.com/projects/starenvoy/">详情</a></td>
    </tr>
    <tr>
      <td nowrap><strong>星口</strong><br /><sub><a href="https://github.com/StarDreamTech/StarPort">StarPort</a></sub></td>
      <td>从本机 Clash 配置按节点分配独立 SOCKS 端口并页面化管理启停（Go · mihomo）</td>
      <td align="center" nowrap><code>原型版</code></td>
      <td align="center" nowrap><a href="https://stardreamfly.com/projects/starport/">详情</a></td>
    </tr>
  </tbody>
</table>

---

## 🌱 筹备与孵化中

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>星码 <a href="https://github.com/StarDreamTech/starcode">starcode</a></strong> &nbsp;<sub>Fork 初始化</sub><br />
      基于 OpenCode 改造的开源 AI Agent 客户端 · <a href="https://stardreamfly.com/projects/starcode/">介绍</a>
    </td>
    <td width="50%" valign="top">
      <strong>星搭子 <a href="https://github.com/StarDreamTech/StarBuddy">StarBuddy</a></strong> &nbsp;<sub>第 0 期</sub><br />
      围绕原创角色「星芽」构建的个人电脑助手 · <a href="https://stardreamfly.com/projects/starbuddy/">介绍</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>星相 <a href="https://github.com/StarDreamTech/StarPersona">StarPersona</a></strong> &nbsp;<sub>筹备中</sub><br />
      规划中的开源指纹浏览器与多账号环境管理 · <a href="https://stardreamfly.com/projects/starpersona/">介绍</a>
    </td>
    <td width="50%" valign="top">
      <strong>星盘 <a href="https://github.com/StarDreamTech/StarDash">StarDash</a></strong> &nbsp;<sub>筹备中</sub><br />
      规划中的跨平台菜单栏与托盘状态面板 · <a href="https://stardreamfly.com/projects/stardash/">介绍</a>
    </td>
  </tr>
</table>

---

## 🤝 定制服务 & 联系我们

除开源项目外，也承接小而精的定制开发（先交付最小可用版本，再按实际使用迭代）：

<table>
  <tr>
    <td width="33.3%" valign="top">
      <strong>🤖 定制 Agent</strong><br />
      <sub>按工作流定制智能体，支持本地或私有部署，明确数据边界</sub>
    </td>
    <td width="33.3%" valign="top">
      <strong>🌐 定制官网</strong><br />
      <sub>面向个人、工作室或开源项目，兼顾深浅双色与移动端体验</sub>
    </td>
    <td width="33.3%" valign="top">
      <strong>💻 定制软件</strong><br />
      <sub>桌面工具、CLI 或轻量 Web 应用，数据可完全留在本地</sub>
    </td>
  </tr>
</table>

<p align="center">
  📬 <strong>联系与合作</strong>：<a href="mailto:hi@stardreamfly.com">hi@stardreamfly.com</a> &nbsp;·&nbsp;
  🌐 <a href="https://stardreamfly.com/">完整星图官网</a> &nbsp;·&nbsp;
  📄 <a href="https://stardreamfly.com/llms.txt">AI 文档索引 (llms.txt)</a> &nbsp;·&nbsp;
  ✨ <a href="https://cpython666.github.io">作者主页</a>
</p>
