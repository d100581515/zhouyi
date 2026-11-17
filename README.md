# 周易本義閱讀器（GitHub Pages 離線版）

## 檔案
- `index.html`：閱讀器本體（64 卦全文已內嵌）
- `sw.js`：離線快取
- `manifest.webmanifest`、`*.png`：主畫面 App 名稱與圖示

## 上傳到 GitHub Pages
1. 登入 GitHub，右上角「+」→ New repository。
   名稱例如 `zhouyi`，選 **Public**，按 Create repository。
2. 在新倉庫頁面點 **uploading an existing file**，把這個資料夾裡的 6 個檔案全部拖進去
   （README.md 可傳可不傳），按 Commit changes。
3. 到 **Settings → Pages**：Source 選 **Deploy from a branch**，
   Branch 選 `main`、資料夾 `/ (root)`，按 Save。
4. 等 1～2 分鐘，頁面上方會出現網址：`https://你的帳號.github.io/zhouyi/`

## 加到 iPhone 主畫面
1. 用 **Safari** 開上面的網址，等首頁出現（這一次需要網路，會把全部內容存到手機）。
2. 分享按鈕 →「加入主畫面」→ 名稱「周易本義」→ 加入。
3. 之後從主畫面圖示開啟，即使沒有網路也能閱讀。

## 更新內容
修改後重新上傳檔案，並把 `sw.js` 第一行的 `zhouyi-v1` 改成 `zhouyi-v2`（數字往上加），
手機下次連網開啟時就會自動換成新版。

## 注意
- 倉庫是公開的，任何人知道網址都能看到（內容是公有領域古籍）。
- 閱讀進度與設定只存在你這支手機裡。若 iPhone 長時間（數週）沒開這個 App，
  iOS 可能清掉離線資料，屆時連網打開一次即可恢復。
