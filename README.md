# 🇨🇳 China Open Brand Intelligence Dataset

### 中国品牌商业智能开放数据集

<p align="center">
  <img width="80" height="80" alt="10190d9e93dca760dc9adf714edbf541" src="https://github.com/user-attachments/assets/1f8e3cfe-60a7-4f84-947b-7080313dd34b" />
</p>

<p align="center">
Open Brand Intelligence Dataset for AI, Commercial Analysis and Location Intelligence
</p>

<p align="center">
面向 AI、商业分析与智能选址的品牌商业智能开放数据集
</p>

---

## 🎯 What Is This?

China Open Brand Intelligence Dataset is an open commercial knowledge base containing nationwide brand information, store scale, city coverage and industry taxonomy.

It is designed for developers, researchers and AI builders who want to build commercial intelligence applications, market research tools and AI agents.
Containing brand basic info with over 10 stores nationwide. 

中国品牌商业智能开放数据集是一套面向开发者、研究人员和 AI 创业者的商业知识库。

数据集包含全国品牌信息、门店规模、城市覆盖、品牌客单价和业态分类等核心商业数据，可用于构建竞品分析、市场研究、智能选址和商业分析 Agent 等应用。
收录全国门店超过10家的品牌基础信息

---

## 📊 Dataset Scale | 数据规模

| Metric                    | Scale      |
| ------------------------- | ---------- |
| 🏢 Brands 品牌              | 45,000+    |
| 🏬 Stores 门店              | 5,000,000+ |
| 🌍 Cities 城市              | 334+       |
| 🗂 Industry Taxonomy 业态分类 | 3-Level    |
| 🖼 Brand Logos 品牌Logo     | Included   |
| 💰 Average Spending 客单价   | Included   |
| 🤖 AI Ready Dataset       | Yes        |

---

## 🚀 Why This Dataset? | 为什么开源这份数据？

Most AI applications have access to models.

Very few have access to structured commercial intelligence.

大多数 AI 项目拥有模型。

但很少拥有高质量、结构化的商业知识库。

This dataset provides nationwide brand intelligence data that can serve as the foundation for commercial AI applications.

本数据集开放了全国品牌商业智能数据，可作为商业智能应用和 AI Agent 的基础知识库。

---

## 💡 What Can You Build? | 你可以构建什么？

### 🏆 Competitive Intelligence | 竞品分析

Analyze market leaders and category competition.

分析行业头部品牌与竞争格局。

Examples:

* Top Coffee Brands in China
* Top Tea Brands in China
* Category Concentration Analysis
* Brand Expansion Benchmarking

例如：

* 全国咖啡品牌排行榜
* 全国茶饮品牌排行榜
* 行业集中度分析
* 品牌扩张能力分析

---

### 📍 AI Site Selection Agent | AI选址Agent

Learn how successful brands expand across cities.

学习头部品牌的扩张路径与覆盖策略。

Examples:

* Brand Expansion Pattern Analysis
* Market Opportunity Discovery
* Category Penetration Analysis
* Site Selection Recommendation

例如：

* 品牌扩张路径分析
* 市场机会发现
* 城市渗透率分析
* 智能选址推荐

---

### 🤖 Commercial Intelligence Agent | 商业分析Agent

Build AI systems capable of answering business questions.

构建具备商业分析能力的 AI Agent。

Examples:

> Which coffee brands cover the most cities?

> What are the leading brands in this category?

> Which restaurant chains are expanding fastest?

例如：

> 哪些咖啡品牌覆盖城市最多？

> 某个业态的头部品牌有哪些？

> 哪些连锁品牌扩张最快？

---

### 📈 Market Research | 市场调研

Generate industry reports and category insights.

用于行业研究与市场分析。

Examples:

* Industry Landscape Analysis
* Brand Benchmarking
* Market Opportunity Research

例如：

* 行业格局分析
* 品牌对标研究
* 市场机会分析

---

### 🗺 Location Intelligence | 地理商业智能

Build maps, dashboards and commercial discovery tools.

构建商业地图、分析看板和地理智能应用。

Examples:

* Brand Distribution Maps
* Industry Heatmaps
* Regional Market Analysis

例如：

* 品牌分布地图
* 行业热力图
* 区域市场分析

---

## 📦 What's Included? | 数据内容

The dataset contains nationwide brand intelligence information.

数据集包含全国品牌商业智能信息。

| Field                   | Description |
| ----------------------- | ----------- |
| brand_id                | 品牌ID        |
| brand_name              | 品牌名称        |
| category_id             | 业态ID        |
| category_name           | 业态名称        |
| store_count             | 门店数量        |
| over_city_count         | 覆盖城市数量      |
| brand_sam_category_rank | 同业态排名       |
| brand_logo              | 品牌Logo      |
| establish_date          | 成立时间        |
| avg_price               | 客单价         |

---

## 📂 Repository Structure | 仓库结构

```text
china-open-brand-dataset
│
├── brand.csv
├── README.md
└── LICENSE
```

---

## 🗄 Dataset Structure | 数据结构

```text
brand.csv

├── brand_id
├── brand_name
├── category_id
├── category_name
├── store_count
├── over_city_count
├── brand_sam_category_rank
├── brand_logo
├── establish_date
└── avg_price
```

---

## ⚡ Quick Start | 快速开始

### Python

```python
import pandas as pd

brand = pd.read_csv("brand.csv")

print(brand.head())
```

### Example Analysis | 示例分析

```python
top_brand = (
    brand
    .sort_values("store_count", ascending=False)
    .head(10)
)

print(top_brand[["brand_name", "store_count"]])
```

Find the largest brands in China.

快速查看全国门店规模最大的品牌。

---

## 🌟 Why We Open Sourced This Dataset | 为什么开源？

High-quality commercial datasets are difficult to access.

We hope this dataset helps developers, researchers and AI builders create better commercial intelligence applications.

高质量商业数据长期存在获取门槛。

我们希望通过开放部分数据资产，帮助开发者、研究人员和 AI 创业者构建更优秀的商业智能产品。

---

## 🏢 About Jike Big Data | 关于及刻大数据

This repository contains only a small subset of Jike's commercial intelligence platform.

本仓库仅开放了及刻商业智能平台中的部分品牌数据。

Beyond this dataset, Jike also provides:

除本项目外，及刻还提供：

* Nationwide POI Database（全国POI数据库）
* Store-Level Intelligence（门店级数据）
* Population Mobility Data（人口流动数据）
* Commercial District Analysis（商圈分析）
* Site Selection Intelligence（智能选址）
* Commercial Intelligence API（开放API）
* AI Business Analysis（AI商业分析）

---

## 📬 Contact | 联系我们

🌐 Website

https://www.isjke.com

📧 Email

[data@clickwifi.net](mailto:data@clickwifi.net)

⭐ If this dataset helps your project, please give us a Star.

如果本项目对您有所帮助，欢迎 Star ⭐。

For richer datasets, APIs and commercial cooperation, feel free to contact us.

如需更丰富的数据资产、开放 API 或商业合作，欢迎联系我们。

---

Built with ❤️ by Jike Big Data

让商业决策更简单。
