---
layout: page
title: 關於
hide_title: true
lang: zh
ref: about
---

你好！我是 Lai-YT :smile:

我之前主要在做圖形處理器（GPU）架構和編譯器最佳化，特別關注執行緒束（warp）層級的記憶體存取模式怎麼和圖形處理器的記憶體階層互動，尤其是第一級快取（L1 cache）。這些研究後來成為我的 [碩士論文](#master-thesis)，主題是透過編譯器來根據存取模式選擇合適的記憶體布局。一路做下來，我對傳統的 SIMT 執行模型和圖形處理器效能分析也算相當熟悉。

現在，我把重心轉向大語言模型（LLM）。現今的圖形處理器加入了越來越多專門硬體[^specialized-hardware]和非同步執行機制，它們在大語言模型的運算裡不可或缺。我想進一步了解這些新的執行模型，以及如何利用它們來最佳化大語言模型的運算。我也對相關的軟硬體協同設計有興趣。

[^specialized-hardware]: 例如，用來做高吞吐量矩陣運算的*張量核心*（tensor core），以及負責非同步資料搬移的*張量記憶體加速器*（TMA）。

## 興趣

- 咖啡 :coffee:
  - 喝酸的比較多
  - [咖啡評鑑](/zh/coffee-review.html)
- 書籍 :books:
  - [推薦書單](/zh/book-recommendations.html)
- 桌球 :ping_pong:
  - 球拍：_Nittaku Acoustic_（木吉他），正手：_XIOM Vega Pro_（Max），反手：_Nittaku Fastarc C-1_

## 其他

- <a id="master-thesis"></a>碩士論文：_基於編譯器導引之紋理硬體運用的圖形處理器執行緒束內快取利用率提升技術_
  - [論文](/assets/files/yi-ting-lai-master-thesis.pdf) (英文，158 頁)[^online-thesis]
  - [投影片](/assets/files/yi-ting-lai-master-thesis-slides.pdf)（英文）
- [簡歷](/assets/files/resume.pdf)（英文）:page_with_curl:

[^online-thesis]: 本論文也收錄於 [國立陽明交通大學機構典藏](https://thesis.lib.nycu.edu.tw/items/67934d57-9254-4745-9f91-afdf6da70433)。典藏版本為雙面列印。

---
