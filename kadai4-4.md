## 自動販売機（オブジェクト、DOM、イベント処理）のミニレポート
### Q4-1. Itemクラスのメソッドについて説明せよ。
* showItemListがクラスメソッドである理由を考察せよ。
  ・htmlに変化を与えないから
  ・商品一覧を表示するためだけに使うから
* buyItemがインスタンスメソッドである理由を考察せよ。
  ・htmlに影響を与えるから
  ・値変更するため
### Q4-2. 商品の購入ボタンをクリックすると、どのような処理でセルの値が減少するか説明せよ。
* 購入された商品の在庫数のセルをどのようにして特定するのか説明せよ。
  ・spanタグにid="stock"+商品IDを設定して識別
  ・購入時にdocument.getElementById("stock" + 商品ID)で特定
* 特定したセルの値をどのように変更するのか説明せよ。
  ・対象の要素をdocument.getElementById()で取得し、textContentに新しい値を代入
### Q4-3. 感想
* 今回の課題で苦労したこと
  ・調べながら書いたので、書き終わるのに時間がかかった
* 演習を通して理解できたこと
  ・tableタグの使い方
* この自動販売機プログラムの追加機能や課題など
  ・アンケートを記入する欄をつくる
