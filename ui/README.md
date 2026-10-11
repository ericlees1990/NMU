# NEW MATERIALS UNION / 新材联 · UI Design Component Kit

**Version:** 1.0.0 · 2026-10-11  
**Brand lock:** **方案 A（Scheme A）唯一定稿** — 与 VI 包同一套 Mark / Lockup  
**定位:** AI-powered Building Industries · 蓝图 / 钢铁清晰度

---

## 中文说明

### 这是什么
面向产品与设计协作的 **UI 组件规范包**：设计令牌、可交互样式指南、可选组件截图。视觉语言与品牌 VI 方案 A 对齐——高对比黑白、扁平 + 1px 边框、工业克制；**不是**通用 Material 皮肤。

### 快速开始
1. 用浏览器打开主文件：  
   **[`NMU_UI_Kit.html`](NMU_UI_Kit.html)**  
   （仓库路径 `ui/NMU_UI_Kit.html`）
2. 右上角切换 **浅色 / 深色**；左侧目录跳转各章节。
3. 工程接入令牌：
   - CSS：`tokens/tokens.css`（`@import` 或复制变量）
   - JSON：`tokens/tokens.json`（Style Dictionary / Figma Tokens）

### 品牌硬性规则
| 规则 | 说明 |
|------|------|
| Logo | 仅用本包 `assets/` 中的方案 A 锁与 Mark；禁止改几何 |
| 填色 | Logo **仅黑 / 白** |
| Navy `#1E3A5F` | **仅辅色**：链接、焦点环、选中态；**禁止**作 Logo 填充 |
| 字体 | EN Montserrat / Inter；ZH Noto Sans SC / 系统 UI |
| 层级 | 优先扁平与 1px 边框；圆角 0–4px；避免大阴影 |

### 目录结构
```
ui/
├── README.md                 ← 本说明（中英）
├── NMU_UI_Kit.html           ← 交互式样式指南（主入口）
├── NMU_UI_Kit.pdf            ← 可打印导出
├── tokens/
│   ├── tokens.css            ← CSS 变量
│   └── tokens.json           ← 设计令牌源
├── assets/                   ← Scheme A Logo / Avatar（UI 引用副本）
└── components/               ← 关键组件 PNG（浅/深，交接用）
```

### 组件覆盖
按钮（主/次/幽灵/危险）、图标按钮、Input / Textarea / Select、Checkbox / Radio / Switch、Tabs / Segmented、Card / List / Table、Nav（浅/深）+ Scheme A Mark、Sidebar / Breadcrumb、Badge / Tag / Chip、Toast / Banner / Modal、Empty / Spinner / Avatar。

### 与 VI 包关系
Logo 主文件仍以本仓库品牌 VI 为准（[`manual/`](../manual/NMU_Brand_Guidelines_v1.html)、[`png/`](../png)、[`svg/`](../svg)）。本 UI Kit 引用其锁定稿，并规定界面语义色与控件态。`ui/assets/` 仅为界面引用副本，不替代 VI 原件。

---

## English

Self-contained **UI component kit** locked to Brand VI **Scheme A**. Open [`NMU_UI_Kit.html`](NMU_UI_Kit.html) in a browser. Import `tokens/tokens.css` or `tokens/tokens.json` into your design system. Master logo artwork stays in [`../png`](../png) and [`../svg`](../svg).

**Hard rules:** Scheme A geometry only; logo fills black/white only; Blueprint Navy `#1E3A5F` is accent-only (links, focus, selection)—never logo fill; industrial, high-contrast, flat + 1px borders.

| Token | Hex | Role |
|-------|-----|------|
| Black | `#000000` | Primary / logo |
| White | `#FFFFFF` | Primary / logo |
| Blueprint Navy | `#1E3A5F` | Accent only |
| Steel | `#8A9199` | Secondary text |
| Surface | `#F5F6F7` / `#E8EAED` | Light surfaces |

© NEW MATERIALS UNION · Internal & partner use
