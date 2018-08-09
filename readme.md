Turn.js 是一个JavaScript库，能够将HTML内容组织成看起来像一本真正的书籍或杂志，用到HTML5的所有优点。turn.js是最合适基于HTML5实现类似杂志，书籍，目录的效果。它适用于大多数的浏览器和设备，轻量级，只有10K。
六大特性：
可以工作在 iPad 和 iPhone上
简单，漂亮，强大的API。.
可以通过Ajax请求动态加载页面。
纯 HTML5/CSS3内容。
两种过渡效果。
可以工作在旧浏览器中比如：IE 8。通过turn.html4.js实现。


#### Usage

**CSS code:**
```css
#magazine{
	width: 800px;
	height: 400px;
}
#magazine .turn-page{
	background-color:#ccc;
}
```

**HTML code:**
```html
<div id="magazine">
	<div><span class="text">Page 1</span></div>
	<div><span class="text">Page 2</span></div>
	<div><span class="text">Page 3</span></div>
</div>
```

**JavaScript code:**
```javascript
$('#magazine').turn({gradients: true, acceleration: true});
```

#### Requirements

jQuery 1.7 or later

#### Browser support
* Chrome 12, Safari 5, Firefox 10, IE 9

#### License
Released under a non-commercial BSD license

[Full documentation](https://github.com/blasten/turn.js/wiki/Reference)

* * *

[turnjs.com](http://www.turnjs.com/)
