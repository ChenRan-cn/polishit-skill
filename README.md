## 项目名称释义

本项目的名称 **"雕屎"** 取自互联网职场黑话 **"屎上雕花"**。

**"屎"**：指那些毫无实际价值、纯粹为了满足形式主义要求、消耗打工人生命却不得不完成的文字垃圾工作。包括没人看的周报、千篇一律的通讯稿、自欺欺人的整改报告、歌功颂德的年终总结、格式重于实质的OKR填写。

**"雕"**：指打工人被迫练就的一项扭曲而精湛的生存技能——用最小的认知成本，把这些"屎"包装成符合审美标准、能顺利通过审查、甚至还能换来一句"写得不错"的"花"。

为什么叫这个名字？因为我们必须先诚实——承认那些东西就是屎。只有承认这一点，才不会在应付它的时候误以为自己在"创造价值"。然后才能有技巧地应付。而"雕"的精髓在于：不投入感情，只投入技巧。

---

<!-- ENGLISH BELOW / What the Name Means -->

## What the Name Means

The project name **"polishit"** comes from the internet workplace slang **"polishing a turd."**

**"Shit"**: The utterly worthless, soul-draining, mandatory busywork that exists only to satisfy bureaucratic formalism — unread weekly reports, cookie-cutter press releases, self-deceptive rectification documents, glorified year-end summaries, and OKR forms where formatting matters more than content.

**"Polish"**: The twisted yet refined survival skill we're forced to master — dressing up that "shit" with minimal cognitive effort so it meets institutional aesthetics, sails through approval, and maybe even earns a "nice work."

Why this name? Because honesty comes first. We have to admit it: that stuff is shit. Only by admitting that can we avoid the delusion that we're actually "creating value" while churning it out. Only then can we deal with it skillfully. And the essence of "polishing" is this: invest zero emotion, just technique.

---

## 能干什么

| 模块 | 适用场景 | 触发词 |
|------|----------|--------|
| 通讯稿生成器 | 单位发布工作动态 / 企业宣传新闻稿 | 通讯稿、新闻稿、工作动态 |
| 周报/月报膨胀器 | 明明没干啥，要写满字数 | 周报、月报、日报 |
| PPT大纲生成器 | 三句话的事要整15页PPT / 晋升答辩PPT | PPT、汇报、述职 |
| 年终总结转化器 | 年终述职 / OKR自评 / 绩效考核填写 | 年终总结、述职报告、OKR、绩效 |
| 整改报告生成器 | 被提意见了要回复 / 投标澄清 / 问题整改 | 整改报告、立行立改、回复函 |
| 民主生活会生成器 | 批评与自我批评（体制内） | 民主生活会、对照检查 |
| 领导讲话稿填充器 | 代写领导讲话、会议发言（体制内为主） | 讲话稿、发言稿 |
| 学习心得生成器 | 培训感悟 / 参会感想 / 观后感 | 学习心得、培训心得、参会感想 |

---

## 设计理念

**不是帮你卷赢同事，而是帮你把被浪费的时间夺回来。**

那些设计形式主义制度的人，赌的就是你会把时间耗在这些事情上——耗到你没精力思考、没时间成长、没心气反抗。

而 polishit.skill 的逻辑是：用你教我的规则，用最短的时间把你布置的作业写完，然后转身去做我真正想做的事。

**这不是消极怠工，这是战略性应付。**

---

## 把省下来的时间用于

- 真正重要的工作
- 陪家人吃一顿完整的晚饭
- 读完那本买了一年没拆封的书
- 什么都不做，只是发呆

---

## 安装方法

### 1. OpenClaw 平台

```bash
git clone https://github.com/ChenRan-cn/polishit.skill ~/.openclaw/workspace/skills/polishit
```

### 2. Claude Code 平台

```bash
# 安装到当前项目（需要在 git 仓库根目录运行）
mkdir -p .claude/skills
git clone https://github.com/ChenRan-cn/polishit.skill .claude/skills/polishit

# 或者全局安装（所有项目都可用）
git clone https://github.com/ChenRan-cn/polishit.skill ~/.claude/skills/polishit
```

> **重要提示**：Claude Code 会在 git 仓库根目录的 `.claude/skills/` 下查找 skills，请确保在正确的位置运行。

### 3. WorkBuddy 平台

```bash
git clone https://github.com/ChenRan-cn/polishit.skill ~/.workbuddy/skills/polishit
```

或者直接把 `SKILL.md` 文件下载到 skills 目录下。

### 4. 手动安装

把 `SKILL.md` 放到你的 AI 工具的 skills 文件夹，重启即可。

---

## 如何使用

安装完成后，直接告诉 AI 你需要对付什么任务即可：

- **"帮我写个周报，这周干了……"**
- **"要写通讯稿，我们部门搞了……"**
- **"年终总结怎么写……"**

polishit 会自动识别并输出成品，可以直接提交。

---

## 使用示例

**你说：** 帮我写个通讯稿，这周部门搞了一次用户调研活动，覆盖了30家企业

**polishit 输出：**
> 【深耕客户·服务升级】XX部门扎实推进用户需求专项调研工作
>
> 近日，XX部门紧紧围绕"以客户为中心"服务理念，聚焦用户真实需求，组织开展用户需求专项调研活动，全面摸排服务现状，持续提升服务质量。

---

**你说：** 周报，这周开了两个会，跟进了A客户，其他时间在熟悉新系统

**polishit 输出：**
> 一、深度跟进A客户需求，完成关键决策人触达与需求画像更新，为下一阶段商务推进奠定基础。
> 二、组织召开项目复盘会与需求评审会，对齐多方认知，明确执行路径与风险预案。
> 三、完成新系统操作流程学习与实操演练，提升个人工作效率，缩短任务响应周期。

---

## License

MIT — 随便用，随便改，随便分发。

如果这个 Skill 帮你从形式主义里夺回了一点时间，那就值了。
