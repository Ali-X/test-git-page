## Ali-X.github.io
# Hairsal
### Front end test project
#### Lesson 0
##### _Mate Academy_
###### **Alina Neshchebnaya**

+ Menu
1. Home
2. Haircut
3. Services
4. About
5. Book online
6. Contact

- Socials
1. Facebook
2. Twitter
3. Instagram
4. Youtube

[Web site link](https://ali-x.github.io/)

* Face of the web site

_not me(_
![Girl](https://ali-x.github.io/images/hero_bg_1.jpg "Good girl")

* Code

The next stuff is peace of `js code` for site menu.

```javascript
var siteMenuClone = function() {

		$('.js-clone-nav').each(function() {
			var $this = $(this);
			$this.clone().attr('class', 'site-nav-wrap').appendTo('.site-mobile-menu-body');
		});
```
* Opening Hours

| Mon – Fri     | Saturday      | Sunday |
| ------------- |:-------------:| ------:|
| 10:00 AM – 8:30 PM | Closed | 10:00 AM – 8:30 PM |

* Rights 

> Copyright ©2018 All rights reserved | This template is made with  by Colorlib
