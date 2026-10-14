# 🍜 BiteSpin

**今天吃什麼？轉一下就知道！** · *Spin the wheel. Pick your meal.*

A lightweight, customizable food decision wheel. Pick your favorite restaurants and let the wheel decide what to eat!

👉 **線上使用 / Try it:** https://pomelobiscuit.github.io/BiteSpin/

## 功能

- 勾選想吃的店家，只會從勾選的選項中抽出結果
- 新增、修改、刪除店家；一次可用逗號新增多家（最多 200 個）
- 每個選項中獎機率相同（使用瀏覽器的 `crypto.getRandomValues`，避免取餘數偏差）
- 保留最近 6 次抽中紀錄
- 手機、電腦都能用

## 隱私

店家清單和抽選紀錄**只存在你自己的瀏覽器**（`localStorage`），不需註冊、不會上傳到任何伺服器。

## 使用方式

- 直接開線上版，或
- 下載 `index.html`，用瀏覽器打開即可——單一檔案，沒有任何外部相依。

## Features (English)

- Only checked options can win; each has an equal chance (uses `crypto.getRandomValues` with rejection sampling)
- Add, edit, and delete options; add several at once separated by commas (up to 200)
- Keeps your last 6 results
- Everything stays in your browser's `localStorage` — no sign-up, nothing uploaded
- Single HTML file, no dependencies

## License

[MIT](LICENSE)
