# 案件別
## 奈良高専吹奏楽部リニューアル
リポジトリ：https://github.com/nitncwind-org/gen3

### ブランチについて
| ブランチ名 | 説明 | 備考 |
| -------- | -- | -------- |
| `master`     | マスターブランチ | リリース済の最新版     |
| `release/` | リリースブランチ | リリース時にマスターブランチにマージする|
| `feature/<title><#issue_num>` |フューチャーブランチ|機能追加や改修などはこれ<br>releaseブランチにマージする|
| `fix/<title><#issue_num>` |バグ修正ブランチ|上がったバグの修正を行うブランチ<br>releaseブランチにマージする|
|`design/<title>`|デザインブランチ|デザインブランチ<br>デザインに関することはここにマージする．ここから`feature/design`にマージする|
|`gh-pages`|GitHub Pagesブランチ|GitHub Actionによって自動的にビルドされデプロイされる|

### サーバについて
#### 開発環境
URL: https://dev.nitncwind.org/  
誰でも自由にデプロイできる．自分の作業しているものが正常にサーバで動くかの確認などに使う．Netlify

#### デザイン
URL: https://design.nitncwind.org/  
`design/develop` が更新されると自動でデプロイ．デザインサーバ．Netlify

#### 検証環境
URL: https://stg.nitncwind.org/  
リリースブランチが更新されると自動でデプロイされる．Netlify

#### pre環境
URL: https://pre.nitncwind.org/  
materが更新されると自動でデプロイされる．GitHub Pages


## ebayスクレイピング
リポジトリ：https://github.com/Yamada-Factory/ebay-scraping

## discord_bot
リポジトリ：https://github.com/Yamada-Factory/discord_bot  
山田製作所botの特化改良


<br>
<br>
