# 信息可视化｜高密度

## 任务

把核心信息组织成能够被准确阅读的逻辑路径。结构是主语，芽仔只负责指示、操作或检查关键节点。

适用关系：

- 顺序与步骤
- 因果与依赖
- 条件分支
- 反馈循环
- 时间演化
- 对比维度
- 数据变化和证据关系

## 先提取信息模块并自动定页数

把需要独立解释的论点、流程、时间线、对比、案例组、数据故事、清单、框架和结论分别计为信息模块。每页目标是 4–6 个可读模块：

- 1–5 个模块：1 张
- 6–10 个模块：2 张
- 11–15 个模块：3 张
- 16–20 个模块：4 张
- 21–30 个模块：5–6 张
- 超过 30 个模块：最多 8 张，合并或省略低优先级重复信息

能组成同一条时间线、流程或数据故事的模块可以合并，但不得为了固定页数缩小文字、压缩间距或堆成卡片墙。用户指定单页时，保留最关键的 4–6 个模块，并在交付中说明省略项。

## 选择页面任务与版式

- 总览或框架：标题、核心命题、3–6 个概念块
- 流程：编号步骤、方向明确的起点到终点
- 时间线：按日期排列的轨道、事件和结果
- 对比：两栏或三栏，使用完全相同的比较维度
- 数据故事：一个主图表、精确标注和简短解释
- 证据或案例：中心证据或事实簇，配合手绘注释
- 清单或指南：分组行动、警告和完成提示
- 结论：压缩后的核心结论、下一步和有意义的芽仔动作

## 页面计划

每页只有一个沟通任务，并记录：

- 页码与页面目标
- 精确标题和可选短副标题
- 信息块及其阅读顺序
- 版式类型与视觉层级
- 阅读起点、方向和终点
- 图表、时间线、分支、轴线或箭头规则
- 芽仔动作、位置和情境道具
- 主蓝色焦点承载的逐字文本或关键物件
- 2–4 个次级蓝色强调和蓝色面积上限
- 精确文本清单

## 关系规则

- 步骤：编号与箭头必须保持原顺序。
- 时间线：日期、先后和事件结果必须准确。
- 分支：条件和出口一一对应，默认不超过 3 个一级分支。
- 循环：回流方向必须清楚，不能只画装饰圆环。
- 对比：使用相同维度对齐两侧内容。
- 数据：保留数值、单位、排序、比例方向和来源注释；不得捏造刻度或趋势。

## 文本门禁

生成前建立逐字文本清单。标题、姓名、日期、数量、单位、步骤名和来源说明必须从输入复制。长段落先在图片外压缩为短句，再进入清单。图片中不得要求模型自行总结或补词。

逐字清单只保留必须在图中出现的内容；每条只出现一次。若压缩后仍不可读，增加页数而不是把正文缩成脚注。

## 芽仔集成

- 每页一个主要小芽仔，或在时间线、连续阶段中最多出现 3 个小芽仔。
- 每次出现都必须帮助理解：指向趋势、检查证据、沿路径移动、演示步骤、比较选择、警告或完成。
- 保留固定宇航服和身份特征；只改变姿势和情境道具，不给芽仔随意换成人类服装。
- 芽仔通常占页面视觉重量 8%–18%，不得压住标题、数据、节点或路径。
- 芽仔与信息物件共享细墨线、局部排线、克制印刷颗粒和浅剪纸阴影；空白背景保持均匀浅色，禁止光滑 3D 玩偶质感。
- 小尺寸芽仔也保留单侧反光来表现曲面：使用同一受光侧的一块短而宽的连续弧面。禁止另一侧光点、孤立圆点、左右成对亮线和八字眉。

## 蓝色焦点系统

- 每页有且只有一个第一眼可见的主蓝色语义焦点，必须承载核心命题、关键步骤、结论、异常值或最重要数据。
- 主焦点可使用蓝色撕纸块、墨块、标记带、关键物件或图表主数据，必要时配暖白手写字。
- 再使用 2–4 个小蓝色强调连接编号、路径、圈注或次级数据。
- 高饱和蓝色总面积通常为 8%–15%；禁止整页蓝底、蓝色卡片墙或所有模块同等变蓝。
- 缩略图测试中，读者应在一秒内指出蓝色强调的核心信息；若只能看到蓝线，页面失败。

## 参考图

使用 assets/examples/paper-blue/03-information-visualization-3x4-v2.png 作为浅纸编辑线描画风、手绘路径和高信息密度的第一风格母版。只学习视觉语言，不复制示例步骤、文字、构图或芽仔动作。

如需额外的信息架构参考，只能使用已经核实来源并完成脱敏的材料。不得把包含个人账号、私密界面、未经证实的数据、Logo 或品牌截图的旧案例打包进公开 Skill。

## 提示词骨架

    Use case: infographic-diagram
    Asset type: {16:9 / 4:3 / 3:4} Chinese information visualization

    Input images:
    - Image 1: Yazai identity reference. Preserve identity, proportions and fixed colors; do not copy its heavy background texture.
    - Image 2: light-paper information-visualization style master. This image controls the medium: pale clean background, editorial ink drawing, object-local hatching, handmade paths and high information density. Do not copy its steps or layout.
    - Image 3: optional sanitized information-architecture reference only. Do not copy its content, brand, palette or character.

    Primary request:
    Visualize this logic accurately: {主题}.

    Page goal:
    {一个沟通任务}

    Layout:
    {总览 / 流程 / 时间线 / 对比 / 数据故事 / 证据案例 / 清单 / 结论}

    Logic:
    - Reading start: {起点}
    - Reading direction: {方向}
    - Required nodes in order: {节点1} -> {节点2} -> {节点3} -> {其余节点}
    - Relationship type: {步骤 / 因果 / 依赖 / 分支 / 循环 / 时间 / 对比 / 数据}
    - Exact direction, condition, axis or scale rules: {规则}

    Composition:
    Make the logic path dominant. Use individually hand-drawn nodes, arrows, annotations and restrained paper layers. Keep one obvious reading route. Place Yazai at {位置}, {动作}, occupying about 8%-18% of the page without covering information. Render Yazai with the same fine ink line, object-local hatching, restrained print grain and shallow shadow as the information objects. Keep exposed background areas clean.

    Visual system:
    Clean light-warm paper canvas, default #F6EFDC within #F4EDDD–#F8F1E0, with almost invisible fine fibers and no full-canvas texture pattern. Use deep-ink handwritten Chinese, editorial outlines, object-local cross-hatching, visibly handmade arrows and irregular borders, clean information surfaces and restrained tactile depth. Use exactly one obvious #0138C4 semantic focal anchor carrying {核心命题/关键步骤/结论/关键数据}, plus only 2–4 smaller blue accents for path, numbering or annotation. The main blue anchor must be more visually prominent than the blue lines.

    Yazai visor:
    Keep a one-sided curved reflection to give every visor volume. Choose one light-facing side from each Yazai pose; place one contiguous broad soft crescent/oval highlight there, with tonal falloff only on that same side. No isolated dot or bright mark on the opposite side. For small Yazai, use one shorter, wider crescent; never remove the reflection entirely.

    Render this text exactly, with no extra words:
    {逐字文本清单}

    Constraints:
    Preserve all facts, dates, values, units, names, order and relationships. Split content rather than shrinking text.

    Avoid:
    Invented facts, wrong sequence, decorative arrows, equal card wall, digital-font perfection, large blue backgrounds, heavy full-canvas paper texture, embossed swirls, cloudy stains, background hatching, glossy or 3D Yazai, second visor glint, isolated visor dot, opposite-side visor line, paired visor highlights, eyes or eyebrows, fake UI, unrelated mascot scene, logo, watermark.

## 修复优先级

先修事实和关系，再修文字，然后修蓝色焦点与阅读层级，最后修风格。逐页生成和验收；只重生成失败页面，保留已通过页面。
