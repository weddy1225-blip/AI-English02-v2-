# 🧺 週末野餐大冒險 (Weekend Picnic Adventure Pro)

![Language](https://img.shields.io/badge/Language-English-orange)
![Platform](https://img.shields.io/badge/Platform-Web-blue)
![Tech](https://img.shields.io/badge/Tech-Web_Speech_API-green)

這是一款專為英語初學者設計的**互動式階梯口說練習網頁**。透過「語音通關」作為核心機制，結合真實音效與冒險情境，讓學習者在練習交通工具句型的過程中建立口說自信心。

---

## 🎮 [立即體驗冒險](https://weddy1225-blip.github.io/AI-English02-v2-/)

> **💡 最佳體驗建議：**
> 1. **瀏覽器**：請使用 **Google Chrome** 以獲得最精準的語音辨識效果。
> 2. **權限設定**：進入網頁後，請點擊 **「允許」** 使用麥克風。
> 3. **環境建議**：戴上耳機體驗真實音效，並在安靜的地方進行練習。

---

## 📖 教學設計特色 (Educational Features)

為了克服單次練習分量不足的問題，專案進行了深度優化：

### 1. 三階段學習梯度 (Progressive Levels)
每個交通工具單元皆分為三個等級，由淺入深引導學習：
*   **Level 1: Vocabulary (單字基礎)**：精確掌握核心名詞發音。
*   **Level 2: Short Sentence (生活短句)**：學習常用動詞搭配。
*   **Level 3: Contextual Challenge (情境長句)**：挑戰完整流暢的句型表達。

### 2. 沉浸式視聽回饋
*   **真實音效**：點擊載具時會觸發開門聲、鈴聲、喇叭聲或進站音。
*   **豐富評價系統**：成功後隨機組合「精準評價」與「冒險情境對話」，強化聽力輸入。

### 3. 成就與進度追蹤
*   **視覺進度條**：即時回饋目前的整體完成度。
*   **狀態記憶**：完成該單元所有關卡後，按鈕會自動**變灰鎖定**，鼓勵學生探索其他交通工具。

---

## 🛠️ 技術架構 (Tech Stack)

*   **Frontend**: HTML5 / CSS3 (採用響應式佈局與脈衝動畫)
*   **Logic**: Vanilla JavaScript (ES6+)
*   **APIs**:
    *   `Web Speech API (Recognition)`：實現即時語音辨識與模糊判定。
    *   `Web Speech API (Synthesis)`：AI 語音示範與真人感回饋。
    *   `HTML5 Audio`: 整合環境音效增強互動感。

---

## 🚀 如何部署至自己的 GitHub

1.  **Fork 倉庫** 或下載 `index.html`。
2.  在 GitHub 建立一個新 Repository 並上傳 `index.html`。
3.  進入 **Settings > Pages**。
4.  將 **Branch** 設定為 `main`，點擊 **Save**。
5.  大約 1 分鐘後，即可透過產生的 URL 分享你的遊戲！

---

## 💡 開發初衷 (Inspiration)

「讓開口說英文變得像玩冒險遊戲一樣簡單。」
傳統的練習往往枯燥乏味，本專案旨在透過 AI 語音技術提供即時正向回饋，並設計明顯的進度指標，讓學生在追求「全破」的過程中，不知不覺地完成多次重複口說練習。

---

## 📄 授權協議 (License)
本專案採用 [MIT License](LICENSE) 授權。歡迎用於教學、學習或個人改作。
