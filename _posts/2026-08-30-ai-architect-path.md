---
layout: post
title: "我的 AI 架構師之路"
date: 2026-08-30
categories: [AI, Career]
tags: [AI-Architect, AI-901, AIF-C01, LLM, RAG, MLOps]
---

![通往 AI 架構師之路：六張證照從基礎到企業架構的學習地圖]({{ '/assets/images/ai-architect-roadmap.jpg' | relative_url }})

*六張證照的學習地圖：從 AI 基礎、AWS AI、AI 應用與 Agent、ML 工程，到多雲 ML 架構與企業級雲端架構。*

# 我的 AI 架構師之路

先給自己 12～15 個月，六張證照，一路做、一路學。

做軟體這麼多年，從桌面程式、Web、Mobile、Cloud 一路走到 AI。這幾年最大的感受是：AI 不只是一批新的開發工具，它正在改變整個軟體系統的設計方式。

以前想的是資料庫怎麼設計、API 怎麼切、系統怎麼部署。現在多了：

- **LLM**（Large Language Model，大型語言模型）：用來理解與生成文字
- **RAG**（Retrieval-Augmented Generation，檢索增強生成）：讓模型先查資料再回答
- **Agent**（代理程式）：可自行呼叫工具完成任務
- **Vector Database**（向量資料庫）：儲存語意向量以供相似度檢索
- **MLOps**（Machine Learning Operations，機器學習維運）：負責模型部署、監控與更新

還要一併考慮模型成本、安全性與資料權限。

所以我替自己訂了新的方向：**往 AI Solution Architect（AI 解決方案架構師）走**。目前規劃六張證照，預計 12～15 個月完成；順序刻意從簡單的開始，再進到應用開發、ML 工程與 Cloud Architecture（雲端架構）。

## 我規劃的六張證照

| 順序 | 證照 | 預計準備 | 難度 | 專業度 | 含金量 |
|---|---|---|---|---|---|
| 1 | Microsoft Azure AI Fundamentals（AI-901） | 1～2 週 | ★★☆☆☆ | ★★☆☆☆ | ★★☆☆☆ |
| 2 | AWS Certified AI Practitioner（AIF-C01） | 2～4 週 | ★★☆☆☆ | ★★★☆☆ | ★★★☆☆ |
| 3 | Microsoft AI Apps & Agents Developer Associate | 1.5～2 個月 | ★★★☆☆ | ★★★★☆ | ★★★★☆ |
| 4 | AWS Machine Learning Engineer – Associate | 2～3 個月 | ★★★★☆ | ★★★★☆ | ★★★★☆ |
| 5 | Google Professional Machine Learning Engineer | 2.5～3 個月 | ★★★★★ | ★★★★★ | ★★★★★ |
| 6 | AWS Solutions Architect – Professional | 3～4 個月 | ★★★★★ | ★★★★★ | ★★★★★ |

星等不是官方評分。「難度」是我預估的準備與通過門檻，「專業度」是證照涉及的技術深度，「含金量」則偏向它放在 AI／Cloud 履歷上的辨識度。

## 為什麼是這個順序

**1. AI-901：先打地基。** 平常在用 LLM 和 API，很容易以為自己都懂了，但「用過」和「有系統地理解」是兩回事。第一張刻意選簡單的，把零散的 AI 知識重新整理一次。作者考試時間：2026-09-15。

**2. AIF-C01：換一個雲再看一次。** 同一件事在 AWS 有不同的產品名稱和做法，但底層觀念相同。只熟一家廠商，遇到問題的第一反應會是「要用哪個產品」；架構師該先問的是「這個問題需要什麼樣的架構」。

**3. Microsoft AI Apps & Agents Developer：開始真的做系統。** 呼叫 LLM API 不難，難的是把 AI 放進系統：怎麼取得公司資料、怎麼呼叫既有 API、哪些事可以讓 Agent 自己做、哪些一定要人確認、權限怎麼處理、答錯了怎麼辦。

**4. AWS Machine Learning Engineer：補 ML 工程與 MLOps。** 企業裡仍有大量傳統 Machine Learning（機器學習）需求，而且到了 Production（正式環境），問題往往不只是模型準不準，還有部署、資料管線、版本更新、效能監控與成本控制。

**5. Google Professional ML Engineer：把產品和架構分開。** 三家雲都碰過之後，重點不是三套 Console 怎麼操作，而是看穿三個名字不同的服務其實在解同一類問題。工程師問「怎麼做」，架構師還要問「為什麼這樣做、有沒有別的選擇、代價是什麼」。

**6. AWS Solutions Architect – Professional：回到架構本身。** 最後一張刻意不是 AI 證照，因為 AI 架構師首先還是架構師。導入 AI 不會讓 Database、Network、Security、IAM（Identity and Access Management，身分與存取管理）、擴充性、備援與成本消失，反而更複雜。

## 準備 AIF-C01 的時候，順手做了這個 App

這原本不在計畫裡。準備 AIF-C01 時找了不少教材和題庫，用一陣子之後總覺得少了點什麼。我不想只是一直刷題：答錯時更想知道為什麼錯，有些題目答對其實只是剛好猜到。

另一個問題是時間。真正能坐在桌前念書的時間有限，但走路、搭車、休息的零碎時間其實不少。既然自己就是做軟體的，乾脆寫一個自己想用的版本。

第一版從 AIF-C01 開始，把準備期規劃成 14 天，每天知道要讀到哪裡，而不是打開幾百題的題庫一直往下做；再加上 Audio Learning（語音學習），走路或搭車就能複習。目前提供 English、日本語、한국어、中文、Español 與 Português (Brasil) 等語言版本。

## 整體時間：12～15 個月

| 證照 | 準備時間 | 累計進度 |
|---|---|---|
| Microsoft AI-901 | 1～2 週 | 第 1 個月 |
| AWS AIF-C01 | 2～4 週 | 第 1～2 個月 |
| Microsoft AI Apps & Agents Developer | 1.5～2 個月 | 第 2～4 個月 |
| AWS Machine Learning Engineer | 2～3 個月 | 第 4～7 個月 |
| Google Professional ML Engineer | 2.5～3 個月 | 第 7～10 個月 |
| AWS Solutions Architect Professional | 3～4 個月 | 第 10～15 個月 |

工作、開發和生活還是要繼續。**12～15 個月是目標，不是死線。** 某一段需要多花時間，我寧可多做一些實際的東西，也不想只為了趕日期把題庫背完。

## 證照不是最後的目的

考證照是因為它能幫我整理學習範圍，給自己明確的階段目標。但拿到六張證照不等於成為 AI 架構師——如果一年後只有六張證照可以放在 LinkedIn 上，卻沒真正做過 AI 系統，那這一年就沒達到我要的效果。

所以我給自己另一個要求：**每完成一個階段，至少留下一個可以實際展示的成果。** 可能是一個 App、一套 Agent、一個 RAG 系統、一條 ML Pipeline（機器學習流程），也可能是一份完整的架構設計。證照讓我知道該學什麼，實作才會讓我知道自己到底會不會。

## 為什麼是 AI 架構師

我的興趣不是變成只做模型研究的人，而是：怎麼把 AI 接進原本的軟體、怎麼讓 Agent 和既有系統合作、資料怎麼處理、怎麼部署與擴充、成本怎麼控制、安全怎麼確保，最後怎麼組成一套真的有人能用、公司敢上線的系統。

<div class="stack">
<p>Software Engineering（軟體工程）</p>
<p>＋ AI / ML（人工智慧與機器學習）</p>
<p>＋ Generative AI / Agent（生成式 AI 與代理程式）</p>
<p>＋ MLOps（機器學習維運）</p>
<p>＋ Cloud Architecture（雲端架構）</p>
<p><strong>＝ AI Solution Architect（AI 解決方案架構師）</strong></p>
</div>

先給自己 12～15 個月，六張證照，一路做、一路學，也一路把過程記錄下來。
