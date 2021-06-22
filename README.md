# Google-Apps-Script-Auto-Batch-Templated-Email

老師們有需要時可以透過 Google Spreadsheet 批量發放個人化電郵給任教學生
[https://docs.google.com/spreadsheets/d/170FY4dH9KpdyCAOHA-eKEixKC6Rc99O-Hk_tlVbNXyg/copy](https://docs.google.com/spreadsheets/d/170FY4dH9KpdyCAOHA-eKEixKC6Rc99O-Hk_tlVbNXyg/copy)

## 功能
- 於 Template 頁簡單設定 Subject 及 電郵 Template 格式
- 按 Data 頁的 Spreadsheet 名單自動發放電郵
- 支援 Mailmerge 自定義欄目，不限欄目數量，每位學生收取不同內容

## 用法
1. (測試) 以 Data 頁 A2 格輸入自己電郵，並設定其他自定義欄位及內容
2. (測試) 設定 Template 頁的 Subject 及 Template 格式，當中 ${"欄位名稱"} 將自動替換為自定義內容
3. (測試) 前往頂部 Menu 主選單 > Tools (工具) > Script Editor (指令碼編輯器) > 新視窗頂部選單設為 sendEmails > 點擊 Run
4. (測試) 成功後將提示 Execution completed，失敗請截圖紀錄以便了解情況，同時檢查 寄出郵件 有沒有對應紀錄
5. 填妥 Data 頁名單
6. 重覆第 3 步

## 限制
- 需以個人身份授權作為寄件人
- 統一 Subject (有待改良)
- Google Apps Script 設有免費限額，詳情請查閱 h
