## Esis Denis

### Contact Info
 - Email: [presetslr@gmail.com](mailto:presetslr@gmail.com)
 - Tel: [+375 29 147-70-06](tel:+375291477006)
 - Telegram: [@Centrovoy](https://t.me/centrovoy)

### Summary
30 years.  
Now I want to change my life.  
I want to become a good programmer.  
I have to work hard and learn a lot.  
I work well with others and prove myself as a positive team player.

 - BORN TO BE
 
 ### Profiles
[Github](https://github.com/presetslrdev), [Vk](https://vk.com/yesis)

### Skills
 - Technologies / Languages: HTML & CSS, JavaScript, C++ (Arduino), Java (core), PHP
 - CSS Frameworks: Bootstrap
 - JS Lib / Frameworks: jQuery, Vue.js
 - CSS preprocessors: Sass (Scss)
 - Metodologies: BEM
 - Tools: Gulp, Webpack
 - CMS: Wordpress, Opencart
 - Graphic: Photoshop, Figma
 
 ### Code
 ```javascript
	var buttonHide = $('.b-language-selection__button');
	var wrapper = $('.b-language-selection__wrapper');
	var buttonClose = $('.b-language-selection__close span');
	function hundler() {
		wrapper.removeClass('animationIn');
		buttonHide.off("animationend", hundler);
	};
	function showLanguageSelectionBlock(event) {
		wrapper.show().addClass('animationBg animationIn');
		buttonClose.addClass('animationBtnHide');
		buttonHide.on("animationend", hundler);
		event.preventDefault();
	}
	function hideLanguageSelectionBlock(event) {
		wrapper.hide();
		event.preventDefault();
	};
	window.addEventListener("keydown", function (e) {
		if (e.keyCode == 27) {
			hideLanguageSelectionBlock();
		}
	}, true);
```
