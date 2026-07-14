# archive-hr-knowledge · 出海 HR 公开档案仓

> **存档类型**：P1 永久 · 公开档案（Public Archive）
> **仓语言**：中文（简体）
> **当前版本**：V1.0 · 2026-07-05

---

## 仓宗旨

本仓库存放**已脱敏 / 已公开化的出海 HR 行业档案**，作为知识库（lobster 私有 + karpathy-llm-wiki 内部 KB）之外的**第三仓**——**对外可分享的公开档案仓**。

### 三仓分工

| 仓 | 数据分类 | 访问范围 | 用途 |
|---|---|---|---|
| **lobster-mirror** | 内部私有 (P0) | 团队内部 | 高敏 / 内部数据 |
| **karpathy-llm-wiki** | 内部 KB (P1) | 团队 + 客户(限域) | 知识库 / 检索 |
| **archive-hr-knowledge** | 公开档案 (P1 · public) | 公开 | 对外分享 / 行业公开 |

---

## V1.0 内容范围（init commit）

派工 #377 v3.5+ · 2026-07-05 11:55 CST 初始化，本次仅入库 3 个公开化文件，全部围绕**人力窝 WowooHR 出海 EOR 对标**主线：

1. **05_行业案例-竞品对标-人力窝WowooHR-出海服务方案-2024.md** — 竞品原文 + 4 警示红线（来自派工 #374）
2. **05_行业案例-竞品对标-人力窝vs用友薪福社-出海EOR对比分析-V1.0-20260705.md** — 业务对标报告（含商业敏感数据警示）
3. **05_行业案例-竞品对标-人力窝-2026官网调研报告-V1.0-20260705.md** — 2026 官网调研 + 5 渠道汇总

详见 [archive-index.md](archive-index.md)（1 文件 1 行 + md5 + 字节 + 行数）。

---

## 公开警示规范

本仓所有文件**头部必有公开化 annotation block**（YAML frontmatter + Markdown 提示段），包含：

- `public_archive_title` —— 公开化标题
- `public_archive_note` —— 公开化动机 / 原派工 / 原作者 / 公开化日期
- `vintage` —— 资料原始 vintage（如 2024-03 PPT）
- `data_classification_was` —— 公开化前分类
- `public_classification_now` —— 公开化后分类（必含 "公开档案"）
- **公开警示**（继承自上游派工的硬性约束，必保留）：
  - 数字非对标口径
  - 排名自称 vs 第三方排行
  - 客户案例未经官方背书
  - 数据未列明细
  - 内部敏感数据公开化警示（如 #375 原文 "非对外发布" 标识）

---

## 文件命名规范（派工 §1.142 7 次踩坑规避）

**严禁子目录嵌套**，全部采用**平铺命名** +「主题子串」：

```
{分类}-{子分类}-{主题}-{可选版本}-{日期}.md
```

例：
- ✅ `05_行业案例-竞品对标-人力窝WowooHR-出海服务方案-2024.md`
- ❌ `05_行业案例/竞品对标/人力窝WowooHR-出海服务方案-2024.md`

---

## commit 规范

- **author 强制**: knowledge-agent（派工 §1.111 P1 永久 author 强制）
- **commit message 格式**: `派工 #NNN v3.5+ · <简述>` + 多段说明
- **首次 commit**: 派工 #377 v3.5+ · V1.0 初始化（3 文件）

---

## 待 Hub 拍板 / V1.x 候选

派工 #377 V1.5+ 候选（待 David / 锴哥拍板）：
- **是否纳入更多 05_行业案例域档案**（如真迈联影/名创优品 / 奇瑞等已公开 PDF）
- **是否扩展到其他 lobsters 域**（01 战略 / 03 区域政策）
- **是否搭建 GitHub Pages**（自动从 archive-index.md 生成静态网页）
- **是否启用 GitHub Discussion**（社区反馈渠道）

---

## 反馈渠道

- 联系作者: knowledge-agent（OpenClaw workspace agent）
- 反馈派工通道: 通过 main 派工 / sessions_send 至 `agent:knowledge:main`

---

**License**: CC BY-NC-SA 4.0（待 Hub 拍板，本 README 为占位）
**Owner**: xiongxiaoyang-cell / archive-hr-knowledge（待 Hub 拍板）
