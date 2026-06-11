# External Report Research For Event Recaps

Use this reference when an activity article needs to incorporate current public coverage of the same event, work, project, or public program: media reports, official recaps, partner posts, WeChat Official Account articles, event pages, Xiaohongshu/Rednote posts, social posts, press releases, public attendee notes, public user experiences, or other participant accounts.

This is a lightweight editorial research step, not a full research report. The goal is to find useful public material, verify facts, notice angles already in circulation, identify participant/user experience signals, and propose what could support the user's article without diluting their voice.

Important: the agent does not get final judgment authority. The agent maps sources, summarizes what each source can and cannot support, flags risks, and suggests possible uses. The user decides which sources, angles, interpretations, and participant experiences should enter the final article.

## When To Research

Run live web research when:

- The user says similar reports have already been published.
- The event involves a public organization, brand, conference, work, project, community, or partner.
- The draft needs current facts, public positioning, media wording, or source links.
- The user asks to "调研一下网上已发布内容", "看看别人怎么写", "找同场报道", "看看小红书/社媒上有没有参与者反馈", "找其他参与方的报道", or "从公开资料里选素材".

Do not rely on memory for current coverage.

## Search Plan

Build 3-6 search queries from:

- Official event name in Chinese and English.
- Brand/organizer/partner names.
- Speaker names and titles.
- Project/work names, product names, exhibition names, campaign names, or community names.
- Date, city, venue, or event platform.
- Distinctive agenda terms, product names, campaign names, or slogans.
- Platform-specific queries: WeChat, 小红书/Rednote, 微博, Bilibili, 即刻, Twitter/X, LinkedIn, blog posts, newsletter, GitHub, forum posts, or event pages.
- Chinese and English variants when the event has international brands.

For WeChat sources:

- Prefer a WeChat article extraction workflow when available.
- Preserve source URL, account name, title, publish date, and any attribution needs.

For public web sources:

- Prioritize official pages, organizer/partner posts, credible media, and first-hand public recaps.
- Use social posts as weak signals unless they contain concrete first-hand observations, images, quotes, user experience, or repeated audience language.

For participant/user experience sources:

- Treat public attendee posts, Xiaohongshu notes, comments, social threads, and personal recaps as experience signals, not automatically as verified facts.
- Look for repeated wording, concrete scenes, questions, friction points, emotional reactions, and unexpected use cases.
- Do not expose ordinary participants' identities in the article unless the source is clearly public, attribution is appropriate, and the user confirms it.
- Prefer anonymized synthesis such as "有参与者提到..." unless the user wants and approves attribution.

## Source Matrix

Before drafting, build a compact internal matrix:

| Source | URL | Publisher/date | What it adds | Use mode | Risk |
| --- | --- | --- | --- | --- | --- |
| Official recap |  | facts, agenda, names | fact-check / cite | low |
| Partner article |  | partner framing or quote | attribute / paraphrase | attribution |
| Media report |  | public context or data | cite / contrast | check accuracy |
| Social post |  | 现场感 or audience reaction | weak signal / quote with permission | consent |
| Xiaohongshu/Rednote note |  | participant experience, images, language | weak signal / anonymized synthesis | consent/context |
| Public comment/thread |  | repeated audience wording, friction, questions | signal only / do not quote | low reliability |

Use mode options:

- `fact-check only`: use to verify names, dates, agenda, titles, links.
- `public context`: use to frame why the event matters publicly.
- `attributed quote`: quote briefly with publisher/person and URL.
- `paraphrase with attribution`: rewrite in Moon's language while naming the source.
- `angle contrast`: note what others emphasized so Moon can choose a different angle.
- `experience signal`: use as evidence that a question, feeling, or friction appeared among participants, but not as confirmed fact.
- `user decision`: present to the user as a possible source or angle and ask whether to include it.
- `do not use`: relevant but risky, repetitive, private, or unsupported.

## Selection Criteria

Choose material that helps one of these jobs:

- Verify factual details.
- Identify what has already been over-written, so Moon does not repeat the same angle.
- Find one public detail that strengthens Moon's现场观察.
- Find participant/user experience signals that reveal how the event, work, or project was actually received.
- Surface a useful contrast between official framing and lived experience.
- Support a claim with public evidence.
- Clarify partner contributions or institutional context.
- Help the user decide whether to include, ignore, anonymize, or further verify a public signal.

Reject material that:

- Sounds good but does not add evidence.
- Repeats the same press-release language.
- Is too promotional for Moon's voice.
- Contains private or semi-private details without clear permission.
- Would make Moon's article feel derivative.
- Turns scattered user comments into exaggerated conclusions.
- Treats social platform reactions as representative without enough evidence.

## Citation And Attribution Rules

- Attribute distinctive claims, statistics, phrases, or observations.
- Do not copy paragraph structure from public reports.
- Do not quote more than necessary; prefer short quotes with clear source labels.
- For ordinary participant or social-platform content, prefer anonymized synthesis unless attribution is clearly public and approved.
- When a source is a weak signal, label it as a signal, not a fact.
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

When using participant/user experience material:

1. Separate official facts from user experience signals.
2. Preserve the user's right to decide whether the signal matters.
3. Do not turn one post into "the audience felt...".
4. Use repeated or vivid public signals to generate questions, not forced conclusions.

## User Judgment Handoff

Before integrating public material into a final article, provide a decision layer when sources are interpretive, social, participant-generated, or strategically sensitive.

```markdown
## 使用者判断层

| 资料 | 可能说明什么 | 可靠度 | 风险 | 建议 |
| --- | --- | --- | --- | --- |
|  |  | 高/中/低 |  | 采用 / 弱化 / 匿名 / 待确认 / 不用 |

### 需要你决定

- 哪些公开资料可以进入正文？
- 哪些只作为事实校准？
- 哪些只作为选题或问题线索？
- 哪些参与者体验需要匿名或不使用？
- 哪些判断必须由你来承担，而不能由 AI 代说？
```

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

When the user asks to research broader online/public material around an event, work, project, or public program:

```markdown
## 公开资料调研地图

### 资料分层
| 类型 | 来源 | 主要内容 | 可用方式 | 可靠度 | 风险 |
| --- | --- | --- | --- | --- | --- |
| 官方/主办方 |  |  | 事实校准 / 官方口径 | 高 |  |
| 合作方/参与方 |  |  | 伙伴视角 / 补充事实 | 中-高 |  |
| 媒体/第三方 |  |  | 公共语境 / 对照角度 | 中 |  |
| 小红书/社媒/用户体验 |  |  | 体验信号 / 问题线索 | 低-中 |  |

### 已有角度

### 可补充的现场/体验信号

### 不建议直接采用的材料

### 使用者判断层
| 资料 | 可能说明什么 | 建议 | 需要你决定 |
| --- | --- | --- | --- |
```

When the user asks for the final Markdown directly, do the research internally and surface only:

- source-aware phrasing in the article
- source links if materially cited
- a compact public-material decision layer for sensitive or interpretive sources
- unresolved issues in `发布前确认`
- optional `素材使用说明`
