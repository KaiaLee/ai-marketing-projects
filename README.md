# ai-marketing-projects / 行銷 AI 作品集

A collection of AI-driven marketing tools and experiments.  
由 AI 技術驅動的行銷工具與實驗作品集。

---

## 📋 Portfolio Overview / 作品集規劃總覽

| 專案編號 | 專案名稱                     | 重點技能                                      | 展示平台建議                                  |
|--------|--------------------------|-------------------------------------------|------------------------------------------|
| ①     | AI 數據儀表板                 | 數據分析 + 視覺化 + AI 洞察生成                   | GitHub + Looker Studio / Streamlit       |
| ②     | AI 報告自動生成器              | ChatGPT API + 自動摘要 + 報告產出                | GitHub + Notion / PDF demo               |
| ③     | 客服問答機器人                | ChatGPT + Web UI + FAQ 資料庫                  | GitHub + Streamlit / Gradio              |
| ④     | AI 行銷文案 & 圖像生成器        | GPT + DALL·E / Midjourney + UX flow         | GitHub + 可用網頁 demo                   |
| ⑤     | Excel + AI 智能預測助手        | Excel + GPT API + 自動推薦                    | GitHub + Google Sheets demo              |

---

# 📊 Project ① - AI Marketing Dashboard

## 🎯 Project Introduction / 專案簡介

An AI-powered dashboard for automatically analyzing Facebook Ads data and generating visual reports & insights.  
一個用於自動分析 Facebook 廣告數據、產出圖表和行銷洞察的 AI 儀表板。

---

## 🔧 Tech Stack / 使用工具

- **Google Sheets/CSV** – 模擬廣告數據
- **Pandas** – 數據分析
- **Looker Studio/Plotly / Altair*** – 圖表視覺化
- **GPT-4** – 生成洞察、分析
- **Streamlit** – 介面展示


---

## 🧠 Core Features / 核心功能

- 📥 自動讀取資料 / Auto data fetching  
- 📊 生成週報 / 月報的行銷洞察 / Weekly & monthly insight generation  
- 🖼️ 將文字轉為視覺圖表 / Convert AI text insights into visual dashboards

---

## 📷 Screenshots / 專案畫面

![dashboard screenshot](screenshots/dashboard.png)

---

## 🚀 Live Demo / 線上展示

👉 [Click here to try the demo](https://xxxx.streamlit.app)  
👉 [點我試用 Demo](https://xxxx.streamlit.app)

---

## 📝 Prompt Sample / Prompt 設計樣本

```prompt
你是一個行銷分析師，請根據以下表格資料，分析哪個廣告組表現最好，並提供優化建議。


## 💡 Future Improvements / 未來規劃

整合 Google Analytics 或 GA4 數據
加入自然語言查詢功能（如：用語音詢問「哪一組表現最好？」）
多平台報表整合（Meta、Google Ads、TikTok Ads）

## 📄 License / 授權條款

