# WeChat Markdown Layout Reference

Use this reference when producing the final Markdown article. Keep the output easy to paste into a WeChat Markdown editor and easy for the user to review.

## Input Bundle Pattern

Accept messy input. When useful, internally normalize it into this shape:

```markdown
活动口述:
合作伙伴记录:
录音/逐字稿/笔记:
图片:
必须出现:
不能出现:
希望读者做什么:
```

Do not require the user to fill every field before drafting. Missing items can go into `发布前确认`.

## Recommended Markdown Structure

```markdown
## 标题候选

1. 直接判断型
2. 现场张力型
3. 读者问题型
4. 栏目感/系列感
5. 轻传播型

## 摘要

一句话说明这篇为什么现在值得发。

## 封面图建议

![封面图: 简短说明](IMAGE_COVER)
*封面图注，可选。*

# 正文标题

开头: 用一个现场细节、问题、反差或用户口述里的判断进入。

![图1: 开场场景](IMAGE_01)
*图注: 说明照片里发生了什么，而不是重复"活动现场"。*

## 小标题一

2-5 个短段落。每段只承担一个意思。

> 如果有必要，放一句短引语。不要把长段逐字稿塞进引用。

## 小标题二

放第二个场景、人物、问题或方法。

![图2: 人物/互动/材料](IMAGE_02)
*图注。*

## 小标题三

把活动意义说清楚，但不要写成空泛总结。

## 接下来

用具体 CTA 结尾: 下一场活动、报名链接、资料领取、留言问题、合作邀请、对伙伴的感谢。

---

## 发布前确认

- 活动名称/日期/地点:
- 人名、机构名、头衔:
- 合作伙伴内容引用与署名:
- 图片授权、排序、图注:
- 链接、二维码或报名入口:
- 不能公开的信息:
```

## Image Rules

- Use exact image URLs or local paths when the user provides them.
- If the image identity is clear but no path is available, use placeholders: `IMAGE_COVER`, `IMAGE_01`, `IMAGE_02`.
- Alt text should name the image's narrative job, such as `图2: 观众提问`, not just `图片`.
- Place images after the paragraph that sets up their meaning.
- Prefer 3-6 images for a standard event article:
  - cover or poster
  - establishing scene
  - speaker or key moment
  - audience interaction
  - artifact, whiteboard, slide, table, or screenshot
  - closing group/photo/resource image
- Add captions only when they help readers understand who, what, or why the image matters.
- Do not claim a photo shows a moment unless the source says so.

## Article Rhythm

- Mobile paragraphs: usually 1-4 Chinese sentences.
- Section count: usually 3-5.
- Section headings: short, specific, and not all in the same grammatical pattern.
- Quotes: short, attributed when needed, and used as evidence rather than decoration.
- Partner notes: paraphrase and attribute if their formulation or observation is distinctive.
- Endings: avoid "未来可期" and similar generic closings; connect to the next real action.

## Publishing Notes

When the user asks for "直接出 md", return the Markdown artifact first. Put process notes only in `发布前确认` or a short `素材使用说明` after the draft.

If permissions are unclear, use cautious wording:

```markdown
## 发布前确认

- 图3 涉及观众正脸，需要确认是否可公开。
- 伙伴记录中这句判断建议署名或改成转述。
- 活动人数暂未确认，正文先不写具体数字。
```
