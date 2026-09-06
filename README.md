# Showcase · 工程作品集

个人工程与作品的可视化统一展示索引。纯前端静态 HTML，本地双击 `index.html` 即可浏览全部分支页面，无需构建、无需依赖。

## 包含什么

- **索引首页**：统一入口，卡片式跳转到每个可视化工程
- **业务工程 ×4**：面向业务价值的工程展示（私有化知识问答 / 智能客服 / 数据脱敏 / AI 运维工程）
- **方法论工程 ×5**：Harness 编排方法论、数字员工大脑、多智能体编排等工程的可视化

## 工程清单

| 入口 | 类型 | 说明 |
|---|---|---|
| 索引首页 `index.html` | 总览 | 全部展示资产的统一入口 |
| `企业私有化知识平台-可视化工程.html` | 业务工程 | RAG 知识平台工程展示：问答链路、检索优化、评测驱动 |
| `智答客-可视化工程.html` | 业务工程 | IM 智能客服产品工程展示 |
| `文档脱敏工具-可视化工程.html` | 业务工程 | 敏感信息识别与脱敏工程展示 |
| `AI运维工程-可视化工程.html` | 业务工程 | AI 驱动的交付运维工程展示 |
| `harness-team-visual/` | 方法论工程 | Harness 多 Agent 团队编排方法论可视化 |
| `fde-brain-visual/` | 方法论工程 | 数字员工大脑 · 前沿部署工程师（FDE） |
| `ensemble-visual/` | 方法论工程 | 合奏体系：多智能体编排 ·「一个人，也可以是一支乐团」 |
| `skill-flow-viz/` | 方法论工程 | Skill 工程可视化 → 独立公开仓库，[在线浏览](https://siyuanjun.github.io/skill-flow-viz/) |
| `ontology-brain-visual/` | 方法论工程 | 本体工程师数字员工 → 独立公开仓库，[在线浏览](https://siyuanjun.github.io/ontology-brain-visual/) |

## 使用方式

```bash
git clone git@github.com:siYuanJun/showcase.git
cd showcase
open index.html
```

## 说明

- 目录内 `skill-flow-viz` 与 `ontology-brain-visual` 为两个独立公开仓库的线上展示入口，本仓库索引页直接跳转其 GitHub Pages 地址，不在本仓库内重复维护源码
- 所有页面为纯静态 HTML，可直接本地打开或托管至任意静态站点服务
