### 用JS分割文本
> - *staggeredLandInText.html*

用 JS 将句子或单词分割成字母，并给每个字母加上不同延时的动画，同样也很华丽。
<br>

效果图：<br><br>
<img src="staggeredLandInText.gif" width="900px">

<hr>

> - *revealText.html*

一般我们都是从第一个元素开始交错的。但如果要从中间元素开始交错的话，就要给当前元素的延时各加上一个值，这个值就是中间元素的下标到当前元素的下标的距离（也就是下标之差的绝对值）与步长的乘积，即：`delay + Math.abs(i - middle) * step`，其中中间元素的下标 `middle = letters.filter(e => e !== "").length / 2`。
<br>

效果图：<br><br>
<img src="revealText.gif" width="900px">