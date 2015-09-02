[![{:navgoco}](https://github.com/tefra/navgoco/raw/master/demo/navgoco.jpg)](http://www.komposta.net/article/navgoco)

A quick update to this plugin to use it as a npm package. Many thanks to the original creator of this plugin!

## Getting Started

Download the plugin, unzip it and copy the files to your application directory and load them inside your HTML.

```html
<head>
	<!-- Load JQuery -->
	<script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>
	<!-- Load jquery.navgoco plugin js and css files -->
	<script type="text/javascript" src="/navgoco/src/navgoco.js"></script>
	<link rel="stylesheet" href="/navgoco/src/navgoco.css" type="text/css" media="screen" />
</head>
```

Sample menu html and activation code:
```html
<script type="text/javascript">
  var options = {};
  var navgoco = require('navgoco');
  var menu = new navgoco(element, options);
</script>
```