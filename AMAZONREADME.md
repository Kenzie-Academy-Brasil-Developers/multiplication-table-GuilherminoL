# Supplemental Challenge: Multiplication Table #

Write an HTML page that uses Javascript to draw a 10x10 multiplication table. The key idea is to use two nested loops _(one loop inside another)_ for the rows and columns of the table.

Pretend you are designing your page for elementary school teachers to use in a classroom. It should look roughly like this:

![](https://i.snag.gy/xf0HnX.jpg)

### Getting Started ###

You can use the following HTML document as a starting point:

```html
<!DOCTYPE html>
<html>
	<head>
		<title>Multiplication Table</title>
		<style>
			.cell {
				display: inline-block;
				width: 30px; height: 30px;
				text-align: right;
			}
        	.header {
				background: lightblue;
			}
    	</style>
	</head>

	<body>
    	<h1>Multiplication Table</h1>
    	<script>
        	// output the header row
        	document.write('<span class="cell header">&times;</span>');
        	for (let i = 0; i <= 10; i++) {
        		document.write('<span class="cell header">' + i + '</span>');
        	}
        	document.write('<br>');
			// TODO: Write two nested for loops to output the rest of the multiplication table
    	</script>
	</body>
</html>
```

### Bonus ###

For an additional challenge:
*   Provide controls to allow generating tables of different sizes (e.g. 12x12, 16x16)
*   Provide controls to change the colors or styles of the table on the fly.