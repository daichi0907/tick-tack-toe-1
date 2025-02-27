# 課題：強くして
本リポジトリのAIに対して、何らかの工夫をしてください！

* 計算を効率化する
* 新たなアルゴリズムを実装する

5目並べにすると、わかりやすいかもしれません。


![結果画像](image.png)

# 取り組み方
* 本プロジェクトをforkして、取り組んでください。
* GitHub Actions (Actionsのタブ)を機能させて、README.mdに記述された下記のバッチの「tpu-game-2022」を自分のアカウントに差し替えてください。
* readme.md に実施した工夫を記載してください
* 可能であれば、速度等を計測して、具体的な効率化度合い、強さを示してください。
* 納得できるところまでできたところでプルリクを出してください。

[![MSBuild](https://github.com/daichi0907/tick-tack-toe/actions/workflows/msbuild.yml/badge.svg)](https://github.com/daichi0907/tick-tack-toe/actions/workflows/msbuild.yml)

（↑のソースコードの「tpu-game-2021」を自分のアカウント名に差し替えてください（２か所））

Nega-max戦略、alpha-beta法、Nega-Scout法、原始モンテカルロ法、モンテカルロ木探索を実装しました。
「Nega-max→alpha-beta→Nega-scout→原始モンテカルロ」という感じで処理速度が速くなっていました。
原始モンテカルロの方が処理速度は速くなっていましたが、モンテカルロ木探索は処理速度が遅くなる代わりに原始モンテカルロよりも強くなっているように感じました。

# 〆切
*/*(日)
