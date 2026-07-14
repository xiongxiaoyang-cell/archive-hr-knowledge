# archive-index.md · 公开档案仓索引 V1.0

> **索引生成时点**：2026-07-05 11:59 CST
> **派工溯源**：派工 #377 v3.5+ · V1.0 初始化（3 文件）
> **author**：knowledge-agent（公开化归档）
> **索引格式**：1 文件 1 行 + md5 + 字节 + 行数 + 入库时间 + 原派工溯源

---

## 文件索引（按文件名排序）

| # | 文件名 | 字节 | 行数 | md5 | 公开化日期 | 原派工 |
|---|--------|------|------|-----|----------|--------|
| 1 | `05_行业案例-竞品对标-人力窝-2026官网调研报告-V1.0-20260705.md` | 18971 | 313 | `b89f519fa00120ce5eec9bdb744aa7c7` | 2026-07-05 | 派工 #376 v3.5+ 选修法 c (5 渠道调研) |
| 2 | `05_行业案例-竞品对标-人力窝vs用友薪福社-出海EOR对比分析-V1.0-20260705.md` | 25834 | 292 | `540830b0005d98430ec019a09d7a874e` | 2026-07-05 | 派工 #375 v3.5+ business agent (5 维对比) |
| 3 | `05_行业案例-竞品对标-人力窝WowooHR-出海服务方案-2024.md` | 27414 | 536 | `f90c88d4b4c0b353dbb3ab273979944b` | 2026-07-05 | 派工 #374 v3.5+ 选修法 a (v1.0 入库) |

---

## 索引同步规则

- **新增文件时**：
  1. 复制源文件 + 公开化 annotation block（每文件头部必须）
  2. 计算 md5 + 字节 + 行数
  3. 在本 `archive-index.md` 表格追加一行
  4. 重新 commit（author=knowledge-agent via `-c user.name/email=` override）
- **修改文件时**：
  1. 重算 md5（如内容变化）
  2. 在本索引对应行更新 md5 / 字节 / 行数
  3. commit message 写明派工编号 + 变更原因

---

## 三仓索引联动

| 仓 | 索引位置 | 数据分类 |
|---|---|---|
| lobster-mirror | `lobster-mirror/.last-sync.json` (派生) | P0 内部私有 |
| karpathy-llm-wiki | `wiki/summaries/` + 知识库检索 | P1 KB |
| **archive-hr-knowledge** (本仓) | `archive-index.md` (本文件) | P1 公开 |

---

## 隐私保护级别

- **P1 永久 · 公开档案**: 上述 3 文件 · 公开警示已保留
- **未公开化处理**: lobster-mirror / 部分 karpathy-llm-wiki raw 文件未迁入本仓
- **不公开化处理**: 内部飞书消息 / sessions 记录 / .gitconfig 等永不公开

---

**维护方**: knowledge-agent（OpenClaw workspace agent）
**派工通道**: 通过 main session 派工（`agent:knowledge:main`）
