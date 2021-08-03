# Punk Building Block Series



## Original CryptoPunks Series (24×24)






##  DIY (Do-It-Yourself) - Yes, You Can! Design Your Own Punks Using the Punk (Building) Blocks

Use the free [ImageMagick](https://imagemagick.org/) tools
to make your own punks.


Let's make punk #7804 - a super rare alien
![](original/alien-male.png)
with a capforward
![](original/capforward.png),
smallshades
![](original/smallshades.png)
and a pipe
![](original/pipe.png)
from scratch:

```
$ magick convert alien-male.png \
                 capforward.png \
                 smallshades.png \
                 pipe.png \
         -background none -flatten punk7804.png
```

<!--
$ magick convert alien-male.png capforward.png smallshades.png pipe.png -background none -flatten punk7804.png
-->

Now open up the new `punk7804.png`. Enjoy your million-dollar punk look-a-alike. Yes, it's
a 100% true authentic pixel original.

![](i/punk7804.png)



Zooming In - 2x, 4x


Scale up the image by doubling the pixels (that is, use the `-filter point` option).
Let's try 2x (that is, 200%):

```
$ magick convert punk7804.png \
         -filter point -resize 200% punk7804x2.png
```

<!--
$ magick convert punk7804.png -filter point -resize 200% punk7804x2.png
 -->

![](i/punk7804x2)

And 4x (that is, 400%):

```
$ magick convert punk7804.png \
         -filter point -resize 400% punk7804x4.png
```

![](i/punk7804x4)

<!--
$ magick convert punk7804.png -filter point -resize 400% punk7804x4.png
 -->



That's it.



## Questions? Comments?

Post them on the [CryptoPunksDev reddit](https://old.reddit.com/r/CryptoPunksDev). Thanks.
