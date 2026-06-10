# External Report Research For Event Recaps

Use this reference when an activity article needs to incorporate current public coverage of the same event: media reports, official recaps, partner posts, WeChat Official Account articles, event pages, social posts, press releases, or public attendee notes.

This is a lightweight editorial research step, not a full research report. The goal is to find useful public material, verify facts, notice angles already in circulation, and decide what can support Moon's article without diluting her voice.

## When To Research

Run live web research when:

- The user says similar reports have already been published.
- The event involves a public organization, brand, conference, or partner such as AMD.
- The draft needs current facts, public positioning, media wording, or source links.
- The user asks to "调研一下网上已发布内容", "看看别人怎么写", "找同场报道", or "从公开报道里选素材".

Do not rely on memory for current coverage.

## Search Plan

Build 3-6 search queries from:

- Official event name in Chinese and English.
- Brand/organizer/partner names.
- Speaker names and titles.
- Date, city, venue, or event platform.
- Distinctive agenda terms, product names, campaign names, or slogans.
- Chinese and English variants when the event has international brands.

For WeChat sources:

- Prefer a WeChat article extraction workflow when available.
- Preserve source URL, account name, title, publish date, and any attribution needs.

For public web sources:

- Prioritize official pages, organizer/partner posts, credible media, and first-hand public recaps.
- Use social posts as weak signals unless they contain concrete first-hand observations.

## Source Matrix

Before drafting, build a compact internal matrix:

| Source | URL | Publisher/date | What it adds | Use mode | Risk |
| --- | --- | --- | --- | --- | --- |
| Official recap |  | facts, agenda, names | fact-check / cite | low |
| Partner article |  | partner framing or quote | attribute / paraphrase | attribution |
| Media report |  | public context or data | cite / contrast | check accuracy |
| Social post |  |现场感 or audience reaction | weak signal / quote with permission | consent |

Use mode options:

- `fact-check only`: use to verify names, dates, agenda, titles, links.
- `public context`: use to frame why the event matters publicly.
- `attributed quote`: quote briefly with publisher/person and URL.
- `paraphrase with attribution`: rewrite in Moon's language while naming the source.
- `angle contrast`: note what others emphasized so Moon can choose a different angle.
- `do not use`: relevant but risky, repetitive, private, or unsupported.

## Selection Criteria

Choose material that helps one of these jobs:

- Verify factual details.
- Identify what has already been over-written, so Moon does not repeat the same angle.
- Find one public detail that strengthens Moon's现场观察.
- Surface a useful contrast between official framing and lived experience.
- Support a claim with public evidence.
- Clarify partner contributions or institutional context.

Reject material that:

- Sounds good but does not add evidence.
- Repeats the same press-release language.
- Is too promotional for Moon's voice.
- Contains private or semi-private details without clear permission.
- Would make Moon's article feel derivative.

## Citation And Attribution Rules

- Attribute distinctive claims, statistics, phrases, or observations.
- Do not copy paragraph structure from public reports.
- Do not quote more than necessary; prefer short quotes with clear source labels.
- If the source is only used to fact-check basic details, citation may be omitted unless the user wants source notes.
- If public reports disagree, mark the conflict under `发布前确认`.
- Keep a `素材使用说明` section when external reports materially shaped the article.

Recommended note:

```markdown
## 素材使用说明

- 活动事实参考:
- 伙伴/媒体报道参考:
- 未直接采用但影响判断的公开材料:
- 需要确认的冲突或缺口:
```

## Integrating Research Into The Article

Do not put the research dump into the article. Fold it into the structure:

- Opening: use Moon's scene or question, not a media-summary lead.
- Middle: use public reports as support, contrast, or context.
- Partner section: name contributions and framing carefully.
- Ending: return to Moon's judgment and next action.

When writing about brands or institutions, avoid becoming a press release. Combine:

1. Verified official facts.
2. Publicly reported context.
3. Moon's现场观察.
4. A cautious interpretation that does not over-claim.

## Research Output Modes

When the user asks to see the research before drafting:

```markdown
## 同场活动公开报道调研

### 可用素材
| 素材 | 来源 | 可怎么用 | 风险 |
| --- | --- | --- | --- |

### 已经被写过的角度

### Moon 可以避开的重复写法

### 值得纳入正文的公开事实/细节

### 需要确认
```

When the user asks for the final Markdown directly, do the research internally and surface only:

- source-aware phrasing in the article
- source links if materially cited
- unresolved issues in `发布前确认`
- optional `素材使用说明`
