```
有时候，我们需要给多个元素添加同一个动画，播放后，不难发现它们会一起运动，一起结束，这样就会显得很平淡无奇。

那么如何将动画变得稍微有趣一点呢？
很简单，既然它们都是同一时刻开始运动的，那么让它们不在同一时刻运动不就可以了吗。
如何让它们不在同一时刻运动呢？注意到CSS动画有延迟（delay）这一属性。

举个栗子，比如有十个元素播放十个动画，将第二个元素的动画播放时间设定为比第一个元素晚0.5秒（也就是将延迟设为0.5秒），
其他元素以此类推，这样它们就会错开来，形成一种独特的视觉效果。
```

效果图：<br><br>
<img src="staggeredWaveLoading.gif" width="300px">

### 交错动画：`通过设置不同的延迟时间，达到动画交错播放的效果`。
