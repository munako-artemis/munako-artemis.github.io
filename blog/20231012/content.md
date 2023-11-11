##### 公開:2023/10/12 更新:2023/10/12 writer:a_sa_hi([@asahi_robocuper](https://twitter.com/asahi_robocuper))
---
<br>

# 2024シーズン初基板着弾！！

<br>
<img src="title.png" class="postpic"> 
<br>

## 初めに
---
どうも、a_sa_hiです。<br>
2024シーズンに入りましてようやくロボ河童らしい活動報告ができそうです。<br>
本当は僕ソフトウェア班のはずなのですがどういうわけかロボット設計に苦しめられることとなっています。<br>

<blockquote class="twitter-tweet" data-theme="dark"><p lang="ja" dir="ltr">なんかめちゃくちゃかっこいい機体できた <a href="https://t.co/ryydnf7Hnw">pic.twitter.com/ryydnf7Hnw</a></p>&mdash; a_sa_hi (@asahi_robocuper) <a href="https://twitter.com/asahi_robocuper/status/1690291532472217600?ref_src=twsrc%5Etfw">August 12, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<blockquote class="twitter-tweet" data-theme="dark"><p lang="ja" dir="ltr">ロボカップあるある <a href="https://t.co/5CL35AoDYS">pic.twitter.com/5CL35AoDYS</a></p>&mdash; a_sa_hi (@asahi_robocuper) <a href="https://twitter.com/asahi_robocuper/status/1711689706461933716?ref_src=twsrc%5Etfw">October 10, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

今回発注した基板は上のツイートのロボット用の基板です。この記事を制作している時点で2機目の設計が90%終わっています。<br>
このロボットは本戦で使うことはありませんが、練習として作ってみた形になります。<br>
<br>

## 基板について
---
これから紹介する発注基板に関しては、中国のPCB製造メーカーであるJLCPCBさんに発注をして生産していただいた基板になっています。
以前の全国大会機の時にも発注をしており、低価格で高クオリティーな基板を製作していただけるのでとてもおすすめです。<br>
今なら<u>新規ユーザーに54$(記事制作時時価で約8000円)のクーポンを配布している</u>ようです。また、Twitterアカウントのフォロー+DMにより追加の10$クーポンを貰えるようです。<br>
基板を作ってみたいという方はぜひJLCPCBさんを利用してはいかがでしょうか。以下にホームページとTwitterアカウントを記載しておきます。<br>

#### JLCPCBのホームページ：[JLCPCB](https://jlcpcb.com/JPV) <br>
#### JLCPCBのTwitter(X)：[JLCPCB_Japan](https://twitter.com/JLCPCB_Japan)
<br>

## 基板紹介
それでは早速今回僕が発注した基板について紹介していきたいと思います。

### 電源基板
<img src="3.jpg" class="postpic">
最初に紹介するのは電源基板です。<br>
ロボカッパーならお馴染み(?)村田製作所のDCDCコンバーターを用いた電源回路になっています。<br>
僕たちの使用用途でいえば、3セル(11.1v)のバッテリーの保護回路の搭載・DCDCを通したメイン基板(後述)の電源生成・モーター用の電源の生成の3つの機能を搭載しています。<br>
この基板結構ミスがありまして、まず電圧計をはめ込む穴が空いてませんでした。Edge-Cutsに線が引かれてるのかと思ったらSilkscreenに入ってて悲しくなりました。<br>
あともう一つ、バッテリーからの電圧が来てすぐのところのダイオードが逆向きになっていました。詳しくは下のツイート参照。(バッテリー刺した瞬間端子からスパーク発生して死ぬかと思った。)<br>
<blockquote class="twitter-tweet" data-theme="dark"><p lang="ja" dir="ltr">間違い探し<br>何が間違っているんでしょうか(白目 <a href="https://t.co/JhFV5HfcgQ">pic.twitter.com/JhFV5HfcgQ</a></p>&mdash; a_sa_hi (@asahi_robocuper) <a href="https://twitter.com/asahi_robocuper/status/1709808914139943267?ref_src=twsrc%5Etfw">October 5, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### メイン基板
<img src="1.jpg" class="postpic">
次に紹介するのはメイン基板です。<br>
メイン基板の役割としては、メインマイコン・ジャイロセンサ・カメラが主なものになります。
カメラのフットプリントが間違っていたこと以外はうまくいってて良かったです。<br>
お気に入りポイントはボタン3つとその下の自チームロゴ。マジでこれ作ってるときカッコよすぎてテンション上がってた。<br>
そうそう、この基板が一番分かりやすいんですが、コネクタ付近にそのピンの用途を書いておくことで回路図を見る手間を省くことができるのでとてもお勧めです。みんなもシルク拘ろうぜ！<br>

### ラインセンサ基板
<img src="2.jpg" class="postpic">
最後に紹介するのはラインセンサ基板です。<br>
昨年度の機体はラインセンサがあまり動いていなかったので、今回はちゃんと動かしてやろうと思い円形ラインとかいろいろしてました。結局一番完璧に動いた基板だったので良かったです。<br>
今は別の機体の設計中なのでもう弄りませんが、もしかしたらこのサイズじゃちょっと小さいかなとか思ってます。多分ラインアウトする未来しか見えない(n敗)<br>
<br>

## さいごに
以上で今回発注した基板の紹介は終わりです。<br>
2台目のロボット設計にしてはよくやったんじゃないかなと個人的には満足しています。ただいろいろ改善点も見られたので
そこは次の機体に活かして完璧に仕上げようと思ってます。次の機体が本戦出場予定の機体となるので気合い入れてがんばります！<br>

(4日で気合いで作った新機体のロボット、下に置いておきます。)
<blockquote class="twitter-tweet" data-theme="dark"><p lang="ja" dir="ltr">ギリ四連休中に形になった！！！！！！！！ <br>前回の機体からだいぶ成長できたのアツい！！！みんな見て！！！！！！ <br><br>(ちなみに <a href="https://twitter.com/Matchya_RCJ?ref_src=twsrc%5Etfw">@Matchya_RCJ</a> のを結構参考にしてたりしてなかったり) <a href="https://t.co/Bfs2ObvDMK">pic.twitter.com/Bfs2ObvDMK</a></p>&mdash; a_sa_hi (@asahi_robocuper) <a href="https://twitter.com/asahi_robocuper/status/1711258278968377754?ref_src=twsrc%5Etfw">October 9, 2023</a></blockquote>
<br>
<br>