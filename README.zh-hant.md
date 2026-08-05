<span align="center">
  
  <span lang="zh-hans">[简体中文](README.md)</span> | <span lang="zh-hant">繁體中文</span> | [English](README.en.md)
</span>

# CVIII：內容與呈現 AI 輔助指數
![CVIII-*1](https://img.shields.io/badge/CVIII-*1-D9A295)

> [!NOTE]
> <span lang="zh-hant">
> **注：** 當前方案為基於 IIIA 的修正案，僅供參考。  
> 本方案目前未被原作者正式採用，但原作者也未作出回應。如原作者對此做出回應，此方案將視情況更新。在本方案未廢止的情況下，若 IIIA 出現修訂更新，本方案將同步跟進。
> </div>

<div lang="zh-hant">
  
[「AI 參與指數」](https://github.com/ErSanSan233/IIIA)（Indice d'implication de l'intelligence artificielle, IIIA）曾嘗試提出一套區分網路影片中 AI 參與度的詳細等級標準，旨在説明影片創作者、觀眾以及相關行業人員清晰地界定和理解影片在製作過程中 AI 參與的程度。

這一標準的出現，為創作過程中人工智慧輔助參與程度的量化提供了可行性。然而，該理論仍存在一定漏洞，且該作者長期未能更新這一標準，故本人在 IIIA 基礎上稍加優化、完善，提出本方案。

「內容與呈現 AI 輔助指數」（Content and Visualization with Intelligence Involved Index, CVIII）將 AI（人工智慧）參與度的詳細等級標準適用範圍擴大到文章、影片等全體網路內容，旨在説明網路文章、影片創作者、讀者與觀眾以及相關行業人員清晰地界定和理解影片在製作過程中 AI 參與的程度。 

## 原始標準 IIIA 潛在問題 | Existing Bugs
IIIA 在制定時認為文案的 AI 成分和呈現效果的 AI 成分是一樣的，若兩者有差距，則取 AI 成分較大的部分作為整體指數。

但當核心內容與呈現方式的 AI 成分差異較大時，問題明顯暴露：一支影片由人工智慧編寫劇本（對應核心內容等級 4），但全部使用真人拍攝，一切素材也均為真人創作（對應內容呈現等級 0），按照原標準應填 4，但得出的結果容易引起「這部影片的實拍畫面『也是人工智慧生成的』」的誤解。

為此，本人在 IIIA 參考標準基礎上稍加優化、完善，對潛在問題進行深層考慮和修正，如果在使用 IIIA 標準時，如果因為遇到上述問題而不知所措，不妨嘗試使用本修正案。
  
## 等級介紹（簡略表格）| Simplified level table
當核心內容與內容呈現的 AI 成分差異不大時，或僅僅包含兩者中的一個，CVIII 等級可以僅由一位數構成，此時該數直接對應 AI 輔助參與情況，具體含義基本同 IIIA。

如：本修正案基於的原始參考標準 IIIA 僅僅涉及核心內容，而在內容呈現方面沒有明顯涉及 AI，基本保持原標準評級 `IIIA-1*`，故本方案的 CVIII 等級為 `CVIII-*1` 或其簡寫 `CV-*1`。

 | 分類 | 等級 | 含義 | 
 | ---------- | -------- | ------------------------------ | 
 | 未經 AI 製作 | 0        | 完全未使用 AI | 
 | 未經 AI 製作 | 1        | AI 僅提供參考，並未參與影片製作     | 
 | AI 參與制作  | 2        | 人類主導，AI用於提升效果            | 
 | AI 參與制作  | 3        | 人類審核和篩查過影片全部內容        | 
 | AI 參與制作  | 4        | 存在未經人類審核的內容              | 
 | 由 AI 製作   | 5        | 完全由 AI 製作                      | 
 | AI 主題      | \*       | 影片本身談論 AI，僅包含核心內容部分 | 
  
## 等級判定（詳細表格）| Detailed level table
若核心內容與內容呈現的等級差異過大，則 CVIII 的等級部分以兩位數表示。第一位表示核心內容的 AI 輔助參與程度，第二位表示內容呈現的 AI 輔助參與程度。

如：張三用人工智慧編寫劇本（對應核心內容等級 4），但是全部使用真人拍攝，背景音樂等素材也均為真人創作（對應影片內容等級 0），故在本標準下的等級為 `CVIII-40`，或使用其簡寫 `CV-40`。

 | 等級 | 核心內容（觀點、腳本、邏輯） | 內容呈現（影片製作中的素材生成、剪輯）| 
 | -------- | --------------------------------------------------- | --------------------------------------------------- | 
 | 0        | 完全由人類完成。觀點、腳本、邏輯鏈均由人工構思，全程無 AI 參與。 | 完全由人類完成。所有圖片／音樂／影片素材均為人工創作或實拍，剪輯完全手動，全程無 AI 參與。 | 
 | 1        | 完全由人類完成，AI 僅作為工具啟發創作靈感作為參考（如頭腦風暴關鍵字、熱點分析），不直接生成觀點。 | 完全由人類完成，AI 僅作為工具提供輔助性靈感（如圖片搜索建議、音樂片段推薦）。 | 
 | 2        | 主要由人類完成，AI 進行基礎輔助工作（如語法檢查、簡單文本潤色、事實核對提示）。 | 主要由人類完成，AI 局部生成少量素材（如背景圖、虛擬場景）。人工完成素材整合與核心剪輯。 | 
 | 3        | AI 完成大量內容模組（如分鏡腳本、觀點論據、腳本初稿），但經過人工深度修改、審核、核實事實並最終定稿。人類保留關鍵決策權。 | AI 完成部分關鍵素材（如主要配圖、背景音樂、部分影片片段），但所有素材均經過人工嚴格篩選、編輯或整合。 | 
 | 4        | AI 主導內容生產完整邏輯鏈（如新聞評論的論點推演、故事線設計），人工僅進行有限潤色或局部調整（如修改不當表述）。 | AI 主導創作，生成大部分或全部素材，人工僅進行抽查式審核。 | 
 | 5        | AI 獨立產出完整內容，無人工干預創作過程。 | AI 全流程自主完成所有素材生成、選擇、編輯與剪輯。人類無任何創作干預，僅執操作（如上傳、發佈）。 | 
 | \*       | 修正選項，對於主題圍繞 AI 展開的影片，在核心內容等級前加星號，如「\*1 級」 | — | 
  
## 使用說明 | Note
創作者在發佈網路內容時，可以根據實際 AI 輔助製作情況，參考本等級標準明確標注 AI 輔助等級，以「AI 輔助指數：`{等級}`」或「CVIII: `{level}`」字樣標注，或展示相應等級貼紙，讓觀眾更清晰地瞭解影片的創作過程。 
  
如果您的項目帶有 `README.md` 檔，可以使用以下徽章來展示您專案的 CVIII. 

| 核心內容＼內容呈現 | 0 | 1 | 2 | 3 | 4 | 5 |
|------------------|---|---|---|---|---|---|
| 0  | ![CVIII-00](https://img.shields.io/badge/CVIII-00-FAB689)  | ![CVIII-01](https://img.shields.io/badge/CVIII-01-FAB689)  | ![CVIII-02](https://img.shields.io/badge/CVIII-02-FAB689)  | ![CVIII-03](https://img.shields.io/badge/CVIII-03-FAB689)  | ![CVIII-04](https://img.shields.io/badge/CVIII-04-FAB689)  | ![CVIII-05](https://img.shields.io/badge/CVIII-05-FAB689)  |
| 0* | ![CVIII-*00](https://img.shields.io/badge/CVIII-*00-FAB689)| ![CVIII-*01](https://img.shields.io/badge/CVIII-*01-FAB689)| ![CVIII-*02](https://img.shields.io/badge/CVIII-*02-FAB689)| ![CVIII-*03](https://img.shields.io/badge/CVIII-*03-FAB689)| ![CVIII-*04](https://img.shields.io/badge/CVIII-*04-FAB689)| ![CVIII-*05](https://img.shields.io/badge/CVIII-*05-FAB689)|
| 1  | ![CVIII-10](https://img.shields.io/badge/CVIII-10-D9A295)  | ![CVIII-11](https://img.shields.io/badge/CVIII-11-D9A295)  | ![CVIII-12](https://img.shields.io/badge/CVIII-12-D9A295)  | ![CVIII-13](https://img.shields.io/badge/CVIII-13-D9A295)  | ![CVIII-14](https://img.shields.io/badge/CVIII-14-D9A295)  | ![CVIII-15](https://img.shields.io/badge/CVIII-15-D9A295)  |
| 1* | ![CVIII-*10](https://img.shields.io/badge/CVIII-*10-D9A295)| ![CVIII-*11](https://img.shields.io/badge/CVIII-*11-D9A295)| ![CVIII-*12](https://img.shields.io/badge/CVIII-*12-D9A295)| ![CVIII-*13](https://img.shields.io/badge/CVIII-*13-D9A295)| ![CVIII-*14](https://img.shields.io/badge/CVIII-*14-D9A295)| ![CVIII-*15](https://img.shields.io/badge/CVIII-*15-D9A295)|
| 2  | ![CVIII-20](https://img.shields.io/badge/CVIII-20-B97CAC)  | ![CVIII-21](https://img.shields.io/badge/CVIII-21-B97CAC)  | ![CVIII-22](https://img.shields.io/badge/CVIII-22-B97CAC)  | ![CVIII-23](https://img.shields.io/badge/CVIII-23-B97CAC)  | ![CVIII-24](https://img.shields.io/badge/CVIII-24-B97CAC)  | ![CVIII-25](https://img.shields.io/badge/CVIII-25-B97CAC)  |
| 2* | ![CVIII-*20](https://img.shields.io/badge/CVIII-*20-B97CAC)| ![CVIII-*21](https://img.shields.io/badge/CVIII-*21-B97CAC)| ![CVIII-*22](https://img.shields.io/badge/CVIII-*22-B97CAC)| ![CVIII-*23](https://img.shields.io/badge/CVIII-*23-B97CAC)| ![CVIII-*24](https://img.shields.io/badge/CVIII-*24-B97CAC)| ![CVIII-*25](https://img.shields.io/badge/CVIII-*25-B97CAC)|
| 3  | ![CVIII-30](https://img.shields.io/badge/CVIII-30-A865B3)  | ![CVIII-31](https://img.shields.io/badge/CVIII-31-A865B3)  | ![CVIII-32](https://img.shields.io/badge/CVIII-32-A865B3)  | ![CVIII-33](https://img.shields.io/badge/CVIII-33-A865B3)  | ![CVIII-34](https://img.shields.io/badge/CVIII-34-A865B3)  | ![CVIII-35](https://img.shields.io/badge/CVIII-35-A865B3)  |
| 3* | ![CVIII-*30](https://img.shields.io/badge/CVIII-*30-A865B3)| ![CVIII-*31](https://img.shields.io/badge/CVIII-*31-A865B3)| ![CVIII-*32](https://img.shields.io/badge/CVIII-*32-A865B3)| ![CVIII-*33](https://img.shields.io/badge/CVIII-*33-A865B3)| ![CVIII-*34](https://img.shields.io/badge/CVIII-*34-A865B3)| ![CVIII-*35](https://img.shields.io/badge/CVIII-*35-A865B3)|
| 4  | ![CVIII-40](https://img.shields.io/badge/CVIII-40-9370DB)  | ![CVIII-41](https://img.shields.io/badge/CVIII-41-9370DB)  | ![CVIII-42](https://img.shields.io/badge/CVIII-42-9370DB)  | ![CVIII-43](https://img.shields.io/badge/CVIII-43-9370DB)  | ![CVIII-44](https://img.shields.io/badge/CVIII-44-9370DB)  | ![CVIII-45](https://img.shields.io/badge/CVIII-45-9370DB)  |
| 4* | ![CVIII-*40](https://img.shields.io/badge/CVIII-*40-9370DB)| ![CVIII-*41](https://img.shields.io/badge/CVIII-*41-9370DB)| ![CVIII-*42](https://img.shields.io/badge/CVIII-*42-9370DB)| ![CVIII-*43](https://img.shields.io/badge/CVIII-*43-9370DB)| ![CVIII-*44](https://img.shields.io/badge/CVIII-*44-9370DB)| ![CVIII-*45](https://img.shields.io/badge/CVIII-*45-9370DB)|
| 5  | ![CVIII-50](https://img.shields.io/badge/CVIII-50-4D6BFE)  | ![CVIII-51](https://img.shields.io/badge/CVIII-51-4D6BFE)  | ![CVIII-52](https://img.shields.io/badge/CVIII-52-4D6BFE)  | ![CVIII-53](https://img.shields.io/badge/CVIII-53-4D6BFE)  | ![CVIII-54](https://img.shields.io/badge/CVIII-54-4D6BFE)  | ![CVIII-55](https://img.shields.io/badge/CVIII-55-4D6BFE)  |
| 5* | ![CVIII-*50](https://img.shields.io/badge/CVIII-*50-4D6BFE)| ![CVIII-*51](https://img.shields.io/badge/CVIII-*51-4D6BFE)| ![CVIII-*52](https://img.shields.io/badge/CVIII-*52-4D6BFE)| ![CVIII-*53](https://img.shields.io/badge/CVIII-*53-4D6BFE)| ![CVIII-*54](https://img.shields.io/badge/CVIII-*54-4D6BFE)| ![CVIII-*55](https://img.shields.io/badge/CVIII-*55-4D6BFE)|

若符合等級介紹中的第一種情況，則可以直接使用包含一位數等級的以下徽章展示 CVIII：  
 - [![CVIII-0](https://img.shields.io/badge/CVIII-0-FAB689)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*0](https://img.shields.io/badge/CVIII-*0-FAB689)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-1](https://img.shields.io/badge/CVIII-1-D9A295)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*1](https://img.shields.io/badge/CVIII-*1-D9A295)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-2](https://img.shields.io/badge/CVIII-2-B97CAC)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*2](https://img.shields.io/badge/CVIII-*2-B97CAC)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-3](https://img.shields.io/badge/CVIII-3-A865B3)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*3](https://img.shields.io/badge/CVIII-*3-A865B3)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-4](https://img.shields.io/badge/CVIII-4-9370DB)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*4](https://img.shields.io/badge/CVIII-*4-9370DB)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-5](https://img.shields.io/badge/CVIII-5-4D6BFE)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*5](https://img.shields.io/badge/CVIII-*5-4D6BFE)](https://github.com/StrideNotStrike/CVIII) 
  
讀者（觀眾）在流覽網路文章（或影片）時，可以查看創作者標注的等級，從而判斷網路內容在創作與呈現方面 AI 的參與程度。 
  
## 貢獻 | Contribution
如果您認為本等級標準存在不完善之處，或者有更好的建議，歡迎透過提交 Issue 或 Pull request 等方式參與貢獻。 
  
## 許可 | License
本等級標準庫採用 MIT License 許可，您可以在遵循授權合約的前提下自由使用和傳播。

## 參考資料 | Reference
[IIIA (Indice d'implication de l'intelligence artificielle)](https://github.com/ErSanSan233/IIIA) by ErSanSan233
</div>
