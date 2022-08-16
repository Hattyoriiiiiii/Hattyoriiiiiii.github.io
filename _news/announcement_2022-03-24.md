---
layout: post
date: 2022-03-24
title: 100 Programにて「Mobile trash can」を発表しました
inline: false
---

<br>

2/10 ~ 3/24の6週間、[「100 Program」](https://100.todaitotexas.com)に参加しました。

音声に反応して移動してくるゴミ箱を作りました。作品名は、「自立移動ゴミ箱」。

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mobile_trash_can_summary.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<br>

## ゴミを捨てに行くのがめんどくさい

<br>

ゴミ箱は家の中の片隅にあるだけで、赤枠で示したような、自分の普段行動する範囲にはあまり置いていない場合が多いと思います。

家具の配置を考慮すると、ゴミ箱は家の片隅に追いやられる事が多い存在です。

「パッと出たゴミをポイッと捨てることができないのがだるい」これが課題です。

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mobile_trash_can_intro.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mobile_trash_can_intro2left.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mobile_trash_can_intro2right.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    ゴミ箱に向かって投げて外したことがあるはず
</div>

<br>

## 技術面

<br>

音声認識、自己位置推定と移動、画像認識という技術を使って自分のところまで移動してくるゴミ箱を作成しました。

まず、「ゴミ箱」という音声に反応して、ゴミ箱が移動を開始します。
次に、LIDARという機器を用いる事で部屋の地図を作成し、ゴミ箱がどこにいるのかを認識しています。

さらに、カメラを用いることで人の顔や下半身などに反応して目的地まで移動します。

現在は全体を通したデバイスの完成はしていませんが、それぞれの動作確認までが完了しています。

***

- 音声認識
  - webカメラが音声も拾ってくれました。
  - `PyAudio`、`SpeechRecognition`、`Julius`を使って単語を認識します。
- 自己位置推定と移動 (SLAM)
  - LIDARにはRPLIDAR A1 M8を用いました。
  - navigationは`cartographer`を利用
  - `rosserial`を使用することで、Arduinoが生成された`cmd_vel`を受け取り、メカナムホイールを制御しています。
- 画像認識
  - 一般的なwebカメラを用いました。
  - 用いたライブラリは`OpenCV`です。

<br>

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mobile_trash_can_hardware.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<br>

動画は後で載せます。