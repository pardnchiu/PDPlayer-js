- Preview: [PDYTPlayer](https://pardnchiu.github.io/PDYTPlayer/)
- Developer: [Pardn Chiu](mailto:chiuchingwei@icloud.com)
- Icons: [Font Awesome 6](https://fontawesome.com)

<br>

簡易YTPlayer 控制器<br>

按鈕可自由添加減少、排列組合<br>

且mobile 在playsinline 的狀態下可真正做到fullscreen<br>


```
var PDYTPlayerConfig = {
  videoId: "UmR9zlez4OE", //預設影片ID
  volume: 10,             //預設音量
  mute: false,            //預設靜音
  panel: [        
    "play",       //播放鍵
    "timebar",    //進度條
    "time",       //進度時間
    "mute",       //靜音鍵
    "volume",     //音量鍵
    "rate",       //速率鍵
    "full"        //影片
  ]
};

function onPDYTPlayerReady () {
  console.log("準備完成")
};

function onPDYTPlayerStart () {
  console.log("開始")
};

function onPDYTPlayerEnd () {
  console.log("結束")
};
```
<br>

Copyright (c) 2022 [Pardn Ltd](mailto:mail@pardn.ltd)
