# AI 课程与教程

> Source: **ShusenWang, 霹雳吧啦Wz, 刘二大人, 王木头学科学, Bubbliiiing, 啥都会一点的研究生** - Snapshot: **2026-10-12** - **0** episodes.
> Data: [`items.json`](items.json)

## Data source / method / limits

**Data source**: `seasons_archives_list` for the episode list; `x/web-interface/view`
per video for its **`desc`** field.

**Method**: this source's titles are already short and complete (no 80-char truncation
observed), so **the title is the record** and no paper/venue/speaker parsing is attempted.
The description is scanned only for links, and links are de-duplicated per episode.

**Limits**: descriptions are shallow and highly repetitive -- the most frequent link
appears on 42 of 106 episodes (an authoritative paper-list repo), another on 29 (a course
homepage) -- so links points at entry points rather than at each individual paper.
**No venue, arXiv id or speaker is available for most entries, and none is invented.**
16 of 106 descriptions are empty entirely.

## All 0 episodes

| # | speaker | affiliation | topic | length | B station |
|---:|---|---|---|---:|---|

## Per entry

