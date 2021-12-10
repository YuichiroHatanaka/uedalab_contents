---
Keywords: Raspberry pi
Copyright: 
---

# A challenge of mobile robot navigation with just one Raspberry Pi 3B

## 目的

Raspberry Pi 3B のスペックでナビゲーションを行えるのかを調査することを目的とします。


## 実験
RT CORPORATION の Raspberry Pi Cat を用いて実験しました。

![](Raspberry-Pi-Cat.png)

Packageは以下のものを使用しました。


[raspicat_navigation](https://github.com/uhobeike/raspicat_navigation)

実験場所は、千葉工業大学津田沼キャンパスの2号館19階の廊下です。
この区間を一周させることで、ナビゲーションが行えたとします。

地図は、gmapping[http://wiki.ros.org/gmapping] で作成しました。

resolutionが0.05の地図ではナビゲーションを行うことができなかったため、resolutionを0.30に設定しました。

![new](AnyConv.com__2_19.png)

rezolution 0.05

![19階地図](map_tudanumakai.png)

rezolution 0.30


## 実験結果

Youtubeにて、走行時の動画です。

[![](https://img.youtube.com/vi/tmFjHElCXa8/0.jpg)](https://www.youtube.com/watch?v=tmFjHElCXa8)

目的である廊下の一周が成功しました。

## 考察・今後の活動

本実験で、地図の解像度・

今後は、千葉工業大学津田沼キャンパス内の指定された区間を走行することを目標とします。
