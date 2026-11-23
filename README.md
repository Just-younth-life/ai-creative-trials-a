# AI Creative Trials A

> 10 个 AI 作品，一个作品一个文件。双击 HTML 就能离线打开——不用服务器、不用联网、不用装依赖。

## 产品原型

| 作品 | 是什么 | 关键数据 | 入口 |
| --- | --- | --- | --- |
| **三思集** Sansi | 学生 / 职场人的决策 Agent：两难问题拆成两条路线 + 明确建议 | 251 条决策知识 · 16 个标签 | (https://github.com/Just-younth-life/ai-creative-trials-a/sansi-agent.html) |
| **松间知宁** Songjian Zhining | 居家养老产品双端原型：PC 品牌官网 + H5 适老版「康伴」 | 2 端 · 9 章 PRD | (https://github.com/Just-younth-life/ai-creative-trials-a/songjian-zhining.html) |
| **宽序** Kuanxu | AI 社交日程管理：公开社交版 + 情侣私密版，游戏化人生地图 | 11 章 PRD · 3 层竞品分级 | (https://github.com/Just-younth-life/ai-creative-trials-a/kuanxu.html) |
| **汪独** WONGDU | Star Battle 类休闲解谜，萌宠外壳 + 严肃秘境，从策划到可复现脚本 | 32 关 · 33/33 测试 · 23 条 Bad Case · 15 份文档 |(https://github.com/Just-younth-life/ai-creative-trials-a/)wangdu.html) · [直接试玩 game.html](https://github.com/Just-younth-life/ai-creative-trials-a/game.html) |

## 内容 IP

| 作品 | 是什么 | 关键数据 | 入口 |
| --- | --- | --- | --- |
| **社会学治愈图文** Sciology Healing | 社会学理论做骨架的治愈图文 IP，全链路生产 SOP | 4 个核心命题 · 10 份资产 | [sciology-healing.html](sciology-healing.html) |
| **AI 音乐二创** Music Lyrics | 等长填词工程：逐句字数对标原曲 + 防幻觉执行规范 | 4 首立项 · 2 首成稿 | [music-lyrics.html](music-lyrics.html) |

## 方法沉淀

| 作品 | 是什么 | 关键数据 | 入口 |
| --- | --- | --- | --- |
| **Triple Synth** | 角色分离 × 多 AI 合成：Proposer / Critic / Judge / Synthesis | 4 角色 · 2 份提示词 | [triple-synth.html](triple-synth.html) |
| **Agent 调度框架** | 灰度开关 + 代理工厂的多模型调度框架 | 10 文件 · 3 家厂商 | [agent-framework.html](agent-framework.html) |
| **AI 工作流升级** | WorkBuddy + Trae 的双工具闭环复盘 | 8 节复盘 | [ai-workflow-sop.html](ai-workflow-sop.html) |
| **摇一摇拆解** | 微信摇一摇的产品生命周期完整样本 | 9 章拆解 | [shake-analysis.html](shake-analysis.html) |

## 怎么用

1. 克隆或用 GitHub Pages 打开 `index.html`
2. 也可以直接双击任意 `.html`：样式、库、图片、音视频全部内联，断网可用
3. 只想玩游戏：直接双击 `game.html`（32 关完整 Demo，图片音频全部内联，单独拿走也能跑）
4. 想看源码：进入作品页的「源码 / 后端实现 / 工程脚本」标签，代码以文本形式保留，可直接复制运行

## 结构对照（原仓库 → 现在）

| 原路径 | 现在 |
| --- | --- |
| `project-Ai-assissment-sansiji/` | `sansi-agent.html` |
| `project-sensor-songjianzhining/` + `project-sensor-viewing/` | `songjian-zhining.html`（双端合并） |
| `projrct-kuanxu/` | `kuanxu.html` |
| `汪独作品集`（本次新增） | `wangdu.html` |
| `creative-ip/` | `sciology-healing.html` |
| `music-lyrics/` | `music-lyrics.html` |
| `date-skills/triple-synth/` | `triple-synth.html` |
| `agent/` + `main.py/` + `api_server.py/` | `agent-framework.html` |
| `AI-thinking-time/` | `ai-workflow-sop.html` |
| `project-shake/` | `shake-analysis.html` |
| `index.html`（旧项目选择页） | `index.html`（新作品集首页） |

原先散落的 63 个文件（含非标准连字符、无扩展名的怪文件名）已收成 10 个作品页 + 1 个首页 + 1 份 README；空文件与纯测试桩不入库。

## 约定

- **一个作品一个文件**：演示、文档、源码收在同一页，不散落成十几个文件夹
- **全部离线**：没有 CDN、没有外部字体、没有接口请求，媒体素材压缩后内嵌
- **不改内容**：原始文档与代码原样保留，只做结构收敛与体积优化
