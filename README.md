# Review1

太久沒上社課了，讓我幫大家複習我們之前學的東西  
p.s. 點擊標題連結可以傳送到完整版講義，忘的一乾二淨的人可以直接點連結，做全面的複習  
p.s. 這邊會快速帶過，如果有任何問題就...自己複習，我不會重上一次  

# [class1](https://github.com/pcic35-html/class1)

## [How to start](https://github.com/pcic35-html/class1#how-to-start)

我們使用<https://repl.it>來撰寫、佈署、發布網頁

## [html-基礎模板](https://github.com/pcic35-html/class1#html-基礎模板)

宣告程式語言為html：  
```html
<!DOCTYPE html>
```
把它加在程式碼第一行

單個元素：  
```html
<tagname>value</tagname>
```

- `<tagname>`：元素的頭、開始，可視作`(`
- `</tagname>`：元素的尾、結束，可視作`)`
- 記得！要有頭有尾
- `value`：包在元素內的東西，通常可以是文字、子元素

（通常）基礎樣板：  
```html
<!DOCTYPE html>
<html>
	<head>
	</head>

	<body>
	</body>
</html>
```

## [縮排](https://github.com/pcic35-html/class1#縮排)

用來區別哪個元素包了什麼東西、被什麼母元素包起來、同一層間有哪些其他元素  
最簡單的例子：  
```txt
老師說：｢
  下課，但
  ｢
    沒交周記的人、
    剛剛上課睡覺的人、
    被我點到的人
  ｣
  不准下課
｣
甲人：｢
  好耶，打球去！
｣
```
透過縮排，我們可以清楚知道：  
- `下課，但...不准下課` 是老師說的話
- `沒交周記...被我點到的人` 是不能下課的人
  - 這段話中的 `我` 由上一層元素 `老師說：...` 可以知道這個 `我` 指的是老師
- `甲人...` 在 `老師說...` 下面，所以 `甲人...` 是比較後發生or比較後處理的東西

## [title](https://github.com/pcic35-html/class1#title-抬頭)

看看頁簽的那段文字，他就是title  
```html
<html>
	<head>
		<title>title名稱</title>
	</head>
</html>
```

## [favicon](https://github.com/pcic35-html/class1#favicon)

看看頁簽那個icon，就是他  
```html
<!DOCTYPE html>
<html>
	<head>
		<link rel="icon" href="圖片連結、檔名、位置.png">
	</head>
</html>
```

## [p](https://github.com/pcic35-html/class1#hello-world)

```html
<!DOCTYPE html>
<html>
	<head>
    ...
	</head>
  <body>
    <p>我是第一段</p>
    <p>我是第二段</p>
  </body>
</html>
```

## [br](https://github.com/pcic35-html/class1#換行)

```html
<p>
  第一行<br>
  第二行<br>
  第三行
</p>
```

## [header (h)](https://github.com/pcic35-html/class1#標題)

```html
<h1>我是最大的標題</h1>
<h2>我是二等標題</h2>
...
<h6>我是最小的標題</h6>
<p>我是內文</p>
<h7>沒有七等標題</h7><!--這是不合法的寫法-->
```

## [note](https://github.com/pcic35-html/class1#note)

首先在註解開始處打上 `<!--`  
在結尾打上 `-->`  
被包起來的東西會被忽略，你可以在這你面寫註解，或一些[怪東東](https://youtu.be/dQw4w9WgXcQ)
```html
<!---
Never gonna give you up.
<p>Never gonna let you down.</p>
-->
```

## [hyperlink (a)](https://github.com/pcic35-html/class1#超連結)

```html
<a
	href="https://你的連結.請寫在/這邊"
>
  任何東西here
</a>

<p>
  我喜歡<a href="https://youtu.be/dQw4w9WgXcQ">這首歌</a>！
</p>
```

## [img](https://github.com/pcic35-html/class1#圖片)

```html
<img
	src="圖片網址here，概念和favicon一樣"
	alt="如果圖片載入不了，則顯示這則訊息，可有可無"
>

<img src="loli.png" alt="圖片被KagariET01搬走辣">
```

## [style](https://github.com/pcic35-html/class1#樣式)

```html
<tagname_here
	style="
		name: value;
		name2: value;

    color:red;
	"
>
  我是紅色文字
</tagname_here>
```

# [class2](https://github.com/pcic35-html/class2)

## [CSS](https://github.com/pcic35-html/class2#css-basic)

`style.css`
> ```css
> tagname_here{
> 	name: value;
> }
> 
> p{
> 	color: #fff;
> 	font-size: 20px;
> }
> 
> body{
> 	background-color: #000;
> }
> ```

## [class](https://github.com/pcic35-html/class2#class)

`style.css`
> ```css
> .a{
> 	color:#f00;
> }
> .b{
> 	color:#0f0;
> }
> .c{
> 	color:#00f;
> }
> ```

`index.html`
> ```html
> <p class="a"></p>
> <p class="b"></p>
> <p class="c"></p>
> ```


## [div](https://github.com/pcic35-html/class2#div)

`<div> </div>`

## [Button](https://github.com/pcic35-html/class2#button)

`<button>Click Me!</button>`

# LICENSE
This work © 2024 by KagariET01 is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit <http://creativecommons.org/licenses/by-nc-sa/4.0/>  

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1">
