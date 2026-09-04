# REAL FOOD STUDIO

> **好菜，不该输给照片。**

REAL FOOD STUDIO 是一个面向真实餐饮菜品的商业影像 Skill。

它不是重新生成一道更漂亮的“AI 菜”，而是优先保留真实菜品事实，再优化摄影表现。

**REAL FOOD, BETTER PHOTOGRAPHY.**

---

## What is REAL FOOD STUDIO?

REAL FOOD STUDIO is a commercial food photography system designed for real restaurant dishes.

它首先保留真实菜品的食材、份量、状态、摆盘与出品事实，再重新处理灯光、环境、构图、色彩与摄影质感。

核心标准：

## REAL 95

**95% 真实菜品事实**  
**5% 专业摄影优化**

> 可以把照片做得更好，但不能把菜做成另一道菜。

优先级：

**真实性 > 食欲感 > 精致度 > 视觉冲击**

---

## Quick Start

安装后调用：

```text
$real-food-studio
```

最简单的使用方式：

```text
$real-food-studio

帮我修一下这道菜。
```

推荐调用方式：

```text
$real-food-studio

处理这张真实菜品原图。

用途：美团菜单
模式：REAL 95
风格：真实、自然、有食欲

要求：
- 不改变食材
- 不改变份量
- 不重新设计摆盘
- 不制造虚假食物
- 优化灯光、环境、构图和摄影质感
```

---

## REAL 95

### 默认锁定

- 菜品类型
- 核心食材
- 食材数量关系
- 份量
- 熟度
- 切法与形状
- 摆盘
- 装饰
- 酱汁位置
- 食物真实纹理
- 核心器皿

### 允许优化

- 光线
- 曝光
- 白平衡
- 色彩
- 构图
- 景深
- 背景
- 环境
- 器皿清洁
- 摄影质感
- 平台适配

### 默认禁止

- 增加或删除核心食材
- 改变份量
- 改变熟度
- 改变切法
- 重新设计摆盘
- 制造虚假油亮
- 过度饱和
- AI 塑料质感
- 凭空增加火焰、蒸汽、配料
- 大面积重构菜品

---

## KEEP / REPAIR / REBUILD

### KEEP
保留可用环境，仅做摄影优化。

### REPAIR
环境可以使用，但需要清洁、修复或整理。

### REBUILD
锁定菜品和器皿，仅重建摄影环境。

规则：

> 能修就不换，能换环境就不动菜。

---

## Subject Gate

默认：

**1 HERO DISH + ≤2 SUPPORTING FOOD OBJECTS**

食物对象总数最多 3 个。

如果出现 4 个或更多食物对象，则进入 FOCUS MODE，不会擅自删除菜品。

---

## Plate Hygiene

> **CLEAN THE PLATE, NOT THE FOOD.**

可清理：指纹、水渍、污渍、盘沿意外油污、非菜品本身的杂物。

必须保留：酱汁、汤汁、辣椒、葱花、油脂、菜品装饰、食物本身。

---

## Frame Recovery

优先顺序：

**扩背景 > 补器皿 > 少量补食物边缘 > 禁止大面积重构菜品**

缺失食物边缘处理建议：

- <10–15%：谨慎补全
- 15–30%：优先裁切 / 重构画面
- >30%：默认不补食物

> When uncertain, crop — don’t invent.

---

## Scene System

Chinese Food Engine V1 支持以下摄影语言：

1. BRIGHT COMMERCIAL
2. NEUTRAL STUDIO
3. DARK APPETITE
4. WARM DINING
5. FIRE & STEAM
6. INGREDIENT STORY
7. MOUNTAIN & NATURE
8. EDITORIAL FOOD

场景选择参考：

- 70% FOOD CHARACTER
- 20% USAGE
- 10% CULTURAL CUE

规则：

> Chinese Food ≠ Chinese Props.

避免默认堆叠传统中式道具。

---

## Usage Examples

### Example 01 — 简单处理

```text
$real-food-studio

帮我修一下。
```

### Example 02 — 外卖平台

```text
$real-food-studio

这张做外卖平台用。
保持真实菜品不变，让主体更清楚、更有食欲，背景干净一些。
REAL 95。
```

### Example 03 — 菜单

```text
$real-food-studio

菜单用。
不要换菜，不要改变份量和摆盘。
优化灯光、色彩、构图和摄影质感，做成专业餐饮菜单摄影。
```

### Example 04 — 深色食欲摄影

```text
$real-food-studio

这道菜做深色食欲摄影。
保持原菜完全可识别，背景可以重新处理，菜品本身保持 REAL 95。
不要过度油亮，不要高饱和，不要 AI 感。
```

### Example 05 — 菜品视觉诊断

```text
$real-food-studio

先不要直接处理。
分析这张照片：
1. 可以直接救
2. 建议补拍
3. 建议重新拍
告诉我原因。
如果可以直接救，再按照 REAL 95 处理。
```

---

## Final Reality Check

每张最终结果都要回答：

> 顾客看到照片后，再看到真实菜品，会不会觉得图片与实物不是同一道菜？

如果答案是“会”，则回退处理。

验收：

**YES → REAL 95 PASS**  
**NO → REJECT**

---

## Brand System

- Brand: **REAL FOOD STUDIO**
- Skill: **`$real-food-studio`**
- Standard: **REAL 95**
- Engine: **Chinese Food Engine V1**
- Brand Statement: **好菜，不该输给照片。**
