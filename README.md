# Gs_kadai1_janken_1022_001
じゃんけんアプリ（課題に忠実版）


# 課題1 -じゃんけんアプリ-

## ①課題内容（どんな作品か）

- じゃんけんアプリ 【課題の要件に忠実ver】

## ②工夫した点・こだわった点

- 配列を使って、じゃんけんの勝ち負け判定をできるようにしたところがポイントです。
- まず、人間が選択したグー、チョキ、パーにそれぞれ値を代入（0,1,2）し、数値化した。
- 次に、コンピューターがランダム生成した数字に基づくグー、チョキ、パーもそれぞれ同様に値を代入（0,1,2）し、数値化した。
- これにより人間が選択した手札と、コンピューターがランダム生成した手札が数値として比較できる状態になり、最後に差し引きの数字で勝ち負け判定をし、判定数値に基づきIF文を分けて表示した。

- 配列を使わない場合も考えたのですが、①　IF（人間がグーを出した場合）｛以下、分岐｝、　②IF（人間がパーを出した場合）｛以下、分岐｝、　③IF（人間がチョキを出した場合）｛以下、分岐｝、の３通りに同じような分岐式をたくさん書かないといけなくなることが想定されたので、配列を使ってまとめられるならばそのほうが構造化しやすそうだなと思い挑戦しました。
- また、自分は作りたいアプリの応用として、もっと手数が多いもの（洋服の種類など無限にあるもの）を今後、応用的にランダム生成することを想定していたので、なるべく配列やまとめられる処理を使って書いてみたかったので、挑戦しました。


## ③難しかった点・次回トライしたいこと(又は機能)

- 課題の要件を満たすものを仕上げるだけでかなりの労力がかかってしまった。仕上げるだけでかなり大変だった。
- 途中、本当に「なにから処理を作ったらよいかわからない」「１つ１つ作ってみてもどれも動かない」「どこが違うのかの見当がつけられない」という状態が数日続き、かなり焦りました。
- 処理をステップに分けて考えて、まずいちばん簡単そうなところから着手する、最初の１つや２つが動くようにできると、できるような気持ちになるのとだんだん少しわかってきて、「こうかな？」と試行錯誤ができる状態になる。その状態でも、なかなか仮説通りに動かないことばかりなので、調べるのに無限に時間がかかったりするが、１つ１つクリアしていくしかないと決めてコツコツすすめるしか無いという感覚を持てた。
- 応用的な機能はなにもトライできていないので、課題末尾002に持ち越しました。
- 

## ④質問・疑問・感想、シェアしたいこと等なんでも

 【感想】
- HTML/CSS までと違い、JavaScript、Jquery、あたりが入ってきて超絶急に難易度があがりました。（１対１０くらい…）
- ついていけるようにがんばります・・・！
- まだこれからサーバーサイドとの接続が待っていると思うので、まずはプリセットできるところをJSで書いている状況ですが、ここができていないとサーバーが出てきたときに大変なことになりそうなので、ひとつひとつ身につけたいと思います。
