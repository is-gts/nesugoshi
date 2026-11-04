# 寝過ごしナシ

降りる駅に近づいたら、GPSで起こすアラーム。

- 事前登録ページ: https://is-gts.github.io/nesugoshi/ （`docs/` を GitHub Pages で公開）
- 登録先: 共通の Google スプレッドシート「登録」シート、アプリキー `nesugoshi`
- 集計: `=COUNTA(UNIQUE(FILTER(登録!C:C,登録!B:B="nesugoshi")))`
- Androidプロジェクトはこのリポジトリのルートに置く（登録数が基準を超えたら着手）

## SNS告知文

電車で寝過ごして終点まで行った経験、ありますか。
降りる駅に近づいたらGPSで起こす「寝過ごしナシ」、時刻設定なしで駅を選ぶだけ。
欲しい人は事前登録👇
https://is-gts.github.io/nesugoshi/

#個人開発 #Androidアプリ #事前登録
