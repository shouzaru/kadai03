# 課題０3：LocalStorageの扱い（テトリスで）
## ①課題内容（どんな作品か）
- 東京卍會を相手にテトリスしよう。
- 相手を選んだらSTARTボタンをクリックしてテトリス開始（ゲームはフツ〜のテトリスです）。
- 相手にマイキーを選ぶと即死。まさに無敵。
- 相手ごとにハイスコアが保存されます。ハイスコア目指し頑張ろう！

## ②工夫した点・こだわった点
- 2ライン揃えるごとにスピードアップするようにしました。20ライン消せたらスゲー。
- 5人のキャラクターそれぞれに対してハイスコアをLocalStrageに保存します。
- 過去に記録したハイスコアを超えた時だけ、LocalStrageのデータを書き換えるようにしました。

## ③苦労した点
- スペースキーをkeyDownすると、html上のスタートボタンがクリックされるという仕様に気づくまで数時間かかった
- LocalStorageにキャラの使用履歴（Key）があれば、値（Value）を確認して、書き換えたりそのまま残したりします。
- LocalStorageにキャラの使用履歴がないことを判定するコードを書くのに苦労。localstorage.hasOwnProperty()で解決。

## ④その他（感想、シェアしたいことなんでも）
- デザインセンスが壊滅的。おしゃれになりたい。
