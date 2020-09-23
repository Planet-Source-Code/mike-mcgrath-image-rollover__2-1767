<div align="center">

## Image rollover<br/>by Mike McGrath

</div>

### Description

Run your mouse over either image to change both images. The swap image has been preloaded to be readily available when needed.

### Source Code

<!doctype html public "-//w3c//dtd html 4.0 transitional//en">
<html>
<head>
<title>rollovers</title>
<script type="text/javascript">
<!-- original: mike mcgrath (mike_mcgrath@lineone.net) -->
<!-- web site: http://website.lineone.net/~mike_mcgrath/index.htm -->
<!--
preload=new image();
preload.src="images/anim.gif";
//-->
</script>
</head>
<body>
<a href="javascript://"
	onmouseover="a.src='images/anim.gif'; b.src='images/anim.gif';"
	onmouseout= "a.src='images/clik.gif'; b.src='images/clik.gif';">
<img border=0 name="a" src="images/clik.gif"></a>
<p>
run your mouse over either image to change both images.<br>
the swap image has been preloaded to be readily available when needed.<br>
right-click and select view source for more details.
<p>
<a href="javascript://"
	onmouseover="a.src='images/anim.gif'; b.src='images/anim.gif';"
	onmouseout= "a.src='images/clik.gif'; b.src='images/clik.gif';">
<img border=0 name="b" src="images/clik.gif"></a>
</body>
</html>

