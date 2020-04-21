# Pointer.js
A JavaScript library for making a cool pointer

## Install Guide
>_Note: You need to import both js and css files._

1. Import js file from 'https://seattleowl.com/pointer.js/pointer.js', like so:

	```html
	<script src="https://seattleowl.com/pointer.js/pointer.js"></script>
	```
1. Do the same for the css:
		
	```html
	<link href="https://seattleowl.com/pointer.js/pointer.css" rel="stylesheet">
	```
1. Finally add this javascript code to customize your pointer:
		
	```javascript
	init_pointer({
		pointerColor: "purple", // Css color
		ringSize: 15, // Pixels
		ringClickSize: 10 // Pixels when clicking
	})
	```
		
You should now have something like the example in `/index.html`.
