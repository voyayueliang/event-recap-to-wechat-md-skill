# Example Scenarios

Use these examples to understand how to run the workflow. They are intentionally schematic so users can adapt them to real events.

## Example 1: Community Roundtable

### User Input

```markdown
活动: AI 创作者圆桌
时间地点: 2026-06-01, Shanghai
材料:
- 录音转写
- 我活动结束后的 8 分钟口述
- 3 张现场图
- 伙伴已经发了一篇公众号
目标:
- 明天发一篇公众号
- 顺便给朋友圈 3 条短内容
边界:
- 观众问题可以匿名转述
- 不要露出正脸
```

### Agent Route

- external report research: partner article + event page
- output contract: 24-Hour Recap Pack
- writing move: open with audience question
- risk: image permission, anonymous audience question

### Expected Output

- main WeChat Markdown draft
- 3 short social posts
- image placement table
- partner attribution note
- publish confirmation list

## Example 2: Brand Event / AMD-Style Recap

### User Input

```markdown
活动: 某品牌 AI 技术会后交流
材料:
- 我的参会口述
- 官网新闻稿
- 3 篇媒体报道
- 现场照片
目标:
- 写一篇不像新闻稿的会后观察
- 用公开报道校准事实
边界:
- 不写未经确认的商业合作
- 品牌表述要谨慎
```

### Agent Route

- external report research: required
- output contract: WeChat Markdown Draft + 素材使用说明
- writing move: contrast official framing with live room question
- evidence gate: public claims need source

### Expected Output

- source-aware article
- public report source matrix
- careful wording around brand/partner claims
- publish confirmation list

## Example 3: Workshop For Future Programming

### User Input

```markdown
活动: 社区工作坊
材料:
- 白板照片
- 参与者提问
- 主理人复盘
目标:
- 不急着公开，先整理成下一场活动线索
边界:
- 参与者不能实名
```

### Agent Route

- output contract: Community Memory Pack
- writing move: preserve questions and method notes
- publication: internal memory first

### Expected Output

- core questions from the room
- scene cards and quote cards
- next-event topic list
- relationship follow-up
- private material list

## Example 4: User Feedback Revision

### User Feedback

```text
这个太 AI 味了，前面太顺，嘉宾声音没了。
```

### Agent Route

- use `human-feedback-dictionary.md`
- identify failed layers: voice, dialogue form, over-synthesis
- restore short quotes and Q&A texture
- weaken neat takeaways
- consider edited dialogue instead of essay

### Expected Revision

- less summary
- more speaker texture
- real scene before judgment
- unresolved question preserved

## Example 5: Thin Material

### User Input

```markdown
只有几张照片和一句: "活动挺好，大家聊了很多 AI 教育的问题。"
```

### Agent Route

- do not invent a rich recap
- output Content View / Gap Card
- ask for organizer debrief, agenda, audience question, permission, CTA

### Expected Output

- what can be drafted lightly
- what is missing
- suggested voice-note prompts for the organizer
