# AI 应用原型项目集

这里收录我独立设计和实现的 AI 与产品原型项目。

项目聚焦真实用户需求、交互体验与可解释的本地规则逻辑。

## 项目导航

| 项目 | 在线体验 | 源码与说明 |
| --- | --- | --- |
| MindfulSelect · 穿搭偏好推荐 | [打开在线 Demo](https://aurora2028.github.io/vibe-coding/mindfulselect/) | [查看源码](https://github.com/aurora2028/vibe-coding/tree/main/mindfulselect) |
| IELTS Speaking Agent · 雅思口语陪练 | [打开在线 Demo](https://aurora2028.github.io/vibe-coding/ielts-speaking-agent/) | [查看源码](https://github.com/aurora2028/vibe-coding/tree/main/ielts-speaking-agent) |

---

## 1. MindfulSelect · 穿搭偏好推荐

一个面向通勤女装场景的偏好驱动推荐原型。

### 项目背景

用户在购物平台中反复修改搜索词后，仍可能看到重复店铺、不喜欢的款式或难以理解的推荐结果。MindfulSelect 让用户主动表达穿搭偏好，并通过收藏与负反馈不断调整推荐。

### 核心功能

- 模糊搜索后进入 `Help Me Choose` 选款流程；
- 保存裙长、场合、颜色与版型偏好；
- 收藏商品时补充喜欢的特征；
- 区分不同“不感兴趣”原因；
- 通过本地规则重新排序推荐结果；
- 使用浏览器 localStorage 保存偏好，无需 API。

[打开 MindfulSelect 在线 Demo →](https://aurora2028.github.io/vibe-coding/mindfulselect/)

---

## 2. IELTS Speaking Agent · 雅思口语陪练

一个帮助用户进行雅思口语练习与反馈的交互式原型。

### 项目目标

帮助用户围绕雅思口语题目完成表达练习，并获得结构化反馈，降低独自练习时“不知道说什么、无法判断表达是否合适”的门槛。

### 核心功能

- 雅思口语题目展示；
- 模拟口语练习流程；
- 针对表达内容提供反馈；
- 帮助用户梳理表达结构与改进方向。

[打开 IELTS Speaking Agent 在线 Demo →](https://aurora2028.github.io/vibe-coding/ielts-speaking-agent/)

---

## 项目说明

- 本仓库中的项目均为个人作品集原型；
- 演示数据与内容仅用于展示产品设计和交互逻辑；
- 不包含真实用户数据或商业平台数据。
