# myled
ロボットシステム学の課題1

### 説明
Raspberry Pi 4 Model B を使用して、GPIOから出力し、LEDを点灯させるためのデバイスドライバ。
自分で端末に入力することで点滅させる。

### 配線
Groudと22番ピン GPIO25に、ブレッドボードを使ってLED、間に200Ω抵抗を入れて接続。

<img src="https://user-images.githubusercontent.com/93691873/146097169-59c92616-35e7-445e-a3e3-017734a13416.jpg" width="320px">

####回路図

<img src="https://user-images.githubusercontent.com/93691873/146373074-89b9f7fa-d537-4371-8747-0ad10247aa32.jpg" width="320px">

### デモ動画
https://youtu.be/MpiWRtNO24c

### 使用方法
LED発光　echo 1 > /dev/myled0
LED消灯　echo 0 > /dev/myled0

### ライセンス
GNU General Public License v3.0

### 著作者
Copyright (C) 2021 Ryuichi Ueda. All rights reserved.
