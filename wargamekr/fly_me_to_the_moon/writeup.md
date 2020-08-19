# wargame.krのfly_me_to_the_moon(189p)のwrite up
## 1.遊んでみる
<img src="./game.png" width=500><br>
すると、下の画像のような画面が表示される<br>
<img src="./game2.png" width=500><br>
どうやらflagを取るには31337点必要らしいが、手動でクリアするのは考えられない。<br>

## 2.Burpでリクエストを見てみる
Burpを使用して、リクエストを見てみると<br>
<img src="./score.png" width=500><br>
このscoreパラメータを31337点以上にしてあげれば、クリア出来そう<br>
<img src="./changed-score.png" width=500><br>
出来た！<br>
<img src="./flag.png" width=500><br>

