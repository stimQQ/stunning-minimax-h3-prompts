# MiniMax H3 提示词库

[![浏览](https://img.shields.io/badge/浏览-135%20条提示词%20+%20视频-F5FF60)](https://apimodels.app/minimax-h3-prompts)
[![API](https://img.shields.io/badge/一个%20API-85%2B%20模型-blue)](https://apimodels.app/models)

**MiniMax H3**（社区称海螺 3.0）的可用提示词库。H3 是 MiniMax 于 2026 年 7 月 31 日
发布的多模态视频模型：2K、24fps、4–15 秒，自带同步原生音效，单次最多可喂 9 张参考图、
3 段参考视频、3 段参考音频。

**每条提示词都配了能直接看的成片。** 提示词与效果并排浏览：

### → **[apimodels.app/minimax-h3-prompts](https://apimodels.app/minimax-h3-prompts)**

---

## 仓库内容

| | 数量 | 位置 |
|---|---|---|
| **反推提示词**（我们撰写，全文，MIT） | 72 | [`prompts/`](./prompts) |
| **社区提示词**（作者撰写，仅索引） | 63 | [`COMMUNITY-INDEX.md`](./COMMUNITY-INDEX.md) |

**`prompts/` 是我们自己写的。** 对于作者没有公开提示词的片子，我们抽帧交给视觉模型，
反推出最可能复现该效果的提示词。这些归我们所有，MIT 授权，随便用。但它是**写法参考，
不是原作者的提示词**——反推描述的是成片，拿不到负向约束、精确台词和参考图工作流。
每个文件开头都写明了这一点。

**`COMMUNITY-INDEX.md` 是作者写的。** 我们只做索引：标题、作者、长度、原帖链接、
以及我们画廊里的对应条目。**全文没有搬进仓库**——这些提示词不属于我们，无法替作者授权。
作者若希望移除索引条目，提 issue 即可。

---

## 在哪里跑这些提示词

H3 目前走 MiniMax 官方 API 与海螺产品，约 **$0.13/秒起**，**尚未在 apimodels.app 上线**
——我们不上架没跑通的模型。一旦在我们这边稳定可用，会第一时间上架并更新本仓库。

下面这些图像与视频模型**已经**在我们的统一 API 上：一个 key、一个端点、按量计费、
注册送 $1。

### 图像模型

| 模型 | 页面 |
|---|---|
| **GPT Image 2** | [gpt-image-2](https://apimodels.app/models/gpt-image-2) |
| GPT Image 2 全档位 | [gpt-image-2-all](https://apimodels.app/models/gpt-image-2-all) |
| **Nano Banana 2** | [nanobanana2](https://apimodels.app/models/nanobanana2) |
| Nano Banana 2 Lite | [nanobanana-2-lite](https://apimodels.app/models/nanobanana-2-lite) |
| **Nano Banana Pro** | [nanobananapro](https://apimodels.app/models/nanobananapro) |
| Nano Banana Pro Lite | [nanobananapro-lite](https://apimodels.app/models/nanobananapro-lite) |
| Gemini 3 Pro Image | [gemini-3-pro-image](https://apimodels.app/models/gemini-3-pro-image) |
| Gemini 3.1 Flash Image | [gemini-3.1-flash-image](https://apimodels.app/models/gemini-3.1-flash-image) |

**[957 条 GPT Image 2 提示词 →](https://apimodels.app/gpt-image-2-prompts)** ——
另一个提示词库，同样每条都配了实际出图。

### 视频模型

| 模型 | 页面 |
|---|---|
| **Seedance 2.0** | [seedance-2.0](https://apimodels.app/models/seedance-2.0) |
| **Kling V3** | [kling-v3](https://apimodels.app/models/kling-v3) |
| **VEO 3.1** | [veo-3.1](https://apimodels.app/models/veo-3.1) |

完整模型列表：**[apimodels.app/models](https://apimodels.app/models)** ·
API 文档：**[apimodels.app/docs](https://apimodels.app/docs)** ·
代码示例：**[apimodels-api-demo](https://github.com/stimQQ/apimodels-api-demo)**

---

## 怎么写好 H3 提示词

读完库里全部 135 条总结出来的。和写图片提示词最大的差别是：你要同时交代**时间**、
**镜头**和**声音**。

1. **一条提示词只讲一个动作。** 4–15 秒装不下三段剧情。
2. **把镜头运动写明白。** 推、拉、摇、跟、手持轻晃、无人机俯冲；不写就是静止机位。
3. **写声音。** H3 会生成同步原生音效——环境音、动作音，甚至一句台词。
4. **先定光和色。** 一句配色/打光决定整条片子的质感。
5. **给出速度与节奏。** 慢动作、实时、延时，以及动作发生在第几秒。
6. **参考图管身份，提示词管动作。** 最多 9 张参考图锁住长相、服装、产品外观。
7. **拆成带时间码的分镜。** 库里最强的那些都写成 `0-4s — …` 的镜头表，最长一条 6602 字符。
8. **写清楚不要什么。** 高质量提示词几乎都以负向约束收尾。

---

## 参与

发现好的 H3 提示词和成片？提 issue 附上帖子链接。作者公开了提示词我们就索引，
没公开的可以反推并标注来源。

## 许可

[MIT](./LICENSE) —— 覆盖 `prompts/` 里的反推提示词和我们撰写的全部内容。
**不覆盖** `COMMUNITY-INDEX.md` 索引的社区提示词，那些归其作者所有，我们只链接、不复制。
