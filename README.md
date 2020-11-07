# DOLK

[![IMAGE ALT TEXT HERE](https://jphacks.com/wp-content/uploads/2020/09/JPHACKS2020_ogp.jpg)](https://www.youtube.com/watch?v=G5rULR53uMk)

## 製品概要
### 背景(製品開発のきっかけ、課題等）
**「メタボ」**   
誰しも一度は聞いたことがあるほど認知されている社会問題だと思います。  
「メタボ」と聞くとついつい人間の話だと思っていませんか？「メタボ」は人間だけの問題ではなく、獣医領域でも同様の問題があるのです...!!!
そう、あなたの犬ちゃんにも！！！！！  
体型も体調も犬ちゃんそれぞれだから犬ちゃんそれぞれに適した運動方法,餌を与えたいけどわざわざ獣医に行くのは...
でも、大切な家族である犬ちゃんに長生きして欲しい...
というわけで我々が目をつけた課題は次のようなものです。   
**「犬ちゃんそれぞれに適した運動・餌の量がわからない」**

### 製品説明（具体的な製品の説明）  
体調管理が人それぞれであるようにペットの体調管理も犬それぞれ。
健康で長生きするには、適度な運動とバランスのよい食生活への改善が必要というのは犬ちゃんも同じ！！
そこで、各犬ちゃんの年齢、体重、写真から最適化された散歩量とご飯の量を教えてくれるアプリケーションを作成しました。

### 特長
#### 1. すごおいいい！！！「犬ちゃんの肥満度をAIモデルを用いて写真から把握」
#### 2. 楽しいいい！！！「適切な日替わり散歩ルートをレコメンド！」


### 解決出来ること
犬ちゃんの健康を簡単に把握、適切な犬ちゃんケアを実現できます！！

### 今後の展望
- 犬ちゃんだけでなく、猫ちゃんやワニちゃんなどあらゆるペットに対応。
→ 動物園などにシステムとして導入
- 犬種などによるさらに適切な指導の実現

### 注力したこと（こだわり等）
* 論文を読んでワンチャンの一日の消費カロリー計算を実装
* 毎日楽しく使えるように日替わり散歩ルートなどのユニークな機能を搭載

## 開発技術
### 活用した技術
#### API・データ
* [Azuret Custom Vision](https://azure.microsoft.com/ja-jp/services/cognitive-services/custom-vision-service/)
* [Google Maps Platform](https://cloud.google.com/maps-platform/?hl=ja)

#### フレームワーク・ライブラリ・モジュール
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Flutter](https://flutter.dev/?gclid=Cj0KCQiAhZT9BRDmARIsAN2E-J10W9sgj5-z-HdIz-9_d4ZcwHx9ZExi6TS71Z2lFDWvz23WEhMW_IAaAmZjEALw_wcB&gclsrc=aw.ds)
* [heroku](https://jp.heroku.com/)
#### デバイス
* iOS

#### ハッカソンで開発した独自機能・技術
* 犬の太り具合を算出する機能の作成
* 距離から散歩ルートを自動生成する機能を作成