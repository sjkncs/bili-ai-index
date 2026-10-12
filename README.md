# B 站 AI 学习资源总索引（按内容类型分目录）

> Snapshot: **2026-10-12** - **659** episodes, one directory per content type.

- VALSE_Webinar, deep_thoughts, 读论文的麦小哲, 秋刀鱼的炼丹工坊, 同济子豪兄, 先进编译实验室, OpenMMLab
- ShusenWang, 霹雳吧啦Wz, 刘二大人, 王木头学科学, Bubbliiiing, 啥都会一点的研究生
- 张小珺商业访谈录, 五里墩茶社, 林粒粒呀
- HyperHorizon
- 机器之心

## Contents

| directory | type | source | episodes | full title | arXiv | speaker |
|---|---|---|---:|---:|---:|---:|
| [`01-paper-reading/`](01-paper-reading/) | AI 论文精读 | VALSE_Webinar, deep_thoughts, 读论文的麦小哲, 秋刀鱼的炼丹工坊, 同济子豪兄, 先进编译实验室, OpenMMLab | 60 | 0 | 5 | 0 |
| [`02-course/`](02-course/) | AI 课程与教程 | ShusenWang, 霹雳吧啦Wz, 刘二大人, 王木头学科学, Bubbliiiing, 啥都会一点的研究生 | 0 | 0 | 0 | 0 |
| [`03-interview/`](03-interview/) | 访谈与行业观察 | 张小珺商业访谈录, 五里墩茶社, 林粒粒呀 | 0 | 0 | 0 | 0 |
| [`04-world-model/`](04-world-model/) | 世界模型论文解读 | HyperHorizon | 83 | 83 | 74 | 0 |
| [`05-wam-vla/`](05-wam-vla/) | WAM 与 VLA 论文解读 | HyperHorizon | 66 | 66 | 57 | 0 |
| [`06-video-generation/`](06-video-generation/) | 视频生成论文解读 | HyperHorizon | 32 | 31 | 29 | 0 |
| [`07-hh-weekly/`](07-hh-weekly/) | 每周论文总结 | HyperHorizon | 1 | 0 | 0 | 0 |
| [`08-conferences/`](08-conferences/) | 机器之心 · 顶会论文分享 | 机器之心 | 96 | 0 | 3 | 53 |
| [`09-mqzx-interviews/`](09-mqzx-interviews/) | 机器之心 · 访谈与论坛 | 机器之心 | 50 | 0 | 0 | 12 |
| [`10-opensource-hands-on/`](10-opensource-hands-on/) | 开源生态与 AIGC 实战 | 机器之心 | 42 | 0 | 2 | 26 |
| [`11-3dv-paper-notes/`](11-3dv-paper-notes/) | 3D 视觉论文解读 | HyperHorizon | 229 | 229 | 209 | 0 |
| | | **total** | **659** | | | |

## Data source / method / limits

**Data source**: `seasons_archives_list` for episode lists; `x/web-interface/view`
per video for the **`desc`** field. Every request goes through a backoff wrapper because
the anonymous API answers risk-control code `-352` under load.

**Method**: directory assignment uses an **explicit map of exact collection names** -- a
fuzzy match silently dropped one whole conference series once (48 instead of 96 items).
Parsing then depends on the source's description shape (paper template / guest-intro block /
title-only).

**Limits**
- Metadata index only: no videos, no subtitles, no slides.
- Bilibili caps video **titles** at 80 chars. Where a source writes full paper names in the
  description, `full_title` is complete while `bvid_title` may be truncated.
- Sources without a description template expose fewer fields; those stay empty and are
  **not guessed**.
- Data was collected with backoff and is a snapshot, not a live view.

---
*2026-10-12 snapshot. All content belongs to the original authors.*