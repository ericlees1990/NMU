# NEW MATERIALS UNION · 新材联  
Brand VI Deliverables / 品牌视觉识别交付包

**Version:** 1.0 · 2026-10  
**Logo status:** Scheme A locked — the only official mark（图标结构禁止修改）

---

## 中文说明

### 这是什么
本目录为新材联（NEW MATERIALS UNION）可交付品牌 VI 包：手册、矢量/位图 Logo、应用示意与命名规范。公司定位由建材旧改转向 **AI 赋能建筑产业**；视觉以黑白为主，辅色仅一枚克制的 Blueprint Navy。

### 从哪里看手册
- **主入口（推荐）：** [`manual/NMU_Brand_Guidelines_v1.html`](manual/NMU_Brand_Guidelines_v1.html)  
  浏览器打开即可阅读；打印时选择 A4、背景图形开启。
- **PDF：** [`manual/NMU_Brand_Guidelines_v1.pdf`](manual/NMU_Brand_Guidelines_v1.pdf)

### 如何使用 Logo
| 场景 | 使用文件 |
|------|----------|
| 印刷严格对齐 / 对外定稿 | `png/NMU_Lockup_H_Master_Light.png` 或 `…_Dark.png`（锁定稿母版） |
| 需要矢量缩放 | `svg/NMU_Mark_*.svg`、`svg/NMU_Lockup_H_*.svg` |
| 微信头像 / App 图标 | `png/NMU_Avatar_Black_512.png` 或 `_1080.png`（仅图标） |
| 深色底 | 白标版本（White / White_on_Black） |
| 浅色底 | 黑标版本（Black / Black_on_White） |

**硬性规则**
1. 不得改图标几何、间隙与笔画比例。  
2. 英文锁必须两行：`NEW MATERIALS` / `UNION`（无斜杠）。  
3. Logo 填色仅限黑或白；辅色 `#1E3A5F` 只用于点缀，不替换 Logo。  
4. 保持安全区（约 1× 主笔画宽）；勿旋转、拉伸、描边、投影。

### 目录结构
```
./
├── README.md                 ← 本说明
├── docs/                     ← 方案 A 定稿说明（唯一正式方案）
├── manual/                   ← 品牌手册 HTML / PDF
├── svg/                      ← 图标与横排锁矢量
├── png/                      ← PNG/JPG 导出（含 Master 锁定稿）
└── assets/                   ← 名片、信纸、PPT、门头、海报等示意
```

### 方案 A（唯一正式方案）
本仓库只收录 **方案 A**。白底黑标 / 黑底白标的横排锁，以及单独使用的图标，都是**同一枚标志**的用法变体，不是两套方案。

[`docs/NMU_Brand_VI_Brief.md`](docs/NMU_Brand_VI_Brief.md) 是方案 A 定稿说明，并取代旧的 Codex 并行对比简报。不要另做第二套 Logo / VI。手册与 Logo 文件是已锁定的 v1。

### 需人工矢量精修的部分
见文末英文节 “Needs human vector polish”。

---

## English

### What this is
A complete, deliverable brand identity pack for **NEW MATERIALS UNION** (新材联): guidelines, SVG/PNG logo set, application mockups, and file naming. The company is pivoting from building-materials renovation to **AI-powered building industries**. Palette is black/white-first with one restrained accent (Blueprint Navy `#1E3A5F`).

### Manual entry point
- **Primary:** [`manual/NMU_Brand_Guidelines_v1.html`](manual/NMU_Brand_Guidelines_v1.html)  
- **PDF:** [`manual/NMU_Brand_Guidelines_v1.pdf`](manual/NMU_Brand_Guidelines_v1.pdf)

### Logo usage
- Prefer **Master** lockup PNGs/JPGs for print-critical work (pixel-locked artwork).  
- Use **SVG** for scalable digital UI; ensure Montserrat (EN) / Noto Sans SC (ZH) are available, or outline type before handoff.  
- Avatars use the **mark only**, centered on black or white, with ≥18% padding.

### Colour
| Token | Hex | Role |
|-------|-----|------|
| Black | `#000000` | Primary |
| White | `#FFFFFF` | Primary |
| Blueprint | `#1E3A5F` | Accent only |
| Steel | `#8A9199` | Neutral |

### Needs human vector polish
Automated SVG reconstruction of the mark reaches **~99% IoU** vs the locked raster, but a designer should still:

1. **Re-trace the mark in Illustrator/Figma** from `png/NMU_Lockup_H_Master_*.png` (or source locks) using perfect 45°/orthogonal constraints and uniform stroke logic — snap terminals and gap widths exactly.  
2. **Convert wordmark to outlines** in the SVG lockups (current SVGs use live text + font fallback; spacing may differ slightly from the locked raster).  
3. **Optional CN lockup** (`NMU_Lockup_H_CN_Black.svg`) is a provisional layout — confirm Chinese type choice and tracking with brand owner.  
4. **Export final PDF/X or outlined AI/EPS** for print vendors after the above polish.  
5. Application mockups in `assets/` are **indicative**, not die-line ready.

### Scheme A is the only official system
This repository documents **Scheme A only**. The black and white horizontal lockups, and the mark used on its own, are usage variants of the **same mark**, not two schemes.

[`docs/NMU_Brand_VI_Brief.md`](docs/NMU_Brand_VI_Brief.md) is the Scheme A lock note. It supersedes the earlier Codex brief that asked for a parallel comparison VI. Do not produce a second logo or VI. The manual and logo files are the locked v1.

---

© NEW MATERIALS UNION · Internal & partner use
