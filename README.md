# Virtual Desktop Browser（中文）

一個給 OpenClaw/Agent 使用的技能：
在 **Xvfb 虛擬顯示器（固定 1200x720x24）** 啟動 **Chromium 非無頭模式**，並用 **PyAutoGUI** 進行模擬人類操作（點擊、輸入、滾動、截圖）。

## 功能
- 啟動/停止 Xvfb + Chromium
- 滑鼠點擊、鍵盤輸入、快捷鍵
- 滾動、截圖、像素取色
- 圖像模板匹配（OpenCV）
- 視窗聚焦

## 安裝（系統依賴）
```bash
sudo apt-get update
sudo apt-get install -y xvfb chromium-browser \
  libnss3 libgconf-2-4 libxss1 libasound2 \
  libatk1.0-0 libatk-bridge2.0-0 libcups2 \
  libdrm2 libgbm1 libgtk-3-0 libxshmfence1 x11-utils
```

## 安裝（Python 依賴）
```bash
pip install -r requirements.txt
```

## 技能文件
- `SKILL.md`：技能說明與工具介面
- `skill.py`：核心實作

## 使用場景
- 小紅書、X/Twitter 等需要模擬人類操作的場景
- 需要 GUI + 虛擬顯示器的自動化流程

## 作者
Creator: **Allen Niu**
