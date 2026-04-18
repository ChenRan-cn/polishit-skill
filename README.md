# 雕屎.skill
## polishit.skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/ChenRan-cn/polishit.skill?style=social)](https://github.com/ChenRan-cn/polishit.skill/stargazers)

> **polish** (抛光) + **shit** (屎) = **polishit** (给屎抛光)
>
> 帮打工人把形式主义的"屎"，"雕"成能交差的"花"。

---

## 项目名称释义

本项目的名称 **“雕屎”** 取自 **“屎上雕花”**。

**“屎”** ：指那些毫无实际价值、纯粹为了满足形式主义要求、消耗打工人生命却不得不完成的文字垃圾工作。包括但不限于：没人看的周报、千篇一律的通讯稿、自欺欺人的整改报告、歌功颂德的年终总结。

**“雕”** ：指打工人被迫练就的一项扭曲而精湛的生存技能——用最小的认知成本，把这些“屎”包装成符合体制审美、能顺利通过审查、甚至还能换来一句“写的不错”的“花”。

**雕屎.skill** 要做的，不是教你认真对待这些工作（那是对你生命的浪费），而是教你用最短的时间、最标准的姿势，合规地应付过去。

---

## What the Name Means

The project name **"polishit"** comes from **"polishing a turd"**.

**"Shit"**: The utterly worthless, soul‑draining, mandatory busywork that exists only to satisfy bureaucratic formalism—unread weekly reports, cookie‑cutter press releases, self‑deceptive rectification documents, and glorified year‑end summaries.

**"Polish"**: The twisted yet refined survival skill we're forced to master—dressing up that "shit" with minimal cognitive effort so it meets institutional aesthetics, sails through approval, and maybe even earns a "nice work."

**polishit.skill** doesn't teach you to take this busywork seriously (that would be a waste of your life). It teaches you how to get it over with—fast, formulaically, and fully compliant—so you can move on.

---

## 为什么叫这个名字？

因为我们必须先诚实。

我们得承认：那些东西就是屎。只有承认这一点，我们才不会在应付它的时候，误以为自己真的在“创造价值”。

然后我们才能有技巧地应付。而“雕”这个动作的精髓在于——不投入感情，只投入技巧。

---

## Why This Name?

Because honesty comes first.

We have to admit it: that stuff is shit. Only by admitting that can we avoid the delusion that we're actually "creating value" while churning it out.

Only then can we deal with it skillfully. And the essence of "polishing" is this: invest zero emotion, just technique.

---

## 能干什么

| 模块                | 适用场景                               | 触发词                                    |
| :------------------ | :------------------------------------- | :---------------------------------------- |
| 通讯稿生成器        | 单位发布工作动态 / 企业宣传新闻稿      | 通讯稿、新闻稿、工作动态                  |
| 周报/月报膨胀器     | 明明没干啥，要写满字数                 | 周报、月报、日报                          |
| PPT大纲生成器       | 三句话的事要整15页PPT / 晋升答辩PPT    | PPT、汇报、述职                           |
| 总结与复盘生成器    | 年终述职 / 项目复盘 / 阶段总结         | 年终总结、复盘、阶段总结、述职、OKR、绩效 |
| 整改报告生成器      | 被提意见了要回复 / 投标澄清 / 问题整改 | 整改报告、立行立改、回复函                |
| 民主生活会生成器    | 批评与自我批评（体制内）               | 民主生活会、对照检查                      |
| 领导讲话稿填充器    | 代写领导讲话、会议发言（体制内为主）   | 讲话稿、发言稿                            |
| 学习心得生成器      | 培训感悟 / 参会感想 / 观后感           | 学习心得、培训心得、参会感想              |
| 方案/提案生成器     | 工作方案 / 项目提案 / 执行方案         | 方案、提案、立项、Project Proposal        |
| 会议纪要生成器      | 会议纪要 / Meeting Notes               | 会议纪要、会议记录、Meeting Notes         |
| 竞品/市场分析生成器 | 竞品分析 / 市场调研                    | 竞品分析、市场调研、Competitive Analysis  |
| 通用：润色改写      | 口语↔正式用语互译                      | 润色、改写、更正式、更口语化              |
| 通用：标题生成器    | 对仗标题 / 抓眼球标题                  | 起标题、拟定标题、取个名字                |

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

安装完成后，直接告诉 AI 你需要对付什么任务即可。polishit 有两种工作模式：

### 全自动档（默认）

开箱即用，AI 根据内置规则直接生成内容。

```
你：帮我写个周报，这周开了两个会跟进了A客户
polishit：[直接输出成品]
```

### 半自动档

上传一批参考文档（3-10篇），AI 先**蒸馏**出共性惯例，再按惯例生成。

适用于：单位/公司已有固定风格、领导有固定口味、需要和已有惯例高度一致的场景。

触发方式：
```
你（全自动）：帮我写个通讯稿，这周搞了用户调研

你（半自动）：半自动模式，这是我单位过去5篇通讯稿，按这个惯例帮我写一篇新的
             [上传参考文件]

polishit：[先分析惯例，再生成成品]
```

两种模式下，只需自然语言描述任务即可，无需记触发词或模块名。

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

**你说：** 帮我写个培训方案，下个月要对全员做一次安全生产培训

**polishit 输出：**
> XX单位全员安全生产培训工作方案
> 一、培训目的：进一步强化全员安全意识...
> 二、培训对象：全体在岗人员...
> 三、培训内容：（一）安全生产法律法规解读；（二）典型事故案例分析...
> 四、时间安排：X月X日-X月X日...
> 五、保障措施：加强组织领导，明确责任分工...

---

**你说：** 开了个会，领导说要加强部门协作，让我出个纪要

**polishit 输出：**
> XX部门工作会议纪要
> 时间：... 地点：... 参会人员：... 主持人：...
> 会议听取了...，讨论了...，形成如下决议：
> 一、...
> 二、...
> 会议要求各相关部门按上述安排抓好落实。

---

**你说：** 帮我润色一下这段话："领导说要把客户服务做好，不能让客户等太久"

**polishit 输出：**
> 会议强调，要始终坚持以客户为中心的服务理念，持续优化服务流程，切实提升服务响应效率，不断提升客户满意度。

---

## License

MIT — 随便用，随便改，随便分发。

如果这个 Skill 帮你从形式主义里夺回了一点时间，那就值了。
