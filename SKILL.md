---
name: camera-motion-exp
description: 写、改、审 Seedance 2.0／2.5 视频提示词里的镜头句子之前必读：景别、角度、运镜、机位、视场、第一人称 POV 与镜头因果、镜头切分、说话镜头与画面对应、一镜到底的路径、转头与镜头节奏；含 JIN 的生成实测和待补。Read before writing or reviewing camera, shot-size, angle, camera-move, POV, long-take or pacing wording in any Seedance video prompt.
---

# 镜头学与运镜实验

**用法：** 写、改、审 Seedance 视频提示词里和镜头有关的句子之前，先读完本文件，再读「references/镜头学.md」。对话压缩后如果这些内容已经不在上下文里，重新读一遍。本 Skill 只提供镜头知识，不授权直接写提示词：写任何视频提示词前先问 JIN（见 jin-seedance-prompt-logic 第一节第 1 条）。

**最后更新：** 2026-10-22。

**读法：**
- 写镜头句子：读「references/镜头学.md」的第一、二、四节；第三节（画面与对白）、第五节（词表）、第六节（一镜到底）按需读。
- 查某个镜头词（景别、角度、运镜、密度）在 Seedance 里测没测过：看第五节每张表后面的"在 Seedance 里"；没写的就是没测。
- 一镜到底、POV 转头、30 秒长镜头：第二节和第六节。
- 镜头节奏（转头快慢、停留、声音和转头的先后）：第六节第 6 条和第七节。现在只有一个咖啡厅样本（单次，没有对照），第七节是待补，不当规则用。

**分工：** 本 Skill 只管镜头。提示词共用的写法（先问再写、参数不进提示词、一次只改一个变量等）归 jin-seedance-prompt-logic（仓库 weoiquan-art/prompit-logic）；Q 版格式归 weoiquan-art/chibi-；真人写实归 jin-realism-video-prompt；案例原文和成片复盘归 JIN 的私有库 video-exp。

**出处标签：**
- 〔JIN 规定〕JIN 明确定下的。
- 〔JIN 实测〕JIN 实际生成过的结果；只有一次的标"单次"。
- 〔官方 2.0〕〔官方 2.5〕来自官方 skill（sd2-pe／sd25-pe）或火山引擎官方 PDF，是官方写法，不是 JIN 实测；本 Skill 一律用自己的话转述。
- 〔JIN skill〕从 JIN 各个 skill 合并出来的通用写法。
- 〔候选〕〔影像常识〕〔外部样本〕〔博主，参考〕的意思见「references/镜头学.md」开头。

**修改治理：**
- 读取、审查、比较、学习，只授权分析，不授权修改本 Skill。要改，先列出改哪里、准确内容、原因、预期影响，问一句"是否按上述方案更改？"，然后停下等回复。〔同 jin-seedance-prompt-logic 第八节〕
- 新发现只作候选；官方和博主的说法只作参考；单次结果不写成规则。
- 这是公开仓库：不放官方 PDF 和官方 skill 的原文；私有库 video-exp 的案例原文不搬进来，只留结论和指向；视频和截图不入库。
- 如果 JIN 把本 Skill 上传到 claude.ai，那份和仓库里的文件是同一份文本：改一边就同步另一边，不一致时以 JIN 最后确认的为准。

**文件：**
- `references/镜头学.md`：全部规则、词表、排法和实测（镜头细则的家）。
- `README.md`：仓库说明和现状。
