# 🎓 刑法申論題 AI 教練｜Legal Essay Tutor

![Profile views](https://komarev.com/ghpvc/?username=mjib007&label=Profile%20views&color=4c8eda&style=flat)
[![Stars](https://img.shields.io/github/stars/mjib007/legal-essay-tutor?style=flat&color=yellow)](https://github.com/mjib007/legal-essay-tutor/stargazers)
[![Forks](https://img.shields.io/github/forks/mjib007/legal-essay-tutor?style=flat&color=blue)](https://github.com/mjib007/legal-essay-tutor/network/members)
![AI](https://img.shields.io/badge/AI-Claude%20(Anthropic)-blueviolet)
![Platform](https://img.shields.io/badge/Platform-claude.ai-orange)
![Language](https://img.shields.io/badge/Language-繁體中文-red)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
![Status](https://img.shields.io/badge/status-active-success)

> 以蘇格拉底問答法為核心，結合 AI 輔助，重新設計刑法申論題的學習與教學體驗。

---

## 這是什麼？

**Legal Essay Tutor** 是一套專為台灣法律系學生與教師設計的 AI 輔助教學工具。

它的核心理念來自蘇格拉底問答法——**不直接給答案，而是用提問引導學生自己發現答案**。透過將這套教學邏輯轉化為 AI Prompt，任何人都可以透過 Claude（Anthropic 出品的 AI）獲得一位「隨時在線的刑法家教」。

---

## 適合誰使用？

| 對象 | 用途 |
|------|------|
| 📚 法律系學生 | 自主練習申論題、獲得即時批改回饋 |
| 👨‍🏫 法律系教師 | 了解 AI 輔助法學教育的可能性與限制 |
| ⚖️ 國考／司律考生 | 針對刑法申論題進行高強度練習 |
| 🔬 法律教育研究者 | 探索 AI 對法學教育模式的影響 |

---

## 三種學習模式

本工具提供三種模式，可依需求切換：

### 模式 A：蘇格拉底問答引導
適合想要「深度思考」的學習者。AI 扮演教授角色，每次只問一個問題，引導你走過九個思考階段，從讀題、切割行為、找罪名，一路到撰寫結論。**不會直接給你答案。**

### 模式 B：逐段批改
適合已經寫好答案、想要回饋的學習者。貼上你的答案，AI 會逐段給出評分（★☆）、優點、問題與修改建議，最後提供總分與改進方向。

### 模式 C：標準答案示範
適合想直接看「範本長什麼樣子」的學習者。AI 依照三階層犯罪審查體系，完整示範一份申論答案，並附上爭點清單、篇幅分配建議與常見扣分陷阱。

---

## 快速開始

### 第一步：準備工具
你需要一個 **Claude 帳號**（免費版即可使用）：
👉 [https://claude.ai](https://claude.ai)

### 第二步：複製 Prompt
前往本倉庫的 [`PROMPT.md`](./PROMPT.md)，複製完整的 Prompt 內容。

### 第三步：開始對話
1. 在 Claude 開啟一個新對話
2. 將 Prompt 貼入對話框，送出
3. 接著貼上你的申論題題目
4. 告訴 AI 你想使用哪種模式（A／B／C）

就這樣，不需要安裝任何程式。

---

## 使用範例

**學生輸入：**
```
甲發現乙正在行竊，遂持磚頭追打乙，致乙死亡。問甲之刑事責任？

我要使用模式 A（蘇格拉底問答）
```

**AI 回應（節錄）：**
```
好，我們從第一步開始——讀題與標記關鍵事實。

這個階段的目的是找出題目裡每一個具有法律意義的事實，
因為命題者安排的每個字都可能是爭點的線索。

請問：你能不能把題目裡每一個你覺得「有法律意義」的事實標記出來？
```

---

## 防幻覺說明

AI 有時會產生不正確的資訊（俗稱「幻覺」）。本工具已在 Prompt 中加入防幻覺機制：

- **法條引用**：僅引用確定存在的條文，條號精確至項款
- **判決字號**：若不確定，改以「依實務見解」帶過，不編造字號
- **學說見解**：僅提及通說立場，不虛構學者姓名或著作

⚠️ **重要提醒**：AI 的回答僅供學習參考，不構成法律意見。法條與判決內容請以官方資料庫（法源法律網、司法院法學資料檢索系統）為準。

---

## 適用考試範圍

- 律師／司法官考試（司律）
- 法研所入學考試
- 大學刑法期中、期末考
- 國家考試（高考、普考、地特）
- 一般刑法申論題練習

---

## 檔案結構

```
legal-essay-tutor/
│
├── README.md          # 你現在看的這份說明文件
├── PROMPT.md          # 完整 Prompt，複製後即可使用
└── EXAMPLES.md        # 示範對話（蘇格拉底模式、批改模式、示範模式各一例）
```

---

## 關於 AI 輔助法學教育

這個工具的出現，代表法學教育正在面臨一個真實的轉變：**當學生可以隨時獲得一位「不會累、不會不耐煩」的 AI 家教，傳統的教學模式需要如何調整？**

本工具並非要取代教師，而是希望：
- 讓學生在課外有更多**主動練習**的機會
- 讓教師能夠將課堂時間用在**更高層次的討論**
- 提供一個可以討論「AI 輔助教學的可能性與限制」的具體案例

---

## 授權

本教材以 [MIT License](./LICENSE) 授權公開，歡迎自由使用、修改與分享，請保留原作者資訊。

---

## 聯絡與貢獻

如果你是法律系教師或學生，歡迎：
- 提交 **Issue** 回報問題或建議
- 提交 **Pull Request** 貢獻示範對話或改善 Prompt
- 直接聯絡作者討論教學合作

---

*本工具由台灣法律教育工作者製作，使用 Claude（Anthropic）作為 AI 引擎。*
