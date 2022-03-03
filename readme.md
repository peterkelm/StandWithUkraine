# Simple \#StandWithUkraine html/css banner  
Show solidarity with the people of Ukraine - right on your website!

## 1. Download the code.

## 2. Link to the stylesheet file
In the HTML `<header>` section add a line like this: `<link rel="stylesheet" type="text/css" href="/css/standwithukraine.css" />`
Adjust the href parameter to reflect the location of the file on your web server.
Alternatively you can also copy the CSS styling code from the file into an embedded style element like this:

```
<style type="text/css">
...
</style>
```

## 3. Add the code wherever you want to display the banner
Paste the code snippet below right before the `</body>` tag in your html code. Adjust the href attribute (the ´\#your_url_goes_here` part) to point to the link you'd like to share.

```
<div id="standwithukraine" class="right">
	<a href="#your_url_goes_here">&#35;StandWithUkraine</a>
</div>
```

## License:
BSD 3-clause license
