# CSSPractice
Some practice about CSS.

### ball.html

实现了小球（60px * 60px）在4s内向右移动400px，在另一个4s回到原来的位置。  
同时向右移动时，小球变为原来的2倍。向左移动时，小球大小恢复到初始大小。

### vcentered.css  

基本的html中，有一个父元素container、子元素box。
```
<div id="container">
    <div id="box">
        this is a box
    </div>
</div>
```
css中实现了子元素box的水平垂直居中，包括三种方法：绝对定位、flex布局、transform。

### twofixed.css

实现了left、right两个元素两边固定，middle元素中间自适应的样式，包括三种方法：浮动布局float、绝对定位、flex布局。
