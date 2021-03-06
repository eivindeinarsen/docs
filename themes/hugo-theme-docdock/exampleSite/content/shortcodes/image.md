+++
title = "image"
description = ""
+++

Images have a similar syntax to links but include a preceding exclamation point.

	![agence](https://github.com/vjeantet/vjeantet.fr/raw/master/static/images/sgthon/C.jpg)

![agence](https://github.com/vjeantet/vjeantet.fr/raw/master/static/images/sgthon/C.jpg)

## Resizing image

Add HTTP parameters `width` and/or `height` to the link image to resize the image. Values are CSS values (default is `auto`).


	![Hackathon](https://github.com/vjeantet/vjeantet.fr/raw/master/static/images/sgthon/C.jpg?height=80px)

![agence](https://github.com/vjeantet/vjeantet.fr/raw/master/static/images/sgthon/C.jpg?height=80px)


## Add CSS classes

Add a HTTP `classes` parameter to the link image to add CSS classes. `shadow` and `border` are available but you could define other ones.

	![s](https://github.com/vjeantet/vjeantet.fr/raw/master/static/images/sgthon/C.jpg?classes=border,shadow)

![agence](https://github.com/vjeantet/vjeantet.fr/raw/master/static/images/sgthon/C.jpg?classes=border,shadow)
