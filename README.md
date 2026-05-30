# 淡路島AI技術リサーチ

English name: Awaji Island AI Technology Research

## 内容

1980年代の代表的な Yamaha オートバイ画像を中心に、先に収集した Yamaha 関連特許を部位別に表示する確認用Webページ。
ページ上部のボタンで日本語/英語を切り替え可能。
英語表示は、UI、車両説明、特許詳細ページに対応。主要特許は個別英訳、その他の特許は技術分類に基づく英語フォールバックで表示する。
外観は Zenn を参考に、白基調、淡いグレー背景、シアン系アクセント、軽いカード境界の技術メディア風に調整。
左側の車両切替リストは、車種名と年代を表示するカード型リスト。

## 表示ファイル

- `index.html`
  - GitHub Pages公開用のトップページ。技術テーマを選択する入口。
- `yamaha-1980s-patents.html`
  - 1980年代 Yamaha オートバイ特許マップの技術テーマページ。

## GitHub Pages 公開メモ

このフォルダの中身をGitHubリポジトリのルートへアップロードすると、`index.html` がトップページとして表示される。

## 代表車両画像

| 車両 | 画像ソース | ライセンスメモ |
| --- | --- | --- |
| Yamaha RD350LC / RD350 YPVS | https://commons.wikimedia.org/wiki/File:Yamaha_RD350.JPG | CC0 |
| Yamaha Venture Royale XVZ1200 | https://commons.wikimedia.org/wiki/File:1983_MK1_Yamaha_Venture_Royale_Gary_Swartz.JPG | GFDL / CC BY-SA 3.0 |
| Yamaha V-Max / VMX1200 | https://commons.wikimedia.org/wiki/File:Yamaha_Vmax_1200.jpg | CC BY-SA 3.0 |
| Yamaha FZR1000 | https://commons.wikimedia.org/wiki/File:Fzr1000.JPG | Public domain |

## Webページで使用中の加工画像

| 車両 | 使用画像 |
| --- | --- |
| Yamaha RD350LC / RD350 YPVS | `assets/processed/rd350_factory_manga.png` |
| Yamaha Venture Royale XVZ1200 | `assets/processed/venture_royale_factory_manga.png` |
| Yamaha V-Max / VMX1200 | `assets/processed/vmax_factory_manga.png` |
| Yamaha FZR1000 | `assets/processed/fzr1000_factory_manga.png` |

## ロゴ

- 採用ロゴ: `assets/brand/awaji_tech_logo_01.png`
- ロゴ案: `assets/brand/awaji_tech_logo_01.png` から `assets/brand/awaji_tech_logo_05.png`

## 注意

- ページ上の特許配置は、特許タイトル、技術分野、収集メモに基づく関連部位の表示。
- 「この特許がこの市販車に採用された」と断定するものではない。
- 採用実績の確認には、Yamaha公式資料、部品表、サービスマニュアル、当時の技術資料との照合が必要。
- 特許番号ピンをクリックすると、Google Patents URL、技術要約、請求項の要約、請求項ツリー、強み、適用製品/適用候補を載せた詳細ページが別ウィンドウで開く。
- 請求項の要約とツリーは、US特許およびUS意匠については Google Patents から取得した原文請求項をもとに精密版へ更新済み。
- `JPS5758511A`、`JPS57102519A`、`JPH0790814B2` は Google Patents の英語ページから原文請求項を抽出できなかったため、詳細ページ内で「請求項未取得」として区別している。正式な精密化には日本語公報またはPDFからの請求項取得が必要。
