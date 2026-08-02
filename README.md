# MiniMax H3 Prompts

[![Gallery](https://img.shields.io/badge/Browse-135%20prompts%20with%20video-F5FF60)](https://apimodels.app/minimax-h3-prompts)
[![API](https://img.shields.io/badge/One%20API-85%2B%20models-blue)](https://apimodels.app/models)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

A working prompt library for **MiniMax H3** (community name: Hailuo 3.0) — the multimodal
video model MiniMax released on 31 July 2026: 2K, 24fps, 4–15 second clips with natively
synced audio, up to 9 reference images / 3 video clips / 3 audio clips per request.

**Every prompt here has a video you can actually watch.** Browse them side by side with
their results in the gallery:

### → **[apimodels.app/minimax-h3-prompts](https://apimodels.app/minimax-h3-prompts)**

---

## What is in this repo

| | Count | Where |
|---|---|---|
| **Reconstructed prompts** (written by us, full text, MIT) | 72 | [`prompts/`](./prompts) |
| **Community prompts** (author-written, index only) | 63 | [`COMMUNITY-INDEX.md`](./COMMUNITY-INDEX.md) |

### Two kinds of prompt, kept clearly apart

**`prompts/` — reconstructed by us.** For clips whose author never published a prompt, we
fed sampled frames to a vision model and wrote the prompt that would most plausibly
reproduce them. These are ours, MIT-licensed, use them freely. They are a *writing
reference*, not the original author's prompt — a reconstruction describes the finished
clip, so it cannot recover negative constraints, exact dialogue or reference-image
workflows. Each file says so at the top.

**`COMMUNITY-INDEX.md` — written by their authors.** We index them: title, author, length,
a link to the original post and a link to our gallery where the prompt is shown with
attribution. **We do not copy the full text into this repo** — we do not own these prompts
and cannot relicense them. Authors who want an entry removed can open an issue.

---

## Run these prompts

MiniMax H3 currently runs through MiniMax's own API and the Hailuo product, from roughly
**$0.13/second**. It is **not yet available through apimodels.app** — we do not list models
we have not got working. The moment H3 runs reliably on our side we will list it and update
this repo.

Meanwhile, the video and image models below **are** live on our unified API — one key, one
endpoint, pay as you go, $1 free on sign-up:

### Image models

| Model | Page | Notes |
|---|---|---|
| **GPT Image 2** | [gpt-image-2](https://apimodels.app/models/gpt-image-2) | Native 1K / 2K / 4K, accurate on-image text |
| GPT Image 2 (all tiers) | [gpt-image-2-all](https://apimodels.app/models/gpt-image-2-all) | Every resolution/quality tier on one model string |
| **Nano Banana 2** | [nanobanana2](https://apimodels.app/models/nanobanana2) | Gemini image generation, fast and cheap |
| Nano Banana 2 Lite | [nanobanana-2-lite](https://apimodels.app/models/nanobanana-2-lite) | Cheapest tier |
| **Nano Banana Pro** | [nanobananapro](https://apimodels.app/models/nanobananapro) | Highest fidelity of the Banana line |
| Nano Banana Pro Lite | [nanobananapro-lite](https://apimodels.app/models/nanobananapro-lite) | Pro quality at a lower tier |
| Gemini 3 Pro Image | [gemini-3-pro-image](https://apimodels.app/models/gemini-3-pro-image) | |
| Gemini 3.1 Flash Image | [gemini-3.1-flash-image](https://apimodels.app/models/gemini-3.1-flash-image) | |

**[957 GPT Image 2 prompts →](https://apimodels.app/gpt-image-2-prompts)** — a second
library, same idea: every prompt with its rendered image, browsable by category.

### Video models

| Model | Page |
|---|---|
| **Seedance 2.0** | [seedance-2.0](https://apimodels.app/models/seedance-2.0) |
| **Kling V3** | [kling-v3](https://apimodels.app/models/kling-v3) |
| **VEO 3.1** | [veo-3.1](https://apimodels.app/models/veo-3.1) |

Full list: **[apimodels.app/models](https://apimodels.app/models)** ·
API docs: **[apimodels.app/docs](https://apimodels.app/docs)** ·
Code examples: **[apimodels-api-demo](https://github.com/stimQQ/apimodels-api-demo)**

### 30-second start

```bash
curl -X POST https://apimodels.app/api/v1/images/generations-sync \
  -H "Authorization: Bearer $APIMODELS_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"gpt-image-2-all","prompt":"a frosted glass serum bottle on wet travertine, soft daylight","aspect_ratio":"4:5","resolution":"1K"}'
```

---

## How to write a MiniMax H3 prompt

Distilled from reading all 135 prompts in the library. The shift from image prompting is
that you now direct **time**, **camera** and **sound**, not just the frame.

1. **One action per prompt.** Clips are 4–15s. "She pushes the door open and glances back"
   beats "she opens the door, crosses the hall, sits down and starts typing."
2. **Spell out the camera move.** Dolly in, pull back, tracking, handheld drift, drone
   descent. Leave it out and you get a locked-off tripod.
3. **Write the sound.** H3 generates synced native audio — name the ambience, the action
   sound, even a line of dialogue.
4. **Set light and palette first.** One lighting/colour sentence decides the whole look.
5. **Give it timing.** Slow motion, real time, timelapse — and when the beat lands.
6. **References carry identity, the prompt carries action.** Up to 9 reference images hold
   the face, wardrobe or product; the prompt says what happens.
7. **Break it into timecoded shots.** The strongest prompts in this library read like a
   shot list: `0-4s — …`, `4-8s — …`. The longest is 6,602 characters.
8. **State what you do not want.** Almost every high-quality prompt ends with negative
   constraints: no extra limbs, no on-screen text, no camera shake.

The **[gallery](https://apimodels.app/minimax-h3-prompts)** groups every prompt by
category — cinematic, camera motion, character performance, dialogue & sound, VFX,
animation, product ads, nature, animals, reference consistency, video editing.

---

## Contributing

Found a good H3 prompt with its clip? Open an issue with the post link. If the author
published the prompt we index it; if not, we can reconstruct it and label it as such.

## Licence

[MIT](./LICENSE) — covers the reconstructed prompts in `prompts/` and everything else we
wrote. It does **not** cover the community prompts indexed in `COMMUNITY-INDEX.md`; those
belong to their authors and are linked, not copied.
