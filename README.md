# musicrotate
H5页面音乐图标转动插件
#使用方式
在CSS中添加rotate.css内的动画函数或自行定义，其他样式自行定义<br />
html布局：
```html
<div class='musicBtn'>
    <audio id='musicId' src="media/music.mp3" autobuffer autoplay autoloop loop></audio>
    <img src="img/musicon.png" class='music '>
</div>
</textarea>
```
在JS中执行
```html
$('.musicBtn').musicBtn({
    // 'imgonSrc': 'img/musicon.png', //播放时的img，可省略
    // 'imgoffSrc': 'img/musicoff.png', //暂停的img，可省略
    // 'audioId':'musicId' //播放音乐的audio或video，可省略
  }); 
  ```
