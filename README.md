# qushengxixiaoluo.github.io

> 🌐 **个人主页 · [qushengxixiaoluo.github.io](https://qushengxixiaoluo.github.io/)**
> 用产品思维定义问题，用工程能力交付答案。

## ✨ 设计风格

**Neo-Brutalism · 黑色描边**

- 全站 3px 黑色描边 + 硬阴影（无模糊），按钮/卡片 hover 按压位移
- 描边大标题（Anton + text-stroke）、跑马灯条、贴纸式旋转角标、六边形描边头像
- 米白纸感底色 + 点阵纹理，彩色（黄/青/粉/橙/蓝/绿）点缀
- 分段入场动画与滚动揭示，适配 `prefers-reduced-motion`

## 🧠 内容框架：把自己写成一份 PRD

自我介绍按产品文档结构组织：

| 区块 | 内容 |
|------|------|
| **产品说明书** | 01 定位 · 02 目标用户 · 03 核心痛点 · 04 价值主张 |
| **产品矩阵** | 每个项目按「痛点 → 方案」结构介绍 |
| **技术资产** | 把痛点跑通所依赖的能力栈 |
| **路线图 + 联系** | V2.0 / V1.x / NEXT 迭代计划 |

## 📦 产品矩阵

| # | 项目 | 技术栈 | 体验 |
|---|------|--------|------|
| P01 | [情绪陪伴助手](https://github.com/qushengxixiaoluo/Emotion_Companion_Assistant) | Flutter · OpenAI API | [在线 Demo](https://qushengxixiaoluo.github.io/Emotion_Companion_Assistant/) |
| P02 | [诗语 · 古诗词赏析](https://github.com/qushengxixiaoluo/Appreciation_of_Ancient_Chinese_Poetry) | Flutter · 离线优先 | [在线 Demo](https://qushengxixiaoluo.github.io/Appreciation_of_Ancient_Chinese_Poetry/) |
| P03 | [校园集市 Demo](https://github.com/qushengxixiaoluo/Campus_Market_Demo) | Vue · JavaScript | [源代码](https://github.com/qushengxixiaoluo/Campus_Market_Demo) |
| P04 | [手势粒子特效](https://github.com/qushengxixiaoluo/Particle_Effect_Display) | Three.js · MediaPipe | [在线 Demo](https://is-cau.github.io/Particle_Effect_Display/) |
| P05 | [拾光手册 · AI 照片日记](https://github.com/qushengxixiaoluo/lifesnap) | Flutter · Anthropic / OpenAI API | [源代码](https://github.com/qushengxixiaoluo/lifesnap) |
| P06 | [智能日程 · 事件日历](https://github.com/qushengxixiaoluo/event_calendar) | Flutter · 本地优先 · AI | [源代码](https://github.com/qushengxixiaoluo/event_calendar) |

## 🛠 技术实现

- **单文件静态站点**：仅 `index.html`，无构建步骤、无依赖
- **滚动揭示**：`IntersectionObserver` 驱动的分段入场动画，附带无 JS / 无 IO 时的降级
- **字体**：Anton（展示）· ZCOOL 庆科黄油体（中文标题）· Noto Sans SC（正文）· Spline Sans Mono（标签）
- **响应式**：桌面双栏 → 移动端单栏，适配 `prefers-reduced-motion`

## 🚀 本地预览

直接用浏览器打开 `index.html` 即可，或起一个本地服务器：

```bash
python -m http.server 8000
# 访问 http://localhost:8000
```

## 📦 部署

推送 `main` 分支即自动触发 [GitHub Pages](https://pages.github.com/) 部署：

```bash
git add index.html
git commit -m "feat: 更新主页"
git push origin main
```

约 1–2 分钟后生效。

---

© 2026 [qushengxixiaoluo](https://github.com/qushengxixiaoluo) · 使用 [GitHub Pages](https://pages.github.com/) 部署 · 由 [Claude Code](https://claude.com/claude-code) 打造
