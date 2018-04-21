# CSS改变光标插入颜色

## src

1. 01.html --> [原生属性caret-color](https://mankeung.github.io/css-caret-color/src/01.html)

2. 02.html --> [普通标签](https://mankeung.github.io/css-caret-color/src/02.html)

3. 03.html --> [::first-line](https://mankeung.github.io/css-caret-color/src/03.html)

4. 04.html --> [混合处理](https://mankeung.github.io/css-caret-color/src/04.html)

## 知识点

+ [caret-color]('https://developer.mozilla.org/en-US/docs/Web/CSS/caret-color')

+ [contenteditable]('http://www.w3school.com.cn/html5/att_global_contenteditable.asp')

+ [::first-line]('http://www.w3school.com.cn/cssref/selector_first-line.asp')

## 结语

在我目前所掌握的前端技术认知中，IE浏览器下的输入光标的颜色自定义，怕是要借助JS才能实现，而且还不好实现，如何实时知道光标位置在哪里，什么时候消失什么时候没有是个很难实现的问题。例如移动端Safari浏览器下的原生的光标定位就会经常出现一些奇怪的问题，更不要提我们这种纯前端技术策略的实现了，一定会出现更多稀奇古怪的问题，投入产出比估计会很糟糕。所以更好的做法应该是忽略IE浏览器。
