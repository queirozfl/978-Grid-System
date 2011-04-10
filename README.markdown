978 Grid System
===============

This repository contains a collection of design templates and code to quickly get you up and running 
with the 978 (and companion) grid systems. As we get free time, we will continue to improve this 
collection over time. We encourage you to contribute as well!

Learn more about 978 for web design:
<http://978.gs/>

The 978 and companion grid systems are brought to you by Brothers Roloff:
<http://www.brothersroloff.com/>


CSS Usage
---------

### Include the CSS framework in your page ###

	<link rel="stylesheet" href="978.css" />

Note: Do not include the "demo-files" CSS, as it is for demonstration purposes only.


### Wrap your layout in a container element ###

	<div class="layout-978">


### Add rows and columns to achieve the desired layout ###

978 is a 12 column grid system. Therefore, you can add as many columns to a row as long as they 
total the number 12. Be sure to total the appropriate number of columns when using the companion 
grid systems CSS.

	<div class="row">
		<div class="col2">138px</div>
		<div class="col10">810px</div>
		<div class="row-end">&nbsp;</div>
	</div>

Don't forget to add a "row-end" element immediately after your last column of a row. Placing the 
ending element here will allow you to apply a background image or color to each row separately and 
it will grow/repeat vertically to the height of your longest column.