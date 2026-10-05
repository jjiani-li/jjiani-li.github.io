# 作品集网站

李嘉妮的个人作品集：**单页静态站，零依赖、零构建**，双击 `index.html` 即可本地预览。

**在线地址** → https://jjiani-li.github.io/

## 内容

| 区块 | 内容 |
| --- | --- |
| 首屏 | 一句话定位 + 证件照 + 邮箱 / GitHub / 所在地 |
| 项目一 · 回家照相馆 | 三张跨年代场景演示图、84 次提交 / 626 个测试用例等可验证数字、工程细节、仓库链接 |
| 项目二 · 沃太家庭能源管家 Butler | 原型真实界面截图 ×4、PRD 规模数字、三条设计约束、**站内可直接打开可交互原型**、仓库链接 |
| 项目三 · AI 视觉质检 | 跨工序溯源图、两个自研 Agent Skill 的产出数字、能力边界说明、仓库链接 |
| 关于我 | 制造业背景 + 客户侧经历 + 为什么转做 AI 应用 |

三个项目的仓库链接指向：

- https://github.com/jjiani-li/huijia-photostudio
- https://github.com/jjiani-li/home-energy-butler-prd
- https://github.com/jjiani-li/vision-qc-agent-skills

## 结构

```
.
├── index.html                    # 整站（内联 CSS，无外部依赖）
├── assets/                       # 图片素材（已压缩，合计约 930 KB）
└── demo/butler-prototype.html    # 可交互原型（2,874 行单文件，站内直接体验）
```

## 本地预览

直接双击 `index.html`。页面不含任何外部请求（字体走系统字体栈），离线可看。

## 部署

纯静态页面，不需要构建配置：

- **GitHub Pages**：当前即用此方式（仓库 `main` 分支根目录）
- **Vercel / Netlify**：导入本仓库，Framework Preset 选 `Other`，Build Command 留空，Output Directory 填 `.`

## 说明

页面上标注为「集训营课题」的项目出自沃太能源「AI 黑客松」集训营（2026 年 9 月 · 六天四夜 · 结业证书），为个人练习作品，不代表任何公司的立场或正式产品。相关数据为模拟数据或示例假设。
