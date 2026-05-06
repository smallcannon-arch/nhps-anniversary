# 內湖國小校慶輪播

新竹市香山區內湖國小校慶活動現場大螢幕輪播頁面。

## 線上網址

https://smallcannon-arch.github.io/nhps-anniversary/

## 內容

四頁循環播放：

1. 貴賓簽到處 歡迎蒞臨（12 秒）
2. 校慶運動會流程表（15 秒）
3. 入校小叮嚀（12 秒）
4. 即時捐款牆（30 秒，iframe 嵌入 [donation-wall](https://smallcannon-arch.github.io/donation-wall/)）

## 鍵盤控制

| 按鍵 | 功能 |
|---|---|
| `空白` | 暫停 / 播放 |
| `←` `→` | 上 / 下一頁 |
| `F` | 全螢幕切換 |
| `Esc` | 退出全螢幕 |

## 修改

- 換圖：替換 `images/` 下的檔案，檔名不變即可
- 改停留秒數：搜尋 `data-duration`，單位為毫秒
- 改頁面順序：把 `<div class="slide">` 區塊往前或往後搬

## 技術

純 HTML + CSS + JavaScript，無框架、無建置流程。直接 push 到 GitHub Pages 即可。
