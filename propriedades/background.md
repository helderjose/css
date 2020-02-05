# Background
https://www.w3schools.com/css/css_background.asp
No fim da página tem exercícios.


## background-blend-mode
https://www.w3schools.com/cssref/pr_background-blend-mode.asp
Valores no site.
The background-blend-mode property defines the blending mode of each background layer (color and/or image).
Default value: 	normal
Inherited: 	no
Animatable: 	no. Read about animatable
Version: 	CSS3
JavaScript syntax: 	object.style.backgroundBlendMode="screen"

## background-color
https://www.w3schools.com/cssref/pr_background-color.asp
The background-color property specifies the background color of an element.
background-color: lightblue;


## background-image:
https://www.w3schools.com/cssref/pr_background-image.asp
The background-image property specifies an image to use as the background of an element.
By default, the image is repeated so it covers the entire element.
background-image: url("paper.gif");


## background-repeat
https://www.w3schools.com/cssref/pr_background-repeat.asp
No site tem os valores das propriedades e a sintaxe.

By default, the background-image property repeats an image both horizontally and vertically.
Some images should be repeated only horizontally or vertically, or they will look strange, like this:
Options:
background-repeat: repeat-x;
background-repeat: repeat-y;
background-repeat: no-repeat;

Default value: 	repeat
Inherited: 	no
Animatable: 	no. Read about animatable


## background-position
https://www.w3schools.com/cssref/pr_background-position.asp
The background-position property is used to specify the position of the background image.
No link tem os valores possíveis.

Default value: 	0% 0%
Inherited: 	no
Animatable: 	yes. Read about animatable
Version: 	CSS1
JavaScript syntax: 	object.style.backgroundPosition="center"

Examples:
background-position: right top;


## background-attachment
https://www.w3schools.com/cssref/pr_background-attachment.asp
No site tem os valores das propriedades e a sintaxe.
The background-attachment property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page):
background-attachment: fixed;
background-attachment: scroll;


## background-size
https://www.w3schools.com/cssref/css3_pr_background-size.asp
No site tem os valores possíveis.

Specify the size of a background-image with "auto" and in pixels.
The background-size property specifies the size of the background images.
There are four different syntaxes you can use with this property: the keyword syntax ("auto", "cover" and "contain"), the one-value syntax (sets the width of the image (height becomes "auto"), the two-value syntax (first value: width of the image, second value: height), and the multiple background syntax (separated with comma).

Default value: 	auto
Inherited: 	no
Animatable: 	yes. Read about animatable


## background-origin
https://www.w3schools.com/cssref/css3_pr_background-origin.asp
No site tem os valores possíveis e a sintaxe.

The background-origin property specifies the origin position (the background positioning area) of a background image.
Note: This property has no effect if background-attachment is "fixed".

Default value: 	padding-box
Inherited: 	no
Animatable: 	no. Read about animatable
JavaScript syntax: 	object.style.backgroundOrigin="content-box"


## background-clip
https://www.w3schools.com/cssref/css3_pr_background-clip.asp
No site tem os valores possíveis e a sintaxe.
The background-clip property defines how far the
background (color or image) should extend within an element.

Default value: 	border-box
Inherited: 	no
Animatable: 	no. Read about animatable
Version: 	CSS3
JavaScript syntax: 	object.style.backgroundClip="content-box"




# CSS background - Shorthand property
https://www.w3schools.com/cssref/css3_pr_background.asp
To shorten the code, it is also possible to specify all the background properties in one single property. This is called a shorthand property.
The shorthand property for background is background.
When using the shorthand property the order of the property values is:
background-color
background-image
background-repeat
background-attachment
background-position
It does not matter if one of the property values is missing, as long as the other ones are in this order.

Ex:
background: #ffffff url("img_tree.png") no-repeat right top;