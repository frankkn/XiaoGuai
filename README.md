# 小乖果實 🐶

介紹小狗「小乖」的網站 — 一隻平凡又貪吃的小狗，碰上小主人後過著睡飽吃、吃飽睡的快樂日子。

🔗 線上版：https://frankkn.github.io/XiaoGuai/

以 [Astro](https://astro.build/) 打造的多頁靜態網站，溫暖活潑風格（米色／暖橘／手寫感字體 LXGW WenKai）。

## 頁面

- 主頁 — 招呼、食物清單、個性、精選照片
- 介紹 — 基本資料與一日日程表
- 照片 — 生活照片集
- 影片 — 生活影片
- 聯繫資訊 — Q&A 與 FB 連結

## 本機開發

```bash
npm install
npm run dev      # 本機預覽 http://localhost:4321/XiaoGuai/
npm run build    # 產生靜態網站到 dist/
```

## 部署

push 到 `master` 後，GitHub Actions（`.github/workflows/deploy.yml`）自動 build 並部署到 GitHub Pages。

## 結構

- `src/pages/` — 5 個頁面
- `src/layouts/`、`src/components/` — 共用版型與 Nav/Footer
- `src/styles/global.css` — 設計變數與樣式
- `public/images/`、`public/videos/` — 圖片與影片
- `legacy/` — 舊版手刻 HTML/CSS 存檔（程式碼歸檔，非可直接瀏覽）

Written by Frank Yang
