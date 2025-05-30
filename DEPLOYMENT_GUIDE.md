# 🚀 數學勇者 RPG 部署指南

## 📋 快速部署步驟

### 1. 啟用 GitHub Pages

1. 前往你的 GitHub 倉庫：https://github.com/Donaldcpk/MathRPG-Ngwah
2. 點擊 **Settings** 標籤
3. 在左側選單中找到 **Pages**
4. 在 **Source** 部分選擇 **GitHub Actions**
5. 點擊 **Save**

### 2. 觸發自動部署

部署會在以下情況自動觸發：
- 推送代碼到 `main` 或 `master` 分支
- 建立 Pull Request

### 3. 檢查部署狀態

1. 前往倉庫的 **Actions** 標籤
2. 查看 "Deploy Math RPG to GitHub Pages" 工作流程
3. 等待部署完成（通常需要 2-5 分鐘）

### 4. 訪問你的遊戲

部署完成後，你的遊戲將可在以下網址訪問：
**https://donaldcpk.github.io/MathRPG-Ngwah/**

## 🎮 遊戲功能

### 主要遊戲檔案
- `index.html` - 遊戲主頁面
- `MultipleChoice.html` - 選擇題模組
- `TrueFalse.html` - 是非題模組  
- `ShortAnswer.html` - 簡答題模組

### 遊戲資源
- `js/` - 遊戲邏輯和插件
- `img/` - 圖片資源
- `audio/` - 音效檔案
- `data/` - 遊戲資料
- `css/` - 樣式檔案

## 🔧 故障排除

### 如果遊戲無法載入：

1. **檢查 GitHub Actions**
   - 前往 Actions 標籤
   - 確認最新的部署是否成功

2. **檢查檔案路徑**
   - 確保所有資源檔案都已正確上傳
   - 檢查檔案名稱是否包含特殊字符

3. **瀏覽器相容性**
   - 使用現代瀏覽器（Chrome, Firefox, Safari, Edge）
   - 啟用 JavaScript
   - 清除瀏覽器快取

### 如果需要更新遊戲：

1. 修改本地檔案
2. 提交變更：
   ```bash
   git add .
   git commit -m "更新遊戲內容"
   git push origin master
   ```
3. GitHub Actions 會自動重新部署

## 📱 行動裝置支援

遊戲支援在以下裝置上運行：
- 📱 智慧型手機
- 📱 平板電腦
- 💻 桌上型電腦
- 💻 筆記型電腦

## 🎯 遊戲特色

- ✅ 完全免費
- ✅ 無需下載安裝
- ✅ 支援離線遊玩（首次載入後）
- ✅ 跨平台相容
- ✅ 教育性數學內容
- ✅ RPG 遊戲元素

## 📞 技術支援

如果遇到技術問題：

1. 檢查網路連線
2. 重新整理頁面
3. 清除瀏覽器快取
4. 嘗試不同瀏覽器
5. 在 GitHub 上提交 Issue

## 🎉 享受你的數學冒險！

現在你的數學 RPG 遊戲已經成功部署到網路上，任何人都可以透過網址訪問和遊玩！

**遊戲網址：https://donaldcpk.github.io/MathRPG-Ngwah/**

分享給你的朋友和學生，一起在遊戲中學習數學吧！ 🌟 