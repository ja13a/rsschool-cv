<style>
	.image-block {
		display: inline-block;
		vertical-align: top;
		position: relative;
	}

	.profile-image {
		border-radius: 8px;
		display: block;
	}

	.image-block:before { 
		border-radius: 0 0 8px 8px;
		content: attr(title); 
		box-sizing: border-box;
		width: 100%;
		padding: 15px;
		position: absolute;
		z-index: 2;
		left: 0;
		bottom: 0;
		background-color: rgba(0, 0, 0, .5);
		text-align: center;
		color: #ffffff;
		font: bold 12px , sans-serif;
	}
</style>

## Sergey Suvorov
<div class="image-block" title="My profile picture almost everywhere">
	<img class="profile-image" src="https://i.imgur.com/ycmGu8C.jpeg" title="me IRL" alt="me IRL" width="300"/>
</div>

***

## Contacts:
🇷🇺 Saint-Petersburg, Russia \
📬 suvorovsergey99@gmail.com \
💬 https://t.me/j4134 \
🐙 https://github.com/ja13a

***

## Skills and Proficiency:
- HTML, CSS/SCSS
- JavaScript, Typescript,
- React, MobX
- Parcel, Webpack (in process...)
- Git, GitHub, Bitbucket

***

## Code example:

##### Codewars task:
Define a function that takes in two non-negative integers *a* and *b* and returns the last decimal digit of $a^b$. Note that *a* and *b* may be very large!

For example, the last decimal digit of $9^7$ is 9, since $9^7$ = 4782969. The last decimal digit of ${(2^{200})}^{2^{300}}$ , which has over $10^{92}$ decimal digits, is 6. Also, please take $0^0$ to be 1.

##### Code:
```javascript
var lastDigit = function(str1, str2) {
  return (str2 === "0") ? 1 : Math.pow(str1.slice(-1), (str2.slice(-2) - (Math.trunc(str2.slice(-2) / 4) - 1) * 4)) % 10;
}
```
***

<img style="background-color: #fff" alt="rsschool-logo" src="https://i.imgur.com/hWj1yK6.png" width="100px" >
