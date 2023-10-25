# PDPlayer

- Preview: [PDPlayer](https://pardnchiu.github.io/PDPlayer-js/)
- Developer: [Pardn Chiu](mailto:chiuchingwei@icloud.com)
- Icons: [Font Awesome 6](https://fontawesome.com)

<br>

簡易影片控制器 (包含 Youtube 影片)<br>

按鈕可自由添加減少、排列組合<br>

且mobile 在playsinline 的狀態下可真正做到fullscreen<br>

<br>


```Javascript
const player = new PDPlayer({
    /* Youtube 影片ID 或 其他影片來源 */
    videoId: "UmR9zlez4OE"
    src: "/img/sample.mp4",
    /* 預設參數 */
    volume: 100,    //預設音量
    mute: false,    //預設靜音
    /* 控制器 */
    panel: [
        "play",     //播放鍵
        "timebar",  //進度條
        "time",     //進度時間
        "mute",     //靜音鍵
        "volume",   //音量鍵
        "rate",     //速率鍵
        "full",     //影片
    ],
    event: {
        ready: function() {
            console.log("ready");
        },
        playing: function() {
            console.log("playing");
        },
        pause: function() {
            console.log("pause");
        },
        end: function() {
            console.log("end");
        }
    }
});
```
<br>

Copyright (c) 2023 [Pardn Ltd](mailto:mail@pardn.ltd)
