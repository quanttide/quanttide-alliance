# 更新日志

本文档记录项目所有重要变更。格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

## [Unreleased]

### 移除

- 实训基地管理职能移出联盟第二大脑：四个子仓的 `qtacademy/` 全部内容按资产类型移交 `defaults/quanttide-academy` 对应仓的 `default/`，联盟侧不再保留副本。README 定位补一句边界——实训基地管理归 `defaults/quanttide-academy`。

### 新增

- `docs/bylaw` 子模块更新：迁入《量潮招聘考核课题立项评审章程》（`qtrecurit/proposal.md`），自量潮人力资源章程仓迁入，与招聘审计章程同区；招聘事务归联盟主体
- 初始化仓库。
- 新增宣传册子模块 `data/brochure`（`quanttide-brochure-of-innovation-alliance`）：联盟主体的对外宣传与介绍材料。
- 新增日志子模块 `data/journal`（`quanttide-journal-of-innovation-alliance`）：联盟主体的工作日志。
- 新增档案子模块 `data/profile`（`quanttide-profile-of-innovation-alliance`）：联盟主体的稳定档案。
- 新增招聘应用子模块 `apps/qtrecurit`（`qtrecurit`）：联盟招聘相关产品应用。

### 变更

- 仓库更名为 `quanttide-alliance`（原 `quanttide-innovation-alliance`），GitHub 地址与档案库路径同步更新。
- `data/context` 与 `data/brochure` 子模块更新：语境草稿《选拔方式》移入宣传册 `qtrecurit/index.md`，源文件按移动纪律删除。
- `data/brochure` 子模块更新：《选拔方式》补充创始人渠道与首个练手项目《滁州夜市 · 串串摊》。
- `data/brochure` 子模块更新：新增《为什么这样选拔》（`qtrecurit/why.md`）。
- `data/brochure` 子模块更新：新增《选拔方式是什么》（`qtrecurit/what.md`）。
- `data/brochure` 子模块更新：新增《怎么加入公司》（`qtrecurit/how.md`），共同流程与考核标准移出《选拔方式是什么》。
- `data/brochure` 子模块更新：《选拔方式》收敛为入口页，正文拆分到 why / what / how。
- `data/brochure` 子模块更新：《选拔方式是什么》新增渠道选择建议。
- `data/brochure` 子模块更新：《选拔方式是什么》重写概述。
- `data/brochure` 子模块更新：新增《在哪里进行》（`qtrecurit/where.md`）。
- `data/brochure` 子模块更新：新增《什么时候进行》（`qtrecurit/when.md`）。
- `data/brochure` 子模块更新：新增《谁在参与》（`qtrecurit/who.md`）。
- `data/brochure` 子模块更新：《选拔方式》重写绪论。
- `data/context` 子模块更新：`qtacademy/journal/` 与 `qtrecurit/journal/` 的 5 篇日志移入 `data/journal`，按域与月份分二级目录。
- `data/journal` 子模块更新：追加实训基地 2026-10-21 日志（组织构建的选人、留人与流程）。
- `data/journal` 子模块更新：2026-10-21 日志补入选人方案的具体执行口径（问卷信息、证据收集、评价与筛选/通过标准）。
- `data/profile` 子模块更新：《组织》选人流程补充可执行口径（问卷信息、证据收集、评价顺序、筛选评分与通过标准）。
- `data/brochure` 子模块更新：新增《SVIP 特权》（`qtacademy/svip.md`），自语境 `qtacademy/bylaw/svip.md` 迁入；暂不具备制定章程的条件，先作为宣传材料整理。
- `data/context` 子模块更新：`qtacademy/bylaw/svip.md` 移入宣传册，源文件按移动纪律删除。
- `data/context` 子模块更新：新增《量潮模拟经营游戏任务书》（`qtacademy/intention/qtgame-tycoon.md`）。

- 新增 docs/handbook、docs/essay 子模块：迁入 qtrecurit 手册与随笔（自量潮科技）
- 招聘口径统一：qtrecurit 手册与随笔按托管口径改写（docs/handbook、docs/essay 子模块更新）；brochure TODO 招募主体口径项关闭（data/brochure 子模块更新）
- data/brochure 子模块更新：迁入 qtrecurit 招聘宣传三篇（自量潮科技宣传册）
- 新增 data/insight、data/history 子模块：迁入 qtrecurit 招聘洞察九篇与历史文章三篇（自量潮科技）
- data/history 子模块更新：修正 qtrecurit 历史目录拼写（accessment → assessment）
- data/journal 子模块更新：迁入 qtrecurit 日志 20 篇（2026-06~08，自量潮科技归档仓）
- 新增 data/archive 子模块：平移 qtrecurit 归档（profile/intention/context，自量潮科技工作归档）
- 新增 data/roadmap、data/report、docs/bylaw 子模块：qtrecurit 招聘路线图、招聘报告（含生成技能）、招聘审计章程迁入（自量潮科技）
- data/profile 子模块更新：迁入 qtrecurit 招聘政策档案（自 qtadmin CLI 数据目录，已脱敏）
- data/profile 子模块更新：新增 strategy/open-vs-close.md（开源与闭源战略）
- data/profile 子模块更新：新增 strategy/acquisition.md（获客战略）
