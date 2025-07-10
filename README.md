# Web-Development-day-42
CSS Transform
CSS 2D Transform
This property allows the content to be restructured in ways like translate, rotate, scale, or skew, etc.

As it is 2D, therefore the content is transformed into x and y dimensions.

Translate
This property transforms the element’s position along x or y or both x and y directions.

Syntax: transform: translate(x, y);

Rotate
This property rotates the content of the division either anticlockwise or clockwise according to the degree of rotation. The values are taken in degrees, and adding a negative sign makes the rotation anticlockwise.

Syntax: transform: rotate(value);

Eg:

transform: rotate(-10deg);

Scale
This property rescales the width and height of the division in the ratio to the original dimensions.

For example:

transform: scale(1.4, 1.2);

This code will increase the width and height by 1.4 and 1.2 times the original, respectively.


Note: This property also changes the aspect ratio of the div, so it has to be used accordingly.

Skew
This property helps in adding a slant or skew to a division. (Skew: A pair of lines neither intersecting nor parallel)

Eg:

transform: skew(10deg, 5deg);

You can also choose to give the values for skew in a particular axis by adding a postfix with skew: skewX.

Note: The properties for 3D Transform are also identical; a new dimension z is included in it.

