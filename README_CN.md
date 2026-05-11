[English](README.md)

# 同行互审制度

> 本指南面向 [Zhuang Liu](https://liuzhuang13.github.io/) 组内成员。欢迎其他人参考或改编使用。

**相关**: [Writing Guide](https://github.com/zlab-princeton-internal/writing-guide) · [Figure Guide](https://github.com/zlab-princeton-internal/figure-guide) · [AI Paper Checking](https://github.com/zlab-princeton-internal/ai-paper-checking) · [Writing Self-Review](https://github.com/zlab-princeton-internal/paper-rating)

## 形式

两人配对，一次专注一篇论文。预定一个**两小时的 session**，找一个有屏幕的会议室。

- 安排在双方都没有其他事情的时段。晚上或周末都可以，只要双方同意，并且在那些时间段头脑清醒、没有干扰。
- 必须是专注的、不被打断的时间。不要着急赶。
- 在满足以上条件的前提下，越早越好。

## 交付物

提前知道你要产出什么。整个流程会产出四份书面文档：

**1. 论文 feedback。** 列出 session 中提出的所有 fixes 和建议，按人归类。谁提出的就写在谁的名字下面。过程中收集截图 example：bad example、good example、以及修改前后的对比。可以用来改进 writing guide 和 figure guide。

**2. 指南 feedback。** 对 paper writing guidelines 和 figure guidelines 本身的反馈：哪些规则不清楚、哪些缺失、哪些多余、哪些没能捕捉到实际问题。这有助于持续改进指南。

**3. AI 检查系统 feedback。** 对 AI 论文检查系统的反馈：哪里做得好、哪里漏查了、哪里给出了错误或无用的结果。我会根据这些反馈进一步优化 AI 检查的 prompt。

**4. Peer review 流程 feedback。** 对 peer review 制度本身的反馈。哪里 work 得好，哪里 work 得不好。比如：打印论文有没有用？两小时够不够？reviewer 的领域跟论文是太近还是太远？时间安排是否方便？整个流程是否有必要？正面和负面反馈都要说。有助于改进制度本身。

Session 期间多做笔记，方便事后整理。如果有帮助，可以用 **Notion transcription** 记录讨论内容。

## Session 之前

**作者**：
- 用尽一切手段（自查、AI、同行反馈）确保论文达到最佳质量。可以使用我们的 [AI 论文检查](https://github.com/zlab-princeton-internal/ai-paper-checking)，也可以用你自己喜欢的 AI 工具。
- Session 之前必须通过所有 [writing](https://github.com/zlab-princeton-internal/writing-guide) 和 [figure](https://github.com/zlab-princeton-internal/figure-guide) requirements。不要带着还有明显问题的稿子来。

**审稿人**：
- 从头到尾逐字逐句读完整篇论文。至少一遍。
- 记录发现的问题、疑问和其他笔记。

**作者**也应提前准备问题，例如：
- "这句话说清楚了吗？"
- "这段你有什么建议？"
- "这个图传达的意思对吗？"

**审稿人**也应提前准备问题和修改建议，例如：
- "这句话是什么意思？"
- "这个 claim 好像没有支撑。能解释一下吗？"
- 建议的改写或修复方案

**双方**：
- 打印两份论文，带上笔，带到 session 中。
- 同时打印 [writing guide](https://github.com/zlab-princeton-internal/writing-guide)、[figure guide](https://github.com/zlab-princeton-internal/figure-guide)、以及 AI 生成的 report（如果跑过的话）。把所有相关资料都带上。

## Session 进行中

两个人，两小时，什么其他事都不干。对着论文一起找问题、讨论改进、修复问题。你可以：

- 对着打印稿逐页过
- 讨论和辩论发现的任何问题
- 现场跑 [AI 检查](https://github.com/zlab-princeton-internal/ai-paper-checking)，对着 AI 生成的 report 一起讨论
- 能当场修的就当场修

**如果觉得已经没有问题了，继续看。一定会发现新的问题。** 不要因为暂时看不出问题就提前结束。两个小时，不要缩短。

### 重点是 clarity，不只是格式

Peer review 最大的价值是**非作者视角**。作者有盲区。自己觉得显而易见的东西，读者可能看不懂。格式和机械性错误 AI 能查；人类 peer reviewer 独特的价值在于判断论文是否**讲得通**。

尤其关注：
- **Title** 是否清晰准确？
- **Abstract** 是否自洽、有吸引力？
- **Introduction** 是否把问题、动机和贡献讲清楚了？
- 非作者能否理解核心 claim？
- 是否有逻辑漏洞或不清楚的过渡？

## Session 之后

如果一个两小时的 session 不够，继续 book 下一个。直到**双方都同意**：

1. 论文通过了所有 writing guidelines。
2. 论文是高质量的。不只是"没有明显错误"，而是写得确实好、确实清楚。

作者和审稿人都必须能够 approve 这篇论文。双方都满意之前，流程不算结束。

之后整理顶部列出的四份交付物。

## 额外的高层反馈

除了配对 peer review 之外，作者还应该再找 **1-2 个人** 做一个更轻量的、约 45 分钟的高层审阅。这些人不需要检查格式或图表规则，只需要读 abstract、introduction 和 contributions，给出诚实的反馈：

- 论文在做什么、为什么重要，是否清楚？
- Contributions 是否容易理解？
- 写作是否对读者友好？
- 他们是否想继续读下去？

作者应该主动去找，在配对 session 之前或之后进行。

## 理念：内化"什么是好的写作"

在**开始写作时**就好好读一遍 writing guide 和 figure guide，而不是等到最后。深入领会每条规则的实际含义。重点不是背一个 checklist，而是培养自己对好的写作的感觉。

先自己检查。自己过一遍论文，直到找不出任何问题。然后再用 AI 来捕捉你遗漏的地方。AI 在你自己先做过充分检查之后最有用，因为你能理解它*为什么*报这个问题，以及这个报告是否合理。

**从长远来看，这才能真正提升你的写作能力。跳过自查直接用 AI 则不会。**
