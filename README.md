# Pagescroll jQuery Menu

Open Source jQuery PageScroll Menu.

## Features ##
* vertical or horizontal display
* absolute, fixed or inline styles
* left, right, top or bottom aligns
* configurable background color, font sizes, colors also configurable via CSS
* smooth animation during pagescroll
* fade in / fade out effect when user scrolling

## Usage ##
```javascript
<script type="text/javascript" src="http://code.jquery.com/jquery-1.11.0.min.js"></script> 
<script type="text/javascript" src="js/pjm.min.js"></script>
<script type="text/javascript">                                                                            
	jQuery(document).ready(function() {
		jQuery(".pagescroll-menu").pagescroll_menu({
			"position":"top",
			"type":"fixed",
			"bgcolor":"#000"
			});	
	});
</script>
```

## Adding Menu ##
Use the following format to add menu to your website:
```html
	<ul class="pagescroll-menu">
            <li><a href="#home">HOME</a></li>
            <li><a href="#section2">FEATURES</a></li>
            <li><a href="#section3">POSITION</a></li>
            <li><a href="#section4">OPTIONS</a></li>
            <li><a href="#download">DOWNLOAD</a></li>
    </ul>
```
Then don't forget to add anchors to the website: 
```html
<a id="section2"></a>
```

## License ##

jQuery PageScroll Menu is published under the MIT license.

## Other Projects ##

#### [Board Game Upgrades](https://boardgameset.com) ####

## WordPress Projects ##

#### [Swift Woo Search - WooCommerce Smart Search Plugin](https://swiftwoosearch.com) ####
