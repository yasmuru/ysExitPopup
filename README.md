# YsExitPopup

ysExitPopup is a really simple jQuery exit modal plugin that shows a cookie-enabled modal popup when your cursor moves out of view. Useful to create a confirm dialog asking the users to confirm if they want to quit your webpage.

### Requires
Latest jQuery plugin js.

``` 
npm install ysexitpopup --save

```

Include YsExitPopup css and js files.

``` 
<link rel="stylesheet" href="../css/ysExit.css" type="text/css">
<script src="../js/jquery.min.js"></script>
<script src="../js/ysExit.min.js"></script>
```

### Example

```
var options = 
{
	debug: true,
    cookieValidity: 3,
    delay: 5
};
$('.test2').ysExit(options);
```

### Default options

Option | Description | Default
-------|-------------|--------
`cookieValidity`|Number of days to remember if the popup was closed|1
`closeOnOutsideClick`|If true the popup will close when clicked outside|true
`delay`|Delay in ms until the popup is registered|0
`debug`|If true, no cookie will be set to allow quick testing|false