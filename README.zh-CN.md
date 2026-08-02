# Stunning MiniMax H3 Prompts

[![画廊](https://img.shields.io/badge/140%20条提示词%20·%20带视频-F5FF60?labelColor=111)](https://apimodels.app/zh/minimax-h3-prompts)
[![统一 API](https://img.shields.io/badge/一个%20API-85%2B%20模型-3158E8)](https://apimodels.app/zh/models)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

**MiniMax H3**（海螺 3.0）提示词库。每条提示词都配着它真正生成出来的那段视频，
署名作者，链回原帖。

**[English](./README.md)** · **[看全部 138 条](./prompts/GALLERY.zh-CN.md)** ·
**[到画廊里带声音看](https://apimodels.app/zh/minimax-h3-prompts)**

---

## MiniMax H3 强在哪

2026 年 7 月 31 日发布。原生 **2560×1440 / 24fps**，4–15 秒，**音频和画面同一次生成** ——
环境声、动作音、台词都落在你指定的那一帧上，不是事后配的背景音乐。

**Omni Reference** 一次请求能吃 **9 张参考图 + 3 段参考视频 + 3 段参考音频**。库里有位作者
用 8 张图（6 个角色 + 1 张场景 + 1 张 UI）驱动出一整段看着像真能玩的游戏画面，H3 把每个角色的
身份、界面元素和动作逻辑在整段里都守住了。

它也吃得下超长提示词。库里最长的一条 **6602 字符**：逐秒分镜、屏幕上一字不差的文字、
人体结构锁定、镜头焦段，外加一张精确到帧的音效表。此外还有首尾帧控制、动作迁移、生成式编辑。

---

## 两类提示词，分得很清楚

| | 数量 | 是什么 |
|---|---|---|
| **作者原文** | 66 | 作者自己公开的。署名、链回原帖。全文放在我们的[画廊](https://apimodels.app/zh/minimax-h3-prompts)里，这个仓库只做索引 —— 因为它不归我们所有。 |
| **AI 反推** | 72 | 作者没公开提示词的片子，我们抽 8 帧交给视觉模型，写出最可能复现这段画面的提示词。**MIT，全文就在这个仓库里。** |

反推描述的是**成片**，恢复不了负面约束、准确台词和参考图工作流 —— 它是写法参考，不是作者的原稿，
每一条都标了 `AI 反推`。

作者们：想撤下某一条，开个 issue 就行。

---

## 精选

作者原文里最长的 12 条。**[看全部 138 条 →](./prompts/GALLERY.zh-CN.md)**

### 1. 断刃重铸的无限循环

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m"><img src="https://pbs.twimg.com/amplify_video_thumb/2082772865410338816/img/wQZjhenyhl6nJlWM.jpg" alt="断刃重铸的无限循环" width="700" /></a>

<strong>提示词</strong> — @image1 15s | 16:9 | 1440p | 24fps | SEAMLESS LOOP [LOCK] Render exactly as @image1. Do not alter hair, bangs, eye color, coat silhouette, sash, hilt ornament, or blade proportion. [LOOP] A perfect cy…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m) （6602 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m)

**来源:** [@Cia0_exe](https://x.com/Cia0_exe/status/2082774526098874724) · 15s · 16:9 · 动画与二次元

---
### 2. 蒙娜丽莎游戏选角与换装

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i"><img src="https://pbs.twimg.com/amplify_video_thumb/2083552730233114624/img/zZaVXYLxeHSBXpiF.jpg" alt="蒙娜丽莎游戏选角与换装" width="700" /></a>

<strong>提示词</strong> — Use @Image 1 for the character and the menu interface style. Use @Image 2 for the game world and the in-game HUD style. Use @Image 3 as the source for every item thumbnail shown inside the panels — it…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i) （6301 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i)

**来源:** [@ivanka_humeniuk](https://x.com/ivanka_humeniuk/status/2083555429758464203) · 15s · 16:9 · 特效与转场

---
### 3. 沙漠对峙 · 15 秒一镜到底

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z"><img src="https://pbs.twimg.com/amplify_video_thumb/2082560936645152769/img/1mJ8RYmFcQdGZZbA.jpg" alt="沙漠对峙 · 15 秒一镜到底" width="700" /></a>

<strong>提示词</strong> — SCENE CONTEXT A middle-aged man stands in the middle of a dirt road in open desert and holds a pistol level at the person filming him. He gives an instruction, is answered by name, and warns them not …

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z) （6078 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z)

**来源:** [@maxescu](https://x.com/maxescu/status/2082563241062875568) · 15s · 16:9 · 对白与音效

---
### 4. 魔幻游戏实机演示

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb"><img src="https://pbs.twimg.com/amplify_video_thumb/2083085291691319296/img/zEXiiVypelJy1CeR.jpg" alt="魔幻游戏实机演示" width="700" /></a>

<strong>提示词</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic AAA fantasy MMORPG gameplay reveal with native synchronized game audio and music. [OMNI REFERENCES] [Image1] = Kael Ardyn, the exact playab…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb) （4443 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb)

**来源:** [@PromptSin](https://x.com/PromptSin/status/2083085328710238400) · 15s · 16:9 · 参考图与一致性

---
### 5. 情景喜剧游戏秀选择

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt"><img src="https://pbs.twimg.com/amplify_video_thumb/2083130633048694784/img/6bfTlMdE8iKutjpq.jpg" alt="情景喜剧游戏秀选择" width="700" /></a>

<strong>提示词</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic multi-camera television sitcom with native synchronized dialogue, audience reactions, SFX and music. [OMNI REFERENCES — [Image1] [Image2] […

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt) （4399 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt)

**来源:** [@PromptSin](https://x.com/PromptSin/status/2083130683183255894) · 15s · 16:9 · 人物表演

---
### 6. 神圣升华网页动效

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax"><img src="https://pbs.twimg.com/amplify_video_thumb/2083087808584101888/img/YJQUBTO4YrEgmQRA.jpg" alt="神圣升华网页动效" width="700" /></a>

<strong>提示词</strong> — 15秒 | 16:9 | 1440p | 24fps | 无缝循环 | 网页首屏动画 [人物锁定 · @image1] 完全按照该参考图呈现，不进行任何重新设计。金色卷发、闭合的双眼、仰起的面容与安详神情；象牙色垂坠长袍；左右两枚金色玫瑰花章肩甲，含中心宝石与放射浮雕；金丝胸饰、十字垂饰、多层珠链；水晶巨剑，含金色巴洛克护手与剑柄头、缠绕剑柄，双臂高举过头横持，金色火柱自上贯入；白色大理石圆台；下…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax) （4269 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax)

**来源:** [@Cia0_exe](https://x.com/Cia0_exe/status/2083090068378616089) · 15s · 16:9 · 参考图与一致性

---
### 7. H3能量饮料宣传片

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb478dp000004l15tqgauxd"><img src="https://pbs.twimg.com/amplify_video_thumb/2082912615052050432/img/4kFMxx1VdMeuLzMU.jpg" alt="H3能量饮料宣传片" width="700" /></a>

<strong>提示词</strong> — [FORMAT] 15-second vertical 9:16 photorealistic commercial product showcase with native synchronized stereo audio. [OMNI REFERENCE — [Image1]] [Image1] is the strict multi-angle product reference for …

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb478dp000004l15tqgauxd) （4178 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb478dp000004l15tqgauxd)

**来源:** [@PromptSin](https://x.com/PromptSin/status/2082912639647465647) · 15s · 9:16 · 产品与广告

---
### 8. Q版卡牌对战游戏视频

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t1gj000404jp58a34rrg"><img src="https://pbs.twimg.com/amplify_video_thumb/2083200281681244160/img/HMoAH6bI63vla0DX.jpg" alt="Q版卡牌对战游戏视频" width="700" /></a>

<strong>提示词</strong> — 【图像参考 · 唯一依据】 本镜头使用上传的八张参考图。Image1至Image6为六位角色的唯一角色参考，Image7为场景的唯一参考，Image8为游戏界面的唯一参考。 Image1＝Capychan：水豚毛绒头套，头顶菠萝冠，金发带绿色挑染，左眼翠绿右眼天蓝，亮黄色10号球衣。 Image2＝Lionchan：狮子毛绒头套，头顶白玫瑰，橙色麻花辫带蓝色挑染，左眼蓝宝石右眼红宝石，白色10号球…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t1gj000404jp58a34rrg) （4053 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t1gj000404jp58a34rrg)

**来源:** [@Preda2005](https://x.com/Preda2005/status/2083203349739192726) · 15s · 16:9 · 参考图与一致性

---
### 9. 极冰交互网页首屏动画

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb1gec6000504jojh8a34bi"><img src="https://pbs.twimg.com/amplify_video_thumb/2083178671440023552/img/VMAqXAYVXbVbBr_s.jpg" alt="极冰交互网页首屏动画" width="700" /></a>

<strong>提示词</strong> — 无缝循环 | 网页首屏动画 [核心概念] 她的每一个动作都对应一种网页交互行为，她不是站在网页前，而是在演示这个网页如何运作。加载、悬停、点击、滚动、拖拽、轮播、提交、刷新——八种交互依次发生，每一种都有对应的冰质界面反馈。 [人物锁定 · @image1] 完全按照该参考图呈现，不进行任何重新设计。 容貌：年轻女性，薄荷绿齐颏短发，发丝随动作轻扬；锐利的浅青碧色双眼，青色指甲，水晶坠耳饰。 服装…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb1gec6000504jojh8a34bi) （3509 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb1gec6000504jojh8a34bi)

**来源:** [@Cia0_exe](https://x.com/Cia0_exe/status/2083180088775045626) · 15s · 16:9 · 特效与转场

---
### 10. 恐怖怪物电影片段

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb21nbo00000ajdti5nw0h2"><img src="https://pbs.twimg.com/amplify_video_thumb/2082759082411253760/img/ASy0atW22QDD7S-U.jpg" alt="恐怖怪物电影片段" width="700" /></a>

<strong>提示词</strong> — Four 15-second 6-shot creature-horror sequences. — THE BASEMENT THING — Shot 1 (0–2.5s): Close-up of a man's hand slowly pushing open a wooden basement door. Dim light spills in. He whispers: "Is some…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb21nbo00000ajdti5nw0h2) （3393 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb21nbo00000ajdti5nw0h2)

**来源:** [@Dheepanratnam](https://x.com/Dheepanratnam/status/2082760158296313960) · 15s · 16:9 · 电影感

---
### 11. 赛博废土风女团MV

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t0ab000004jp8hfbfcbj"><img src="https://pbs.twimg.com/media/HOiNPd4bMAAp5fu.jpg" alt="赛博废土风女团MV" width="700" /></a>

<strong>提示词</strong> — 15s K-pop 女团 MV 提示词 主体：三人 K-pop 女团，人物形象与当前角色设定一致。 SOL：黑色长直发，冷静强势，黑色结构短西装、低腰百褶短裙、黑色长靴。 LUNA：银灰色短狼尾，冷感疏离，银灰短款机能夹克、黑色连体内搭、不对称裙裤、厚底靴。 CORONA：深红棕长卷发，带细辫，叛逆锋利，红黑赛车短夹克、低腰裙裤、绑带长靴。 场景：白色无缝影棚被重新处理成地下音乐杂志拍摄现场。背景…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t0ab000004jp8hfbfcbj) （3288 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t0ab000004jp8hfbfcbj)

**来源:** [@liandeli2](https://x.com/liandeli2/status/2083070647660609837) · 15s · 16:9 · 视频编辑

---
### 12. 1998 首尔 Hi8 家庭录像

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsakc7l5000104jw52pg0x2c"><img src="https://pbs.twimg.com/amplify_video_thumb/2082747028283719680/img/2ZOpzhqz3Lu8DZko.jpg" alt="1998 首尔 Hi8 家庭录像" width="700" /></a>

<strong>提示词</strong> — Create an authentic 15-second archival home video that appears to have been recorded in Seoul, South Korea, during the summer of 1998 using a consumer Hi8 or VHS-C camcorder. The camcorder is never vi…

[**读完整提示词 →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsakc7l5000104jw52pg0x2c) （3225 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsakc7l5000104jw52pg0x2c)

**来源:** [@itxabdullaa](https://x.com/itxabdullaa/status/2082747126497300930) · 15s · 16:9 · 电影感

---

---

## 仓库结构

| 路径 | 内容 |
|---|---|
| [`prompts/GALLERY.zh-CN.md`](./prompts/GALLERY.zh-CN.md) | 全部 138 条：缩略图 + 提示词 + 来源，也就是上面精选段的完整版 |
| [`prompts/GALLERY.md`](./prompts/GALLERY.md) | 同一份画廊的英文版 |
| [`prompts/<分类>/`](./prompts) | 72 条 AI 反推提示词的单文件版本，按用途分目录，方便 grep，MIT |

---

## 怎么跑这些提示词

MiniMax H3 目前走 MiniMax 官方 API 和海螺产品，约 **$0.13/秒起**。它**还没有在 apimodels.app 上线** ——
没调通的模型我们不上架。等它能跑了就上，这个仓库同一天更新。

下面这些图像和视频模型**已经**在我们的统一 API 上：一个 key、一个端点、按量付费，注册送 $1。

| 图像 | 视频 |
|---|---|
| [GPT Image 2](https://apimodels.app/zh/models/gpt-image-2) · [全档位](https://apimodels.app/zh/models/gpt-image-2-all) | [Seedance 2.0](https://apimodels.app/zh/models/seedance-2.0) |
| [Nano Banana 2](https://apimodels.app/zh/models/nanobanana2) · [2 Lite](https://apimodels.app/zh/models/nanobanana-2-lite) | [Kling V3](https://apimodels.app/zh/models/kling-v3) |
| [Nano Banana Pro](https://apimodels.app/zh/models/nanobananapro) · [Pro Lite](https://apimodels.app/zh/models/nanobananapro-lite) | [VEO 3.1](https://apimodels.app/zh/models/veo-3.1) |
| [Gemini 3 Pro Image](https://apimodels.app/zh/models/gemini-3-pro-image) · [3.1 Flash Image](https://apimodels.app/zh/models/gemini-3.1-flash-image) | [全部模型 →](https://apimodels.app/zh/models) |

```bash
curl -X POST https://apimodels.app/api/v1/images/generations-sync \
  -H "Authorization: Bearer $APIMODELS_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"gpt-image-2-all","prompt":"a frosted glass serum bottle on wet travertine, soft daylight","aspect_ratio":"4:5","resolution":"1K"}'
```

**[957 条 GPT Image 2 提示词 →](https://apimodels.app/zh/gpt-image-2-prompts)** —— 同一套做法的第二个库。 ·
[API 文档](https://apimodels.app/zh/docs) · [代码示例](https://github.com/stimQQ/apimodels-api-demo)

---

## MiniMax H3 提示词怎么写

下面这几条是把库里每条提示词读完之后总结的。和写图像提示词最大的区别是：你现在要指挥的是
**时间**、**镜头**和**声音**，不只是一张画面。

1. **一条提示词只讲一个动作。** 片长 4–15 秒，一个动作讲清楚，胜过塞三个。
2. **把运镜写出来。** 推、拉、跟、手持轻晃、无人机下降。不写就是一个死机位。
3. **把声音写出来。** H3 生成同步原生音频 —— 环境声、动作音，甚至一句台词，都点名。
4. **先定光和色。** 一句关于光线和色调的话，决定整段片子的观感。
5. **给它节奏。** 慢动作、正常速度、延时；以及那个"重拍"落在第几秒。
6. **参考图管身份，提示词管动作。** 最多 9 张参考图锁住脸、服装或产品；提示词负责说发生了什么。
7. **拆成带时间码的分镜。** 库里最强的那几条读起来就是一张分镜表：`0-4s — …`、`4-8s — …`。
8. **写清楚你不要什么。** 几乎所有高质量提示词的末尾都有负面约束：不要多手多脚、不要屏幕文字、不要镜头抖动。

---

## 参与

看到不错的 H3 片子？开个 issue 贴原帖链接。作者公开了提示词，我们就署名收录；
没公开的，我们可以反推并明确标注。

## 许可

[MIT](./LICENSE) —— 覆盖 AI 反推的提示词和我们自己写的所有内容，
**不覆盖**作者原文提示词：那些归作者本人所有，我们只做链接，不做再授权。
