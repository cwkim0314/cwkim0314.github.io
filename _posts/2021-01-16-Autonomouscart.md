---
layout: post
comments: true
title: Autonomous Driving Trolley, MEME
categories: [AI]
---

### 自動走行カートMEME、プロジェクト紹介  
自律走行カートとは、カメラでお客様を認識し、自発的にお客様に付いていくカートです。  
顧客がカートを直接引きなくても、カートが自発的に動くので顧客はより便利なショッピングができます。  
カートにはLiDARセンサーが取り付けられ、LiDARセンサーでSLAMとNavigation技術を利用して周辺状況を把握し、Path  TrackingとPath  Planningを具現します。  
また、従来の自動運転カートとは一線を画したものがあります。  
音声認識技術を適用したものです。 自動運転カートの名前、  MEMEとも関係する部分です。  
Accuracyが高いimage trackingアルゴリズムを使用しても、お客様の多いマートではカートがお客様を認識する上でエラーが生じることがあります。  
カートが最初に認識したお客様についていくと逃してしまうのです。  
そのような場合にお客様がカートの名前を呼ぶと、カートはお客様についていくことになります。  
自動運転カートは一般のお客様にも役立つが、必要な状況で役に立つことになる。  
マートには歩行が自由なお客様だけが来るのではありません。  
車椅子に乗ったり、ベビーカーをお持ちのお客様に便利に使われるでしょう。  

![CartMEME](https://github.com/cwkim0314/cwkim0314.github.io/tree/master/_posts/CartMEME.PNG)

### 使用されるアルゴリズム
*   YOLO
*   EfficientNet
*   DeepSORT
*   SLAM(LiDAR)
*   Navigation(LiDAR)
*   LSTM

### 詳しくはGithubでご確認ください！
[Github](https://github.com/cwkim0314/Autonomous-Driving-Trolley-MEME)
