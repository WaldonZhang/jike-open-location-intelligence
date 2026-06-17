# 🇨🇳 China Open Brand Intelligence Dataset

# 🇨🇳 中国品牌商业智能开放数据集

![banner](./assets/banner.png)

An open-source brand intelligence dataset powered by Jike Big Data.

由及刻大数据提供的品牌商业智能开放数据集。

---

🏢 13,000+ Brands 品牌
🏬 5,000,000+ Stores 门店
🌍 334+ Cities 城市
🗂 3-Level Industry Taxonomy 业态分类
🤖 AI Ready Dataset AI适配的数据库

---

# 🚀 Overview | 项目简介

This repository contains a subset of Jike's commercial intelligence data assets, designed for developers, data analysts, AI engineers, and researchers building:

* AI Agents
* Location Intelligence Applications
* Site Selection Systems
* Commercial Analysis Platforms
* Geo-RAG Applications
* Business Recommendation Systems

本仓库开源了及刻大数据部分品牌商业智能数据资产，帮助开发者、数据分析师和 AI 工程师快速构建：

* AI Agent
* 智能选址系统
* 商业分析平台
* 地理智能应用
* 商业推荐系统
* Geo-RAG 应用

---

# 📊 Dataset Highlights | 数据亮点

| Metric               | Description |
| -------------------- | ----------- |
| 🏢 Nationwide Brands | 全国品牌基础信息    |
| 🏬 Store Count       | 品牌门店数量      |
| 🖼 Brand Logos       | 品牌 Logo     |
| 🌍 City Coverage     | 品牌覆盖城市数量    |
| 💰 Average Spending  | 品牌客单价       |
| 🗂 3-Level Taxonomy  | 品牌三级业态分类    |

---

# 📦 Dataset Structure | 数据结构

```text
brands.csv
├── brand_id
├── brand_name
├── category_id
├── category_name
├── store_count
├── over_city_count
├── brand_sam_category_rank
├── brand_logoc
├── establish_date
└── avr_price


```

---

# 🌟 Example Data | 示例数据

| Brand         | Store Count | Cities | Avg Price | Category |
| ------------- | ----------- | ------ | --------- | -------- |
| Starbucks     | 7000+       | 300+   | ¥35       | Coffee   |
| Haidilao      | 1400+       | 200+   | ¥110      | Hotpot   |
| Luckin Coffee | 20000+      | 300+   | ¥18       | Coffee   |

---

# 💡 Use Cases | 应用场景

## 🤖 AI Agent

* Commercial Intelligence Agent
* Site Selection Agent
* Recommendation Agent

## 📈 Business Intelligence

* Industry Analysis
* Brand Analysis
* Competitive Analysis

## 🌍 Location Intelligence

* Market Research
* Business Distribution Analysis
* Commercial Opportunity Discovery

---

# 📂 Repository Structure | 仓库结构

```text
dataset/
├── brands.csv
├── brands.json
├── categories.csv
└── metadata.json

examples/
├── python_demo.py
├── sql_demo.sql
└── notebook.ipynb

docs/
└── data_dictionary.md
```

---

# 🚀 Quick Start | 快速开始

```python
import pandas as pd

brands = pd.read_csv("dataset/brands.csv")
print(brands.head())
```

---

# ❤️ About the Dataset | 关于数据

This repository only contains a subset of Jike's commercial intelligence data assets.

本仓库仅开源了及刻大数据部分商业智能数据资产。

Jike provides significantly richer commercial intelligence capabilities, including:

* Nationwide POI Database
* Brand Intelligence Database
* Store-Level Information
* Commercial District Analysis
* Consumer Insights
* Population Mobility Data
* Site Selection Intelligence
* AI Commercial Analysis

及刻拥有更加丰富的商业数据能力，包括但不限于：

* 全国 POI 数据库
* 品牌数据库
* 门店级信息
* 商圈分析数据
* 消费洞察数据
* 人口流动数据
* 智能选址数据
* AI 商业分析能力

---

# 📬 Contact Us | 联系我们

Website：
[www.isjke.com](http://www.isjke.com)

Official Website：
https://www.isjke.com

Email：
[data@clickwifi.net](mailto:data@clickwifi.net)

If this dataset is useful to your project, please give us a ⭐.

For commercial cooperation, data services, or API access, please contact us.

如果本项目对您有所帮助，欢迎 Star ⭐。

如果您希望获取更多商业数据、开放 API 或开展商业合作，欢迎联系我们。

---

# 🏢 About Jike | 关于及刻

Jike is an AI-powered location intelligence company dedicated to making commercial decision-making easier through data and AI.

及刻是一家专注于 AI 与商业地理智能的科技公司，致力于通过数据和人工智能让商业决策更加简单。

Powered by Jike Big Data.
