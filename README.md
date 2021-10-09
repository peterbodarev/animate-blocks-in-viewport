# Animate blocks in viewport ⇒ [Demo](https://animate-blocks-in-viewport.netlify.app)

## Description

Simple site using flexbox with custom animated blocks in viewport

## Examples 👁️

based on [Responsive site using flexbox](https://github.com/peterbodarev/responsive-site-using-flexbox)

![screenshot](https://user-images.githubusercontent.com/91592743/136660142-945cda10-3d92-4803-a870-23b4d854cc78.png)

https://user-images.githubusercontent.com/91592743/136660145-f7674d45-007a-4c2b-8dca-6f8119fd5a7f.mp4

---

## Technologies used 🛠️

<h3 align="left"> &nbsp  &nbsp  &nbsp Programming languages</h3>

<a href="https://www.w3.org/html/" target="_blank"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" height="30"/> </a>
<a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" height="30"/> </a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" height="30"/> </a>

<h3 align="left"> &nbsp  &nbsp  &nbsp Helper apps</h3>
<a href="psdetch.com" target="_blank"> <img src="https://html-plus.in.ua/wp-content/uploads/2019/08/studio-psdetch.png" alt="psdetch.com" height="30"/> </a>

---

## Features 💡

⚡️ Fully Responsive\
⚡️ Custom block animation\
⚡️ Ease to use

## How To Use 🔧

Add `_anim-items` class for items you want to activate animation
Add `_anim-no-hide` class to show animation just once

```html
<div class="hi__title _anim-items _anim-no-hide">Привет, друг!</div>
<ul class="hi__list _anim-items">
	<li>У тебя все получится!</li>
	<li>Никогда не сдавайся!</li>
	<li>Сегодня ты уже знаешь больше чем вчера!</li>
	<li>Так держать!</li>
</ul>
```

Sett animation by using `_active` class in your css

```css
.hi__title {
	-webkit-transform: translate(30%, 0);
	transform: translate(30%, 0);
	opacity: 0;
	-webkit-transition: all 0.8s ease 0s;
	transition: all 0.8s ease 0s;
}
/* animation */
.hi__title._active {
	-webkit-transform: translate(0, 0);
	transform: translate(0, 0);
	opacity: 1;
}
```

---

## Acknowledgments 🎁

Thanks to
[Евгений Андриканич](https://fls.guru/) ,
[Vladilen Minin](https://www.youtube.com/c/VladilenMinin) ,
[CS50](https://cs50.harvard.edu/college/2021/fall/) ,
[Александр Лущенко](https://itgid.info/) ,
[Vadim Makeev](https://www.youtube.com/channel/UCaTfYudJUVA8cV_But8KZVQ) ,
[Safak](https://github.com/safak) ,
[Adrian Hajdin](https://www.completepathtojavascriptmastery.com/) ,
[Sumit Dey](https://www.youtube.com/c/BackbenchCoder)
for motivational and helpful content

---
