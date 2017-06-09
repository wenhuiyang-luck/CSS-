# CSS布局

#### 1. 两边固定宽度，中间自适应

- [圣杯布局](https://wenhuiyang-luck.github.io/CSS-Layout/圣杯布局/index.html)   

```html
<div id="header">#Header</div>
<div id="container">
    <div id="center" class="column">#center</div>
    <div id="left" class="column">#left</div>
    <div id="right" class="column">#right</div>
</div>
<div id="footer">#Footer</div>
```

- [双飞翼布局](https://wenhuiyang-luck.github.io/CSS-Layout/双飞翼布局/index.html)

```html
<div id="header">#Header</div>
<div id="container">	

    <div id="center" class="column">
        <!-- 内层div包裹center -->
        <div id="center_wrapper">#center</div>    
    </div>		

    <div id="left" class="column">#left</div>
    <div id="right" class="column">#right</div>
</div>
<div id="footer">#Footer</div>
```
