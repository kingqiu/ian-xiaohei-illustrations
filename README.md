# 两克伴小小克正文配图 Skill

> 把中文文章里的判断、流程、状态和隐喻，变成一张张白底、手绘、怪诞但清爽的正文配图。
>
> 16:9 横版 | 小小克 IP | 纯白手绘 | 两克伴酒红信号 | Codex Skill

---

## 这个仓库是什么

这是一个面向“两克伴”内容体系定制的 Codex Skill，用来指导 AI Agent 为中文文章、帖子、博客、Notion 文档和方法论内容生成正文配图。

它不是通用插画 prompt，也不是 PPT 信息图模板。它的核心目标是：先理解文章里的认知锚点，再把其中一个判断、流程、结构、状态或隐喻，变成一张有记忆点的 16:9 手绘解释图。

默认视觉 IP 是 **小小克**：一个纯黑/近黑、不规则、有质量感的“活着的重量单位”。小小克不是猫，不是砝码小人，不是贴纸，也不是站在角落里的装饰物，而是正在认真参与系统运转的荒诞工作者。

一句话：**让 AI 不只是“配一张图”，而是把文章里的一个关键认知动作画出来。**

---

## 适合谁用

特别适合：

- 写中文文章，需要正文配图和文章插图的人
- 做知识型内容、方法论内容、AI 工作流内容的人
- 想把抽象判断画成具体隐喻的人
- 想要一种比 PPT 信息图更轻、更怪、更有识别度的配图风格的人
- 用 Codex 做内容生产，希望稳定复用“两克伴”视觉语言的人

不适合：

- 想要商业插画、品牌 KV 或精致扁平插画的人
- 想要传统 PPT 信息图、复杂架构图或正式流程图的人
- 想要儿童卡通、表情包或可爱宠物 IP 的人
- 想把大量正文、长段解释或完整课程页塞进一张图里的人
- 需要严格可编辑矢量源文件的人

---

## 核心视觉

### 主线模式：黑色小小克

默认使用主线黑色小小克：

- 纯白背景，不要纸纹、米色、阴影、渐变
- 黑色手绘线稿，细线，轻微抖动
- 主体是纯黑/近黑的不规则小小克
- 大量留白，主体只占画面约 40%-60%
- 两克伴酒红用于信号弧、刻度、校准线、重点批注、判断结果
- 橙色只在路径关系必须分离时少量使用
- 蓝色默认不用，只在系统反馈必须出现时少量使用
- 一张图只表达一个核心动作、结构、状态或隐喻
- 小小克必须参与核心动作，不能只是装饰
- 怪诞、有创意、清爽，但不幼稚、不卖萌

### 可选模式：黄色小小克

黄色小小克不是默认模式。只有在用户明确要求以下方向时启用：

- 黄色小小克
- 高能模式
- 亲和模式
- 封面更抓眼
- 小红书卡片
- 轻松栏目或活动内容

黄色小小克的规则：

- 主体是暖黄色软绒团，不是纸片、不硬描边
- 仍然是不规则、有质量感的“活着的重量单位”
- 要软、蓬、微绒、能被压扁、能沉底、能拉住线索
- 两克伴酒红用于外围信号、刻度、标记点和重点
- 不用蓝色
- 不要画成小黄鸭、鸟、宠物、毛绒玩具或儿童绘本角色

深度文章、商业洞察、方法论正文配图，仍然优先使用主线黑色/近黑小小克。

---

## 它会产出什么

默认输出：

- 16:9 横版正文配图
- 一篇文章的 4-8 张 shot list
- 每张图的主题、核心意思、结构类型、小小克动作和中文标注建议
- 最终 PNG 图片，保存到 workspace 的 `assets/<article-slug>-illustrations/`

默认不输出：

- PPTX / PDF / Keynote
- SVG / HTML / Canvas 可编辑图
- 商业海报或封面 KV
- 大段文字型信息图

---

## 示例效果

当前仓库中的示例图主要用于校准线条密度、留白比例、颜色克制和“角色参与核心动作”的方式。它们不是构图模板，也不代表新的小小克品牌设定已经全部视觉化。

### 两个断点

![两个断点](examples/images/01-two-breakpoints.png)

### 按目的分拣

![按目的分拣](examples/images/02-sort-by-purpose.png)

### 一鱼多吃

![一鱼多吃](examples/images/03-one-fish-many-uses.png)

### 承接路径

![承接路径](examples/images/04-handoff-path.png)

### 信息井

![信息井](examples/images/05-information-well.png)

### 想法压机

![想法压机](examples/images/06-idea-press.png)

### 内容发酵

![内容发酵](examples/images/07-content-fermentation.png)

### 信任桥

![信任桥](examples/images/08-trust-bridge.png)

使用时应该从当前文章重新发明隐喻，不要照抄旧案例的物件和构图。

---

## 安装

克隆仓库：

```bash
git clone https://github.com/kingqiu/ian-xiaohei-illustrations.git
cd ian-xiaohei-illustrations
```

复制 Skill 到 Codex skills 目录：

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R ./ian-xiaohei-illustrations "${CODEX_HOME:-$HOME/.codex}/skills/"
```

安装后，在 Codex 里使用：

```text
Use $liangkeban-xiaoxiaoke-illustrations 为这篇中文文章设计并生成 5 张小小克怪诞正文配图。
```

---

## 怎么用

### 只做配图规划

```text
Use $liangkeban-xiaoxiaoke-illustrations 先不要生图。
请分析下面这篇文章哪里值得配图，输出 5 张左右的 shot list。
每张图写清楚：放在哪段后、主题、核心意思、结构类型、小小克在做什么、建议中文标注词。

<粘贴文章>
```

### 直接生成正文配图

```text
Use $liangkeban-xiaoxiaoke-illustrations 把下面这篇文章生成 4 张小小克怪诞正文配图。
要求：16:9 横版、纯白背景、黑色手绘线稿、两克伴酒红信号/刻度/重点批注。

<粘贴文章>
```

### 为单个概念生成一张图

```text
Use $liangkeban-xiaoxiaoke-illustrations 为“信任不是喊出来的，而是一块证据一块证据铺过去”生成一张正文配图。
画面要怪诞但清爽，小小克必须承担核心动作。
```

### 启用黄色小小克

```text
Use $liangkeban-xiaoxiaoke-illustrations 用黄色小小克高能模式，为这篇小红书卡片内容生成 3 张正文配图。
要求：暖黄色软绒主体、两克伴酒红信号、不要蓝色、不要纸片感。

<粘贴内容>
```

### 去掉图里的标题或错误文字

```text
Use $liangkeban-xiaoxiaoke-illustrations 帮我编辑这张图，去掉左上角的“流程图”标题，其他内容保持不变。
```

---

## 工作流程

这个 Skill 的流程是：

1. 读取文章、Markdown、Notion 内容、截图或用户给的主题
2. 提炼核心观点、认知转折、流程结构和适合视觉化的段落
3. 先输出 shot list：每张图只选一个认知锚点
4. 为每张图选择结构类型：Workflow、系统局部、前后对比、角色状态、概念隐喻、方法分层、地图路线或小漫画分镜
5. 重新发明一个低科技、怪诞但成立的物理隐喻
6. 让小小克承担核心动作
7. 每张图单独调用图像模型生成
8. 按 QA checklist 检查：白底、留白、小小克动作、中文标注、非 PPT 感、非旧案例复刻
9. 保存最终 PNG，并报告用途和路径

---

## 目录结构

```text
.
├── README.md
├── LICENSE
├── NOTICE.md
├── examples/
│   ├── images/
│   │   ├── 01-two-breakpoints.png
│   │   ├── 02-sort-by-purpose.png
│   │   └── ...
│   └── prompts.md
└── ian-xiaohei-illustrations/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    ├── assets/
    │   └── examples/
    └── references/
        ├── style-dna.md
        ├── xiaoxiaoke-ip.md
        ├── yellow-xiaoxiaoke-mode.md
        ├── composition-patterns.md
        ├── prompt-template.md
        └── qa-checklist.md
```

真正需要安装到 Codex 的是子目录：

```text
ian-xiaohei-illustrations/
```

根目录的 README、LICENSE、NOTICE 和 examples 是 GitHub 分享文档。

---

## 注意事项

- 图片里的中文文字越短越稳定。
- 每张图只讲一个核心结构，不要把文章做成说明书。
- 小小克必须承担核心动作；如果去掉小小克画面仍然完全成立，说明小小克太装饰了。
- 主线默认是黑色/近黑小小克，不要未经要求切成黄色模式。
- 黄色小小克只适合高能、亲和、封面、小红书卡片和轻松内容。
- 示例图只用于校准线条密度、留白、颜色克制和角色参与方式，不要复刻构图。
- AI 图像模型可能出现错字、幻觉标签、风格漂移或多余标题，生成后需要检查。
- 如果中文错字严重，优先减少标注词并重生成。

---

## 当前版本

这个版本已经迁移为“两克伴小小克”风格：

- 主线 IP：纯黑/近黑小小克
- 品牌色：两克伴酒红信号
- 可选模式：黄色软绒小小克
- 核心机制：仍然是认知锚点、原创隐喻、角色承担核心动作
