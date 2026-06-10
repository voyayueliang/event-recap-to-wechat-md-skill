---
name: event-recap-to-wechat-md
description: 将活动录音、活动回放、活动结束后的口述复盘、同场活动公开报道调研、合作伙伴已发布记录、现场照片、海报、截图和精选图片整合成可发布的公众号 Markdown 图文草稿。Use when the user asks to 活动复盘转公众号, 活动录音整理成推文, 调研同一场活动已发布报道, 结合合作伙伴记录和图片出 md, 活动传播稿, 沙龙/工作坊/圆桌/直播活动纪要转公众号, or produce publish-ready WeChat Markdown with image placement, captions, external-source research, public-boundary checks, and CTA.
---

# Event Recap To WeChat Markdown

Use this skill to turn mixed event material into a ready-to-edit WeChat article draft. The goal is not a neutral event summary; it is a publishable传播稿 that preserves the现场感, names the public value of the event, integrates public reports and partner references responsibly, and places selected images in the Markdown body.

For final drafts, always apply `references/ai-collaboration-editorial-principles.md`. These principles protect the user's voice, reduce AI味, keep claims evidence-based, and prevent the agent from crossing public/private or partner boundaries.

Also apply `references/content-creation-principles.md` for the broader content creation principles: real voice, scene before concept, evidence before fluency, expression/experiment tracks, platform fit, and asset recovery.

When the user mentions that the event already has public reports, media coverage, partner posts, WeChat articles, official recaps, social posts, or "网上已经有人发了", use live web research and apply `references/external-report-research.md` before drafting. Current external coverage is time-sensitive; do not rely on memory.

If the source is only a raw transcript or recording with no publication goal yet, use an audio-to-article or transcript-cleanup workflow first if available. Use this skill when the user wants a finished activity article, especially when they provide a post-event oral debrief, partner notes, and images.

## Default Stance

- Treat the user's口述复盘 as the editorial backbone.
- Treat AI as an editor and structure helper, not as the author of the user's judgment.
- Treat recordings, transcripts, slides, chats, and partner records as evidence and texture.
- Treat partner-published records as references, not as copy to rewrite or silently absorb.
- Treat public online reports as research sources: useful for fact-checking, angles, public context, and attribution, but not as language to copy.
- Treat selected images as part of the narrative structure, not decoration.
- Produce the smallest useful output, but default to a Markdown draft when the user asks to "直接出 md", "排版好", "可发布", or "公众号稿".
- Do not fabricate attendance numbers, speaker intent, audience reactions, quotes, partner positions, or future plans.
- Preserve uncertainty, hesitation, discomfort, and relationship care when they are part of the user's real judgment.

## Workflow

1. Build an input map:
   - 活动事实: name, date, city/platform, format, organizers, partners, speakers, audience.
   - 用户口述: why this event mattered, what surprised them, what they want readers to remember, next action.
   - Source material: audio, transcript, notes, slides, chat logs, agenda, registration copy, partner articles/posts.
   - External research need: whether to search media reports, partner/organizer pages, WeChat articles, social posts, press releases, or event pages.
   - Images: cover candidate, scene photos, speaker photos, audience/action photos, artifacts, screenshots, posters.
   - Boundaries: public, semi-public, off-record, needs consent, anonymize, do not mention.
2. Ask only for blockers. If details are missing but the article can be drafted, continue and add them to `发布前确认`.
3. Run external report research when needed:
   - Use `references/external-report-research.md` when the user says there are public reports, when the activity involves a public brand or institution such as AMD, or when facts/positioning need current verification.
   - Search the live web for same-event coverage using event name, organizer, partner names, speaker names, date, city, and distinctive agenda terms.
   - For WeChat Official Account sources, use a WeChat article extraction workflow when available; otherwise search for public links and cite them.
   - Build a compact source matrix: source, URL, publisher, date, useful material, how it can be used, attribution need, risk.
   - Do not let external coverage decide the user's article angle; use it to support, contrast, verify, or enrich the user's editorial backbone.
4. Apply collaboration and editorial principles:
   - Use `references/ai-collaboration-editorial-principles.md` for AI collaboration boundaries, anti-AI-writing checks, evidence calibration, partner attribution, and cautious publishing rules.
   - If the article contains strong claims, partner references, audience stories, or sensitive images, run the principle checklist before drafting and again before finalizing.
5. Decide the best article form:
   - `活动复盘报道`: what happened, why it mattered, who was there, what comes next.
   - `现场观察文`: one public insight revealed by the room, supported by scenes and quotes.
   - `方法提炼文`: turn event practice into a reusable method, checklist, or playbook.
   - `人物/群像文`: show participants, partners, creators, or audience through concrete moments.
   - `伙伴联动文`: emphasize cross-organization collaboration, shared problem, and mutual value.
   - `品牌/机构会后报道`: synthesize official facts, public reports, and the user's现场观察 without sounding like a press release.
   - `下场预告文`: use this event as proof for a next workshop, community action, recruitment, or collaboration.
6. Reconcile sources:
   - Compare partner records with the user's memory and the recording.
   - Compare public reports with the user's memory, event facts, and partner records.
   - Attribute externally published claims when they are distinctive.
   - Use short quotes only when they carry voice, evidence, or emotional weight.
   - If sources conflict, prefer the user's boundary and mark uncertainty for confirmation.
7. Build the article before drafting:
   - One-sentence thesis.
   - 3-5 section arc.
   - Key scene or quote for each section.
   - Image placement plan.
   - External-source usage plan: cite, paraphrase, fact-check only, or do not use.
   - CTA tied to the actual event: next event, reply invitation, registration, partner thanks, resource link, or collaboration opening.
8. Draft as Markdown:
   - Use the layout rules in `references/wechat-md-layout.md` when producing final Markdown.
   - Put images near the paragraph they support.
   - Use real image paths/URLs when provided; otherwise use stable placeholders like `IMAGE_01` and descriptive alt text.
   - Keep paragraphs short enough for mobile reading.
   - Include source links or a `素材使用说明` section when external reports are used materially.
   - Include `发布前确认` for facts, permissions, names, image choices, or links that need final approval.
9. Run a final editorial check:
   - Is there one clear reason this article should exist?
   - Are the strongest scenes shown before abstract conclusions?
   - Are partner references transformed and attributed rather than copied?
   - Are external reports used with source awareness rather than copied or over-weighted?
   - Are private details, client details, audience stories, and off-record comments protected?
   - Are factual claims supported by source material, or weakened into observations/questions?
   - Does AI stay in its role as editor rather than replacing the user's judgment?
   - Does the piece sound like a lived event, not a press release or generic AI recap?

## Output Modes

### Intake Gap Card

Use when there are serious missing details or boundary risks.

```markdown
## 还差哪些信息

| 缺口 | 为什么影响发布 | 可先怎么处理 |
| --- | --- | --- |

## 可以先写的方向

## 需要确认后再写的内容
```

### Article Direction Card

Use when the user asks for angles before drafting.

```markdown
## 最强传播方向

## 标题候选

## 文章结构

## 图片使用建议

## 合作伙伴内容怎么用

## 发布风险
```

### WeChat Markdown Draft

Use by default when the user asks for a finished draft.

```markdown
## 标题候选

## 摘要

## 封面图建议

# 正文标题

导语段落。

![图1: 现场/人物/材料说明](IMAGE_01)
*图注。*

## 小标题

正文段落。

> 短引用或现场原话。

![图2: 说明](IMAGE_02)

## 结尾

CTA。

---

## 发布前确认

- 人名/机构名:
- 图片授权/图注:
- 合作伙伴引用:
- 活动链接/报名链接:
```

## Style Rules

- Start from a concrete scene, tension, or public question; avoid "本次活动圆满举行" as the opening unless the user requests official copy.
- Keep the event's living texture: room details, audience questions, speaker hesitations, artifacts, photos, and small turning points.
- Do not over-summarize every agenda item. Select the moments that support the article's claim.
- Use partner materials and public reports to widen perspective, cross-check facts, and add public context.
- Preserve Moon's voice: concrete before conceptual, field detail before trend judgment, relationship boundary before promotional enthusiasm.
- Avoid AI-flavored transitions, promotional slogans, and overly complete frameworks unless the source supports them.
- Close with a soft, specific action instead of a generic slogan.

## Guardrails

- Do not publish private conversations, client details, financial terms, identifiable audience stories, or off-record comments without permission.
- Do not turn a partner's claim into the user's stance unless that relationship is explicit.
- Do not copy public reports or partner articles. Paraphrase, cite, or mark as reference-only.
- Do not use images whose publication permission is unclear without flagging them.
- Do not imply co-hosting, endorsement, sponsorship, or partnership beyond the source material.
- If the material is thin, draft a lighter recap and clearly mark what would make it stronger.
