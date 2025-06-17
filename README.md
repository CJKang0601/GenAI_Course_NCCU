# 🤖 AI-Powered IELTS 雅思備考助理

這是一個使用 Google Gemini API 打造的互動式雅思（IELTS）練習平台，專為生成式 AI 課程期末專案而設計。平台完全在 Google Colab 環境中運行，透過 `ipywidgets` 提供互動介面，讓使用者可以進行動態、即時的閱讀與寫作練習。




---

## 🚀 主要功能 (Key Features)

* **動態生成閱讀測驗**：
    * 每次點擊都能由 Gemini AI 即時生成一篇全新的學術風格文章。
    * AI 會根據文章內容，自動產生多種題型（選擇、是非/未提及、填空）的題目。
    * 告別靜態題庫，提供無限的練習機會。
![image](https://github.com/user-attachments/assets/75598a7b-9ea9-4de2-bfb7-7c8d65a650fa)
![image](https://github.com/user-attachments/assets/889e1b98-12c5-4f6e-9976-cdb2e0aaea61)


* **動態生成寫作題目**：
    * 使用者可根據選擇的主題（如科技、環境），由 AI 生成一個符合雅思 Task 2 格式的寫作題目。
    * 確保每次練習都充滿新鮮感與挑戰性。
![image](https://github.com/user-attachments/assets/3ca99aa9-7b8a-430b-91ce-06f3d1d04814)

* **AI 深度寫作評分**：
    * 專案的核心亮點！使用者提交作文後，後端會呼叫 Gemini API。
    * AI 會扮演雅思考官，從**任務完成度 (TA)**、**連貫與銜接 (CC)**、**詞彙資源 (LR)**、**語法廣度與準確性 (GRA)** 四個面向進行全面分析。
    * 提供各項子分數、具體評語、總分和總結，給予使用者極具參考價值的回饋。
![image](https://github.com/user-attachments/assets/04d9ea2c-3f23-4667-8a5f-109e4bc6bf80)

* **全互動式介面**：
    * 使用 `ipywidgets` 在 Colab Notebook 中直接建構操作介面，無需架設網站。
    * 提供下拉式選單、按鈕、文字輸入區等元件，使用者體驗流暢。
![image](https://github.com/user-attachments/assets/fcd7b906-3c42-4a9d-96ac-cd8db9dce92b)

---

## 🛠️ 技術棧 (Technology Stack)

* **程式語言**: Python 3
* **主要平台**: Google Colab
* **核心模型**: Google Gemini 1.5 Flash API
* **自然語言處理**: spaCy
* **互動介面**: ipywidgets

---

## ⚙️ 如何使用 (Setup and Usage)

1.  **取得 API 金鑰**：
    * 前往 [Google AI Studio](https://aistudio.google.com/) 取得您的 Gemini API 金鑰。

2.  **在 Colab 中開啟**:
    * 點擊上方的 "Open in Colab" 按鈕，或直接將 `.ipynb` 檔案上傳到您的 Google Colab 環境。

3.  **設定 API 金鑰**：
    * 在 Colab 介面左側的側邊欄中，點擊「鑰匙 🔑」圖示 (Secrets)。
    * 新增一個密鑰，名稱必須設為 `GOOGLE_API_KEY`。
    * 將您複製的金鑰貼到「值 (Value)」的欄位中並儲存。

4.  **執行程式**：
    * 點擊「執行階段」 -> 「全部執行」。
    * 程式會自動安裝所需套件、載入模型，並在儲存格下方顯示互動介面。
    * 現在，您可以開始使用 AI 進行雅思練習了！

---

## ✨ 未來展望 (Future Work)

* **整合語法檢查工具**：引入 `language-tool-python` 等工具，在寫作分析中提供更具體的語法錯誤修正建議。
* **擴充閱讀題型**：增加如段落標題配對 (Matching Headings)、摘要填空 (Summary Completion) 等更複雜的題型。
* **儲存練習紀錄**：允許使用者儲存過去的作文、分數與 AI 評語，方便追蹤進步軌跡。
* **進階詞彙建議**：分析使用者作文中的常用詞，並由 AI 建議更高級的同義詞替換。

---

## 👨‍💻 作者

* [CHENG-JUN KANG]([(https://github.com/CJKang0601])
