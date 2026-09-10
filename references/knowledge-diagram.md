# 知识图解｜中密度

## 任务

把一个核心知识通过图解表达得相对充分。重点回答“它是什么、由什么组成、核心机制怎样、两种状态有什么差别”，不要求读者严格沿步骤执行。

先写教学句：

    看完后，读者能够复述：______。

## 可用骨架

- 中心概念与 3–5 个组成
- 输入、机制、结果
- 旧状态、变化点、新状态
- 底层、中层、上层
- 多个来源汇聚到一个核心
- 一个核心分成 2–3 个分支

一张图只保留一个主骨架。若核心是严格先后步骤、条件分支或循环，改用信息可视化。

## 信息限制

- 一个中心命题。
- 3–5 个必要语义节点。
- 4–8 个短标签。
- 最多一个主关系和一个辅助关系。
- 关系主要靠物件、位置和手绘连接表达，文字负责命名和补充。

## 风格母版

使用 assets/examples/paper-blue/02-knowledge-diagram-16x9-v2.png 作为浅纸背景、编辑线描、局部排线、手写关系和中等信息密度参考。只学习视觉语言，不复制节点内容、构图或芽仔动作；画幅仍严格服从用户选择，不因母版是 16:9 而改变比例。

## 材质统一门禁

- 芽仔、信息纸片和物件共享细墨轮廓、局部排线、克制印刷颗粒与浅接触阴影；空白背景只提供均匀浅纸色，不复制主体排线和颗粒。
- 芽仔可以有剪纸层次，但不能出现独立于背景的 3D 塑料高光、白棚光、厚阴影或商品渲染质感。
- 缩小到缩略图时，芽仔仍应像纸上画出来或剪出来的角色，而不是后贴进去的玩偶。
- 面罩反光遵守 yazai-ip.md：保留一块连续、较宽的单侧受光面和同侧自然衰减；禁止另一侧光点、孤立圆点和左右成对亮线。芽仔很小时仍保留短而宽的同侧弧面。

## 蓝色焦点

把中心命题或最关键变化放进一个明确的 #0138C4 语义承载面，例如蓝色撕纸块、蓝色墨带或核心物件。其上可用暖白手写字。另用 2–4 个小蓝色标记连接其余节点。禁止只有蓝箭头而没有蓝色核心焦点。

## 提示词骨架

    Use case: scientific-educational
    Asset type: {16:9 / 4:3 / 3:4} Chinese knowledge diagram

    Input images:
    - Image 1: Yazai identity reference. Preserve identity, proportions and fixed colors; do not copy its heavy background texture.
    - Image 2: light-paper knowledge-diagram style master. This image controls the medium: pale clean background, editorial ink drawing, object-local hatching, handwritten relationships and medium information density. Do not copy its concepts or layout.

    Primary request:
    Explain this knowledge visually: {主题}.

    Teaching goal:
    After viewing, the reader can restate: {教学句}.

    Information structure:
    - Core proposition: {中心命题}
    - Required nodes in reading order: {节点1} / {节点2} / {节点3} / {可选节点4} / {可选节点5}
    - Main relationship: {组成 / 机制 / 汇聚 / 分层 / 对比 / 分流}

    Composition:
    Build one coherent paper-based explanatory scene. Use hand-drawn paper objects, restrained cut-paper pieces, handwritten annotations and one primary relationship skeleton. Yazai is {关键操作}. Render Yazai with the same fine ink line, object-local hatching, restrained print grain and shallow shadow as surrounding objects. Keep the exposed background quiet and clean. The information remains understandable without the character.

    Visual system:
    Clean light-warm paper canvas, default #F6EFDC within #F4EDDD–#F8F1E0, almost invisible fine fibers, no full-canvas texture pattern. Use deep-ink handwritten Chinese, editorial outlines, object-local cross-hatching, light handmade borders and arrows, subtle tactile depth and generous breathing room. Place {中心命题/关键变化} on exactly one obvious #0138C4 torn-paper or ink-block focal anchor, optionally with warm-white handwriting; add only 2–4 smaller blue accents.

    Yazai visor:
    Keep a one-sided curved reflection to give the visor volume. Choose one light-facing side from Yazai's pose and scene lighting; place one contiguous broad soft crescent/oval highlight there, with tonal falloff only on the same side. No isolated dot or bright mark on the opposite side. For small Yazai, use one shorter, wider crescent on that same side; never remove the reflection entirely.

    Text (verbatim):
    "{标签1}" / "{标签2}" / "{标签3}" / "{标签4}" / "{可选标签5}" / "{可选标签6}" / "{可选标签7}" / "{可选标签8}"
    Render each phrase exactly once and add no other text.

    Avoid:
    Strict numbered steps, dense timeline, formal flowchart symbols, equal card grid, dashboard, fake UI, decorative icons, long paragraphs, heavy full-canvas paper texture, embossed swirls, cloudy stains, background hatching, glossy or 3D Yazai, second visor glint, isolated visor dot, opposite-side visor line, paired visor highlights, eyes or eyebrows, invented text, logo, watermark.

## 合格判断

读者先看到蓝色核心命题，再说出组成关系，最后注意到芽仔做了什么。芽仔必须像属于同一张纸；如果像后贴的 3D 玩偶，或只能看见几个漂亮物件却无法复述知识，图解失败。
