##### 公開:2023/07/23 更新:2023/07/23 writer:a_sa_hi([@asahi_robocuper](https://twitter.com/asahi_robocuper))
---
<br>

# ArduinoでL3GD20を動かしてみた

<br>
<img src="title.png" class="postpic"> 
<br>

## 初めに
---
どうも、a_sa_hiです。<br>
今シーズンのロボットで方向制御をするために必要なジャイロセンサを選定していたところ、L3GD20(L3GD20H)を発見しました。<br>
ネットに使い方の情報自体は書いてあるのですが、方向制御ができるレベルの説明がされているサイトを発見できなかったので、備忘録ということもかねて解説しようかなと思います。<br>
<br>
今回この記事を作成するにあたり、以下の環境を使用しましたが、PlatformIOではなく通常のArduino IDEでも問題なく動作することを確認しております。<br>


<br>
<br>