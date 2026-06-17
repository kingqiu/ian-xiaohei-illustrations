# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse deep wine-red handwritten Chinese annotations and signal/calibration marks, with very little orange only if a path needs it and blue only if secondary system feedback is necessary. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
小小克, a living tiny unit of weight for the brand 两克伴: a small pure-black or near-black irregular blob-like creature with mass, white dot eyes, tiny thin legs, occasional thin arms, blank serious expression, and a wobbly asymmetric hand-drawn body. It can look like a black bean, ink drop, pebble, flattened shadow, or heavy soft block, but never like a standard calibration weight, seal, stamp, cylinder mascot, or cat. 小小克 must perform the core conceptual action, not decorate the scene. It should weigh value, calibrate judgment, detect signals, press down noise, anchor clues, or settle useful information. Make 小小克 serious, deadpan, slightly bizarre, and not cute.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：小小克在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black or near-black for main line art and 小小克. The LiangkeBan brand deep wine red, close to #B5122B, for signal arcs, calibration ticks, selected value marks, key warnings, problems, and results. Orange only when a main path/arrow absolutely needs separation. Blue only for secondary notes or feedback/system state, and omit it by default.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not turn 小小克 into a cat, cute pet, standard砝码, stamp, seal, sticker, or bright-color mascot. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 图像编辑提示

## 黄色小小克可选模式

只有当用户明确要求黄色小小克、高能模式、亲和模式、封面更抓眼、小红书卡片或轻松内容时，才在常规模板后追加：

```text
Optional yellow Xiaoxiaoke mode:
Use the yellow high-energy version of 小小克. The body is a warm golden-yellow soft downy fuzzy irregular mass, like a living tiny unit of weight with soft baby-down texture, but not a duck, bird, pet, toy, or existing character. No hard orange outline. Keep edges defined by soft fuzz and only sparse dark sketch marks at contact points. Use LiangkeBan deep wine red (#B5122B-like) for signal arcs, calibration ticks, selected value marks, and emphasis dots. Do not use blue. Keep the expression tiny-eyed, deadpan, serious, and slightly bizarre. Preserve weight through compression, sinking, anchoring, and pressure.
```

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强怪诞感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 小小克 more central to the conceptual action. 小小克 should be doing the strange work that explains the idea, not standing beside the diagram. Express its “living unit of weight” identity through pressure, weighing, calibration, sinking, anchoring, or signal detection. Keep it clean, sparse, hand-drawn, pure-black/near-black with sparse deep wine-red marks, and not cute.
```
