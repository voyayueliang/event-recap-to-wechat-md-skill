# Event Recap To WeChat Markdown Skill

一个面向活动组织者和社区运营者的 Codex skill：把活动录音、口述复盘、合作伙伴记录、同场公开报道调研和精选图片，整理成可发布公众号 Markdown 图文稿、会后传播包、社区记忆包或伙伴/赞助方回顾包。

它适合活动、圆桌、直播、工作坊、品牌会后报道、社区 meetup、媒体/伙伴联动报道等场景。它不是让 AI 代写通稿，而是给活动组织者提供一层会后内容与社区记忆基础设施：把现场材料、公开报道、图片和组织者判断组织成有证据、有边界、可发布、可回收的内容资产。

## 能做什么

- 整理活动事实、口述复盘、录音/逐字稿、伙伴记录和图片。
- 调研同一场活动已公开发布的报道、官方 recap、媒体报道、公众号文章和社交帖子。
- 从公开报道中筛选可用事实、公共语境、角度对照和可引用素材。
- 输出公众号 Markdown 草稿、24 小时会后传播包、社区记忆包、伙伴/赞助方回顾包或 public learning pack。
- 做去 AI 味、证据校准、关系边界、图片授权和合作伙伴署名检查。
- 区分表达轨和实验轨，避免把所有活动都写成同一种新闻稿。
- 把每场活动回收成素材卡、问题清单、伙伴 proof、方法笔记、下一场活动选题或 offer/product signal。
- 使用写作方法 playbook，把“先现场再观点”“证据比流畅重要”“图片进入叙事”等原则变成具体写作动作。
- 使用人类反馈词典，把“太 AI”“不像我”“逻辑像拼贴”“有点敏感”等自然反馈翻译成具体修改策略。

## 安装

把仓库里的 `event-recap-to-wechat-md` 文件夹复制到 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
cp -R event-recap-to-wechat-md ~/.codex/skills/
```

安装后，新开一个 Codex 线程或刷新 skill 列表，就可以用：

```text
用 $event-recap-to-wechat-md，把这场活动的口述复盘、伙伴记录、网上公开报道和图片整理成公众号 md。
```

也可以用基础设施模式：

```text
用 $event-recap-to-wechat-md，把这场社区活动整理成 24 小时会后传播包，包括主稿、社交短内容、伙伴感谢语、图片建议、素材卡和发布前确认。
```

## 推荐输入

可以一次性提供，也可以分几次补：

- 活动名称、时间、地点、主办方/合作方、嘉宾、议程
- 活动结束后的口述复盘
- 录音转写、会议笔记、PPT、聊天记录
- 合作伙伴已经发出的记录或链接
- 希望调研的公开报道线索
- 图片路径/链接，以及封面图偏好
- 哪些可以公开，哪些不能公开
- 希望读者看完后做什么

## 输出形态

默认输出：

- 标题候选
- 摘要
- 封面图建议
- 可发布正文
- 图片位置和图注
- 素材使用说明
- 发布前确认

当材料不足或风险较高时，会先输出缺口卡或文章方向卡，而不是硬写成确定稿。

基础设施模式可输出：

- 24 小时会后传播包
- 社区记忆包
- 伙伴/赞助方回顾包
- Public learning pack
- 活动资产回收卡
- 72 小时反馈回收卡

## 设计原则

- AI 是第二张编辑台，不是代笔。
- 先有现场，再有观点。
- 证据比流畅重要。
- 去 AI 味不是换词，而是恢复人的判断和素材质地。
- 对谈、活动、伙伴记录和公开报道都要保留来源边界。
- 图片是叙事结构的一部分，不是装饰。
- 发布前要检查事实、声音、关系、隐私、图片授权和合作伙伴署名。
- 每场活动都应该留下可复用的社区记忆，而不是只留下当日热闹。
- 用户反馈是工作流信号，不只是审美意见。

## 文件结构

```text
event-recap-to-wechat-md/
  SKILL.md
  agents/openai.yaml
  references/
    ai-collaboration-editorial-principles.md
    community-event-infrastructure.md
    content-creation-principles.md
    example-scenarios.md
    external-report-research.md
    human-feedback-dictionary.md
    output-contracts.md
    wechat-md-layout.md
    writing-method-playbook.md
```

## 方法论模块

- `writing-method-playbook.md`: 把活动材料变成公共写作的具体动作，包括开头场景、组织者判断、公开报道整合、图片叙事、去新闻稿腔。
- `human-feedback-dictionary.md`: 将用户自然反馈翻译成修改动作，避免只做表面润色。
- `output-contracts.md`: 固定不同交付物的输出形态，适合活动组织者直接复用。
- `example-scenarios.md`: 提供社区圆桌、品牌会后报道、工作坊、反馈修改、材料不足等示例。

## 备注

这个 skill 会在需要当前公开报道时要求进行 live web research。因为活动报道和媒体发布是时效性信息，不应该依赖模型记忆。
