# Stunning MiniMax H3 Prompts

[![Gallery](https://img.shields.io/badge/Browse%20140%20prompts%20with%20video-F5FF60?labelColor=111)](https://apimodels.app/minimax-h3-prompts)
[![One API](https://img.shields.io/badge/One%20API-85%2B%20models-3158E8)](https://apimodels.app/models)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

Curated **MiniMax H3** (Hailuo 3.0) video prompts — every one shown next to the clip it
actually produced, with credit and a link to the creator's original post.

**[中文说明](./README.zh-CN.md)** · **[Browse all 138 prompts](./prompts/GALLERY.md)** ·
**[Watch them with sound](https://apimodels.app/minimax-h3-prompts)**

---

## What MiniMax H3 does

Released 31 July 2026. Native **2560×1440 at 24fps**, 4–15 second clips, with **audio
generated in the same pass** — ambience, foley and dialogue landing on the frame you
specify, not a soundtrack added afterwards.

**Omni Reference** takes up to **9 reference images + 3 video clips + 3 audio clips** in a
single request. One creator in this library drove an entire playable-looking game sequence
from 8 images — 6 characters, 1 arena, 1 UI — and H3 held every identity, the interface and
the action logic coherent across the whole clip.

It also follows very long prompts. The longest in this library is **6,602 characters**: a
per-second shot breakdown, exact on-screen text, anatomy locks, focal lengths and a
frame-accurate audio cue sheet. Plus first/last-frame control, motion transfer and
generative editing.

---

## Two kinds of prompt, kept clearly apart

| | Count | What it is |
|---|---|---|
| **Author-written** | 66 | Published by the creator. Credited, linked to the original post. Full text lives in our [gallery](https://apimodels.app/minimax-h3-prompts) — we index it here rather than copy it, because we do not own it. |
| **Reconstructed** | 72 | For clips whose creator never published a prompt, we sample 8 frames, hand them to a vision model, and write the prompt that would most plausibly reproduce the clip. **MIT, full text in this repo.** |

A reconstruction describes the *output*. It cannot recover negative constraints, exact
dialogue or reference-image workflows — it is a writing reference, not the creator's
prompt, and every one is labelled `reconstructed`.

Creators: if you would like an entry removed, open an issue.

---

## Featured prompts

The twelve longest author-written prompts in the library. **[See all 138 →](./prompts/GALLERY.md)**

### 1. Infinite Cycle of the Blade

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m"><img src="https://pbs.twimg.com/amplify_video_thumb/2082772865410338816/img/wQZjhenyhl6nJlWM.jpg" alt="Infinite Cycle of the Blade" width="700" /></a>

<strong>Prompt</strong> — @image1 15s | 16:9 | 1440p | 24fps | SEAMLESS LOOP [LOCK] Render exactly as @image1. Do not alter hair, bangs, eye color, coat silhouette, sash, hilt ornament, or blade proportion. [LOOP] A perfect cy…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m) (6602 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m)

**Source:** [@Cia0_exe](https://x.com/Cia0_exe/status/2082774526098874724) · 15s · 16:9 · Animation & Anime

---
### 2. Mona Lisa Character Selection Screen

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i"><img src="https://pbs.twimg.com/amplify_video_thumb/2083552730233114624/img/zZaVXYLxeHSBXpiF.jpg" alt="Mona Lisa Character Selection Screen" width="700" /></a>

<strong>Prompt</strong> — Use @Image 1 for the character and the menu interface style. Use @Image 2 for the game world and the in-game HUD style. Use @Image 3 as the source for every item thumbnail shown inside the panels — it…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i) (6301 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i)

**Source:** [@ivanka_humeniuk](https://x.com/ivanka_humeniuk/status/2083555429758464203) · 15s · 16:9 · VFX & Transitions

---
### 3. Desert Standoff — 15s single take

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z"><img src="https://pbs.twimg.com/amplify_video_thumb/2082560936645152769/img/1mJ8RYmFcQdGZZbA.jpg" alt="Desert Standoff — 15s single take" width="700" /></a>

<strong>Prompt</strong> — SCENE CONTEXT A middle-aged man stands in the middle of a dirt road in open desert and holds a pistol level at the person filming him. He gives an instruction, is answered by name, and warns them not …

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z) (6078 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z)

**Source:** [@maxescu](https://x.com/maxescu/status/2082563241062875568) · 15s · 16:9 · Dialogue & Sound

---
### 4. Fantasy MMORPG Gameplay Reveal

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb"><img src="https://pbs.twimg.com/amplify_video_thumb/2083085291691319296/img/zEXiiVypelJy1CeR.jpg" alt="Fantasy MMORPG Gameplay Reveal" width="700" /></a>

<strong>Prompt</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic AAA fantasy MMORPG gameplay reveal with native synchronized game audio and music. [OMNI REFERENCES] [Image1] = Kael Ardyn, the exact playab…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb) (4443 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb)

**Source:** [@PromptSin](https://x.com/PromptSin/status/2083085328710238400) · 15s · 16:9 · Reference & Consistency

---
### 5. Sitcom Game Show Choice

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt"><img src="https://pbs.twimg.com/amplify_video_thumb/2083130633048694784/img/6bfTlMdE8iKutjpq.jpg" alt="Sitcom Game Show Choice" width="700" /></a>

<strong>Prompt</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic multi-camera television sitcom with native synchronized dialogue, audience reactions, SFX and music. [OMNI REFERENCES — [Image1] [Image2] […

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt) (4399 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt)

**Source:** [@PromptSin](https://x.com/PromptSin/status/2083130683183255894) · 15s · 16:9 · Character & Performance

---
### 6. Divine Ascension Web Interface

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax"><img src="https://pbs.twimg.com/amplify_video_thumb/2083087808584101888/img/YJQUBTO4YrEgmQRA.jpg" alt="Divine Ascension Web Interface" width="700" /></a>

<strong>Prompt</strong> — 15秒 | 16:9 | 1440p | 24fps | 无缝循环 | 网页首屏动画 [人物锁定 · @image1] 完全按照该参考图呈现，不进行任何重新设计。金色卷发、闭合的双眼、仰起的面容与安详神情；象牙色垂坠长袍；左右两枚金色玫瑰花章肩甲，含中心宝石与放射浮雕；金丝胸饰、十字垂饰、多层珠链；水晶巨剑，含金色巴洛克护手与剑柄头、缠绕剑柄，双臂高举过头横持，金色火柱自上贯入；白色大理石圆台；下…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax) (4269 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax)

**Source:** [@Cia0_exe](https://x.com/Cia0_exe/status/2083090068378616089) · 15s · 16:9 · Reference & Consistency

---
### 7. H3 Energy Drink Showcase

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb478dp000004l15tqgauxd"><img src="https://pbs.twimg.com/amplify_video_thumb/2082912615052050432/img/4kFMxx1VdMeuLzMU.jpg" alt="H3 Energy Drink Showcase" width="700" /></a>

<strong>Prompt</strong> — [FORMAT] 15-second vertical 9:16 photorealistic commercial product showcase with native synchronized stereo audio. [OMNI REFERENCE — [Image1]] [Image1] is the strict multi-angle product reference for …

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb478dp000004l15tqgauxd) (4178 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb478dp000004l15tqgauxd)

**Source:** [@PromptSin](https://x.com/PromptSin/status/2082912639647465647) · 15s · 9:16 · Product & Ads

---
### 8. Chibi Card Battle Game Spot

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t1gj000404jp58a34rrg"><img src="https://pbs.twimg.com/amplify_video_thumb/2083200281681244160/img/HMoAH6bI63vla0DX.jpg" alt="Chibi Card Battle Game Spot" width="700" /></a>

<strong>Prompt</strong> — 【图像参考 · 唯一依据】 本镜头使用上传的八张参考图。Image1至Image6为六位角色的唯一角色参考，Image7为场景的唯一参考，Image8为游戏界面的唯一参考。 Image1＝Capychan：水豚毛绒头套，头顶菠萝冠，金发带绿色挑染，左眼翠绿右眼天蓝，亮黄色10号球衣。 Image2＝Lionchan：狮子毛绒头套，头顶白玫瑰，橙色麻花辫带蓝色挑染，左眼蓝宝石右眼红宝石，白色10号球…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t1gj000404jp58a34rrg) (4053 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t1gj000404jp58a34rrg)

**Source:** [@Preda2005](https://x.com/Preda2005/status/2083203349739192726) · 15s · 16:9 · Reference & Consistency

---
### 9. Glacia Ice UI Interactive Loop

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb1gec6000504jojh8a34bi"><img src="https://pbs.twimg.com/amplify_video_thumb/2083178671440023552/img/VMAqXAYVXbVbBr_s.jpg" alt="Glacia Ice UI Interactive Loop" width="700" /></a>

<strong>Prompt</strong> — 无缝循环 | 网页首屏动画 [核心概念] 她的每一个动作都对应一种网页交互行为，她不是站在网页前，而是在演示这个网页如何运作。加载、悬停、点击、滚动、拖拽、轮播、提交、刷新——八种交互依次发生，每一种都有对应的冰质界面反馈。 [人物锁定 · @image1] 完全按照该参考图呈现，不进行任何重新设计。 容貌：年轻女性，薄荷绿齐颏短发，发丝随动作轻扬；锐利的浅青碧色双眼，青色指甲，水晶坠耳饰。 服装…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb1gec6000504jojh8a34bi) (3509 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb1gec6000504jojh8a34bi)

**Source:** [@Cia0_exe](https://x.com/Cia0_exe/status/2083180088775045626) · 15s · 16:9 · VFX & Transitions

---
### 10. Chilling Creature Horror Sequences

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb21nbo00000ajdti5nw0h2"><img src="https://pbs.twimg.com/amplify_video_thumb/2082759082411253760/img/ASy0atW22QDD7S-U.jpg" alt="Chilling Creature Horror Sequences" width="700" /></a>

<strong>Prompt</strong> — Four 15-second 6-shot creature-horror sequences. — THE BASEMENT THING — Shot 1 (0–2.5s): Close-up of a man's hand slowly pushing open a wooden basement door. Dim light spills in. He whispers: "Is some…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb21nbo00000ajdti5nw0h2) (3393 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb21nbo00000ajdti5nw0h2)

**Source:** [@Dheepanratnam](https://x.com/Dheepanratnam/status/2082760158296313960) · 15s · 16:9 · Cinematic

---
### 11. Cyber Grunge K-Pop MV

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t0ab000004jp8hfbfcbj"><img src="https://pbs.twimg.com/media/HOiNPd4bMAAp5fu.jpg" alt="Cyber Grunge K-Pop MV" width="700" /></a>

<strong>Prompt</strong> — 15s K-pop 女团 MV 提示词 主体：三人 K-pop 女团，人物形象与当前角色设定一致。 SOL：黑色长直发，冷静强势，黑色结构短西装、低腰百褶短裙、黑色长靴。 LUNA：银灰色短狼尾，冷感疏离，银灰短款机能夹克、黑色连体内搭、不对称裙裤、厚底靴。 CORONA：深红棕长卷发，带细辫，叛逆锋利，红黑赛车短夹克、低腰裙裤、绑带长靴。 场景：白色无缝影棚被重新处理成地下音乐杂志拍摄现场。背景…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t0ab000004jp8hfbfcbj) (3288 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsb3t0ab000004jp8hfbfcbj)

**Source:** [@liandeli2](https://x.com/liandeli2/status/2083070647660609837) · 15s · 16:9 · Video Editing

---
### 12. 1998 Seoul Hi8 Home Video

<a href="https://apimodels.app/minimax-h3-prompts#prompt-cmsakc7l5000104jw52pg0x2c"><img src="https://pbs.twimg.com/amplify_video_thumb/2082747028283719680/img/2ZOpzhqz3Lu8DZko.jpg" alt="1998 Seoul Hi8 Home Video" width="700" /></a>

<strong>Prompt</strong> — Create an authentic 15-second archival home video that appears to have been recorded in Seoul, South Korea, during the summer of 1998 using a consumer Hi8 or VHS-C camcorder. The camcorder is never vi…

[**Read the full prompt →**](https://apimodels.app/minimax-h3-prompts#prompt-cmsakc7l5000104jw52pg0x2c) (3225 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://apimodels.app/minimax-h3-prompts#prompt-cmsakc7l5000104jw52pg0x2c)

**Source:** [@itxabdullaa](https://x.com/itxabdullaa/status/2082747126497300930) · 15s · 16:9 · Cinematic

---
---

## Repository layout

| Path | What is in it |
|---|---|
| [`prompts/GALLERY.md`](./prompts/GALLERY.md) | All 138 entries with thumbnail, prompt and source — the full version of the featured section above |
| [`prompts/GALLERY.zh-CN.md`](./prompts/GALLERY.zh-CN.md) | Same gallery in Chinese |
| [`prompts/<category>/`](./prompts) | The 72 reconstructed prompts as individual `.md` files, grouped by use case — grep-friendly, MIT |

---

## Run these prompts

MiniMax H3 currently runs through MiniMax's own API and the Hailuo product, from roughly
**$0.13/second**. It is **not yet available through apimodels.app** — we do not list models
we have not got working. When it runs, it ships, and this repo gets updated the same day.

These image and video models **are** live on our unified API — one key, one endpoint, pay
as you go, $1 free on sign-up:

| Image | Video |
|---|---|
| [GPT Image 2](https://apimodels.app/models/gpt-image-2) · [all tiers](https://apimodels.app/models/gpt-image-2-all) | [Seedance 2.0](https://apimodels.app/models/seedance-2.0) |
| [Nano Banana 2](https://apimodels.app/models/nanobanana2) · [2 Lite](https://apimodels.app/models/nanobanana-2-lite) | [Kling V3](https://apimodels.app/models/kling-v3) |
| [Nano Banana Pro](https://apimodels.app/models/nanobananapro) · [Pro Lite](https://apimodels.app/models/nanobananapro-lite) | [VEO 3.1](https://apimodels.app/models/veo-3.1) |
| [Gemini 3 Pro Image](https://apimodels.app/models/gemini-3-pro-image) · [3.1 Flash Image](https://apimodels.app/models/gemini-3.1-flash-image) | [All models →](https://apimodels.app/models) |

```bash
curl -X POST https://apimodels.app/api/v1/images/generations-sync \
  -H "Authorization: Bearer $APIMODELS_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"gpt-image-2-all","prompt":"a frosted glass serum bottle on wet travertine, soft daylight","aspect_ratio":"4:5","resolution":"1K"}'
```

**[957 GPT Image 2 prompts →](https://apimodels.app/gpt-image-2-prompts)** — a second
library, same idea. · [API docs](https://apimodels.app/docs) ·
[Code examples](https://github.com/stimQQ/apimodels-api-demo)

---

## How to write a MiniMax H3 prompt

Distilled from reading every prompt in this library. The shift from image prompting is that
you now direct **time**, **camera** and **sound**, not just the frame.

1. **One action per prompt.** Clips are 4–15s. One clear beat beats three crammed ones.
2. **Spell out the camera move.** Dolly in, pull back, tracking, handheld drift, drone
   descent. Leave it out and you get a locked-off tripod.
3. **Write the sound.** H3 generates synced native audio — name the ambience, the action
   sound, even a line of dialogue.
4. **Set light and palette first.** One lighting/colour sentence decides the whole look.
5. **Give it timing.** Slow motion, real time, timelapse — and when the beat lands.
6. **References carry identity, the prompt carries action.** Up to 9 reference images hold
   the face, wardrobe or product; the prompt says what happens.
7. **Break it into timecoded shots.** The strongest prompts here read like a shot list:
   `0-4s — …`, `4-8s — …`.
8. **State what you do not want.** Almost every high-quality prompt ends with negative
   constraints: no extra limbs, no on-screen text, no camera shake.

---

## Contributing

Found a good H3 clip? Open an issue with the post link. If the creator published the prompt
we index it with credit; if not, we can reconstruct it and label it as such.

## Licence

[MIT](./LICENSE) — covers the reconstructed prompts and everything else we wrote. It does
**not** cover author-written prompts, which belong to their creators and are linked, not
relicensed.
