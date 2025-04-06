# Modern Login Page (現代化登入頁面)

這是一個現代化的、響應式的登入頁面實現，具有直觀的用戶界面和豐富的互動功能。

![登入頁面預覽](https://raw.githubusercontent.com/jerry3315765/MCP_test/master/preview.png)

## 功能特點

- 🎨 現代化設計
  - 使用漸變背景色
  - 清晰的卡片式布局
  - 響應式設計，支援各種設備尺寸

- 🔒 安全性功能
  - 密碼強度即時檢查（最少8個字符）
  - 密碼顯示/隱藏切換
  - 電子郵件格式即時驗證

- ⚡ 交互體驗
  - 浮動標籤效果
  - 表單驗證即時反饋
  - 記住我選項
  - 登入狀態反饋

## 技術實現

- 純 HTML5 / CSS3 / JavaScript
- 使用 CSS 變量實現主題定制
- Flexbox 布局
- Google Noto Sans TC 字體支援
- 原生 JavaScript 實現所有互動功能
- SVG 圖標

## 本地測試

1. 克隆此倉庫：
```bash
git clone https://github.com/jerry3315765/MCP_test.git
```

2. 進入項目目錄：
```bash
cd MCP_test
```

3. 在瀏覽器中打開：
   - 直接打開 `login-page/index.html`
   - 或使用本地服務器（如 Live Server）運行

## 功能測試

1. **表單驗證**：
   - 嘗試提交空表單，會收到提示
   - 輸入無效的電子郵件格式，輸入框會顯示紅色提示
   - 輸入少於8個字符的密碼，將看到密碼強度提示

2. **交互功能**：
   - 點擊密碼欄位右側的眼睛圖標可切換密碼顯示/隱藏
   - 勾選"記住我"選項
   - 點擊"忘記密碼？"和"立即註冊"鏈接
   - 觀察表單提交時的登入狀態變化

## 自定義主題

您可以通過修改 `style.css` 中的 CSS 變量來自定義主題：

```css
:root {
    --primary-color: #4f46e5;    /* 主要顏色 */
    --primary-hover: #4338ca;    /* 懸停顏色 */
    --text-color: #1f2937;       /* 文字顏色 */
    --text-light: #6b7280;       /* 次要文字顏色 */
    --background: #ffffff;        /* 背景顏色 */
    --error: #ef4444;            /* 錯誤提示顏色 */
    --success: #10b981;          /* 成功提示顏色 */
}
```

## 注意事項

- 這是一個前端示例，實際使用時需要配合後端API
- 密碼驗證僅檢查長度，實際應用中應該有更嚴格的規則
- "忘記密碼"和"立即註冊"鏈接需要根據實際需求進行配置

## License

MIT License - 請查看 LICENSE 文件了解更多信息。
