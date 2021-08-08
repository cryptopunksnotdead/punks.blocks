# Punk Building Block Series



## Original CryptoPunks Series (24×24)

Humans (Male/Female)
![](original/human-male_lighter.png)
![](original/human-male_light.png)
![](original/human-male_dark.png)
![](original/human-male_darker.png)
![](original/human-female_lighter.png)
![](original/human-female_light.png)
![](original/human-female_dark.png)
![](original/human-female_darker.png),
Aliens (Male)
![](original/alien-male.png),
Apes (Male),
![](original/ape-male.png),
Zombies (Male)
![](original/zombie-male.png).


Attributes - Crazy Hair ![](original/crazyhair.png),
Cap ![](original/cap.png),
Cap Forward ![](original/capforward.png),
Knitted Cap ![](original/knittedcap.png),
Headband ![](original/headband.png),
Small Shades ![](original/smallshades.png),
Pipe ![](original/pipe.png),
Smile ![](original/smile.png)


<!-- note:
       double check/todo: some attribute need a variant for females (width less by one or such)
       e.g. shades and others!!!!
-->



## Alien Invasion Series (24x24)

_Aliens in more colors (by degree on the HSL color wheel)_

Aliens (Male) in red (0°), orange (30°),  yellow (60°),
, chartreuse (90°), green (120°), magenta (°300), fuchsia (°330), and more.

![](alien-invasion/alien-male_0.png)
![](alien-invasion/alien-male_30.png)
![](alien-invasion/alien-male_60.png)
![](alien-invasion/alien-male_90.png)
![](alien-invasion/alien-male_120.png)
![](alien-invasion/alien-male_150.png)
![](alien-invasion/alien-male_180.png)
![](alien-invasion/alien-male_300.png)
![](alien-invasion/alien-male_330.png)



## All Caps Series (24x24)

_(Baseball) caps in more colors (by degree on the HSL color wheel)_

Caps in red (0°), orange (30°),
chartreuse (90°),
green (120°),
blue (240°),
magenta (300°),
fuchsia (330°), and more.

![](all-caps/cap_0.png)
![](all-caps/cap_30.png)
![](all-caps/cap_90.png)
![](all-caps/cap_120.png)
![](all-caps/cap_240.png)
![](all-caps/cap_300.png)
![](all-caps/cap_330.png)



## More Series (24x24)

_New species, new attributes_

Alien (female) ![](more/more_alien-female.png),
Ape (female) ![](more/more_ape-female.png),
Zombie (female) ![](more/more_zombie-female.png),
Demon (male / female) ![](more/more_demon-male.png) ![](more/more_demon-female.png),
Vampire (male / female) ![](more/more_vampire-male.png) ![](more/more_vampire-female.png),
Orc (male / female) ![](more/more_orc-male.png) ![](more/more_orc-female.png),
Skeleton (male / female) ![](more/more_skeleton-male.png) ![](more/more_skeleton-female.png),
Mummy (male / female) ![](more/more_mummy-male.png) ![](more/more_mummy-female.png),
Robot (male / female) ![](more/more_robot-male.png) ![](more/more_robot-female.png)



## Normie Series (24x24)

_Left-facing? Right-facing? Normie designs use the golden middle. Male? Female? Non-binary? Normie designs are unisex_

Human ![](normies/normie_human-lighter.png) ![](normies/normie_human-light.png) ![](normies/normie_human-dark.png) ![](normies/normie_human-darker.png),
Alien ![](normies/normie_alien.png),
Ape ![](normies/normie_ape.png),
Zombie  ![](normies/normie_zombie.png),
Demon  ![](normies/normie_demon.png),
Skeleton  ![](normies/normie_skeleton.png)



## Dodge Series (32x32)

_Shiba Inu dogs - Much wow_

Classic ![](dodge/dodge.png),
Dark ![](dodge/dodge-dark.png),
Zombie ![](dodge/dodge-zombie.png),
Alien ![](dodge/dodge-alien.png)



Attributes -
Beanie ![](dodge/beanie-dodge.png),
Cap  ![](dodge/cap-dodge.png),
Knitted Cap ![](dodge/knittedcap-dodge.png),
Cowboy Hat ![](dodge/cowboyhat-dodge.png),
Headband ![](dodge/headband-dodge.png),
Regular Shades  ![](dodge/regularshades-dodge.png),
Classic Shades ![](dodge/classicshades-dodge.png),
Small Shades  ![](dodge/smallshades-dodge.png),
Big Shades  ![](dodge/bigshades-dodge.png),
Eye Patch   ![](dodge/eyepatch-dodge.png),
Nerd Glasses  ![](dodge/nerdglasses-dodge.png),
3D Glasses ![](dodge/3dglasses-dodge.png),
Tiara ![](dodge/tiara-dodge.png)




##  DIY (Do-It-Yourself) - Yes, You Can! Design Your Own Punks Using the Punk (Building) Blocks

Use the [free ImageMagick tools](https://imagemagick.org)
to make your own punks.


### Alien with Cap Forward, Small Shades & Pipe

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
a 100% true authentic pixel ~~copy~~ original.

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

![](i/punk7804x2.png)

And 4x (that is, 400%):

```
$ magick convert punk7804.png \
         -filter point -resize 400% punk7804x4.png
```

![](i/punk7804x4.png)

<!--
$ magick convert punk7804.png -filter point -resize 400% punk7804x4.png
 -->


Why stop? Let's add a smile ![](misc/smile-alien.png)!

```
$ magick convert punk7804.png \
                 smile-alien.png \
         -background none -flatten punk7804_smile.png
```

<!--
$ magick convert punk7804.png smile-alien.png  -background none -flatten punk7804_smile.png
-->

![](i/punk7804_smile.png)   2x, 4x:
![](i/punk7804_smilex2.png)
![](i/punk7804_smilex4.png)





#### Alien Invasion

Let's try the green (120°) variant.
Let's make - a super rare alien
![](alien-invasion/alien-male_120.png)
with a capforward
![](original/capforward.png),
smallshades
![](original/smallshades.png)
and a pipe
![](original/pipe.png)
from scratch:

```
$ magick convert alien-male_120.png \
                 capforward.png \
                 smallshades.png \
                 pipe.png \
         -background none -flatten punk7804_120.png
```

<!--
$ magick convert alien-male_120.png capforward.png smallshades.png pipe.png -background none -flatten punk7804_120.png

$ magick convert punk7804_120.png -filter point -resize 200% punk7804_120x2.png

$ magick convert punk7804_120.png -filter point -resize 400% punk7804_120x4.png
-->

![](i/punk7804_120.png)   2x, 4x:
![](i/punk7804_120x2.png)
![](i/punk7804_120x4.png)

Or try the 90° ![](alien-invasion/alien-male_90.png) variant - `alien-male_90.png`:

![](i/punk7804_90.png)   2x, 4x:
![](i/punk7804_90x2.png)
![](i/punk7804_90x4.png)

Or 150° ![](alien-invasion/alien-male_150.png) - `alien-male_150.png`:

![](i/punk7804_150.png)   2x, 4x:
![](i/punk7804_150x2.png)
![](i/punk7804_150x4.png)




### Alien with Cap

Let's make punk #2890 - another super rare alien
![](original/alien-male.png)
with a cap
![](original/cap.png)
from scratch:

```
$ magick convert alien-male.png \
                 cap.png \
         -background none -flatten punk2890.png
```

<!--
$ magick convert alien-male.png cap.png -background none -flatten punk2890.png
-->


![](i/punk2890.png)   2x, 4x:
![](i/punk2890x2.png)
![](i/punk2890x4.png)



#### All Caps

Let's try the red (0°) variant.
Let's make - a super rare alien
![](alien-invasion/alien-male.png)
with a cap
![](all-caps/cap_0.png)
from scratch:

```
$ magick convert alien-male.png \
                 cap_0.png \
         -background none -flatten punk2890_0.png
```

<!--
$ magick convert alien-male.png cap_0.png -background none -flatten punk2890_0.png

$ magick convert punk2890_0.png -filter point -resize 200% punk2890_0x2.png

$ magick convert punk2890_0.png -filter point -resize 400% punk2890_0x4.png
-->

![](i/punk2890_0.png)   2x, 4x:
![](i/punk2890_0x2.png)
![](i/punk2890_0x4.png)


Or try the blue (240°) ![](all-caps/cap_240.png) variant - `cap_240.png`:

![](i/punk2890_240.png)   2x, 4x:
![](i/punk2890_240x2.png)
![](i/punk2890_240x4.png)



### Humans with Cap

Or let's make a (light skintone) human punk
![](original/human-male_light.png)
with a red (0°) cap
![](all-caps/cap_0.png)
and a smile
![](original/smile.png)
from scratch:


```
$ magick convert human-male_light.png \
                 cap_0.png \
                 smile.png \
         -background none -flatten human_light.png
```

<!--
$ magick convert human-male_light.png cap_0.png smile.png -background none -flatten human_light.png

$ magick convert human_light.png -filter point -resize 200% human_lightx2.png
-->

![](i/human_light.png)   2x, 4x:
![](i/human_lightx2.png)
![](i/human_lightx4.png)


Or try the dark skintone ![](original/human-male_dark.png) variant - `human-male_dark.png` -
with a green (120°) cap ![](all-caps/cap_120.png)  - `cap_120.png`:


<!--
$ magick convert human-male_dark.png cap_120.png smile.png -background none -flatten human_dark.png
-->


![](i/human_dark.png)   2x, 4x:
![](i/human_darkx2.png)
![](i/human_darkx4.png)


### Dodge Shiba Inu - Much Wow

Let's make a dodge punk  - a super rare alien
![](dodge/dodge-alien.png)
with a headband
![](dodge/headband-dodge.png)
from scratch:

```
$ magick convert dodge-alien.png \
                 headband-dodge.png \
         -background none -flatten dodge3100.png
```

<!--
 $ magick convert dodge-alien.png headband-dodge.png -background none -flatten dodge3100.png

 $ magick convert dodge3100.png -filter point -resize 200% dodge3100x2.png
  -->

![](i/dodge3100.png) 2x, 4x:
![](i/dodge3100x2.png)
![](i/dodge3100x4.png)


Or let's make a zombie
![](dodge/dodge-zombie-notop.png)
with a knitted cap
![](dodge/knittedcap-dodge.png)
from scratch:


```
$ magick convert dodge-zombie_notop.png \
                 knittedcap-dodge.png \
         -background none -flatten dodge2066.png
```

<!--
 $ magick convert dodge-zombie_notop.png knittedcap-dodge.png -background none -flatten dodge2066.png

 $ magick convert dodge2066.png -filter point -resize 200% dodge2066x2.png
  -->

![](i/dodge2066.png) 2x, 4x:
![](i/dodge2066x2.png)
![](i/dodge2066x4.png)



Or let's make a classic
![](dodge/dodge.png)
with a 3d glasses
![](dodge/3dglasses-dodge.png)
from scratch:


```
$ magick convert dodge.png \
                 3dglasses-dodge.png \
         -background none -flatten dodge_3dglasses.png
```

<!--
 $ magick convert dodge.png 3dglasses-dodge.png -background none -flatten dodge_3dglasses.png

 $ magick convert dodge_3dglasses.png -filter point -resize 200% dodge_3dglassesx2.png
  -->


![](i/dodge_3dglasses.png) 2x, 4x:
![](i/dodge_3dglassesx2.png)
![](i/dodge_3dglassesx4.png)



And so on. Yes, you can.





## Bonus - ImageMagick Special Effects

Use the [free ImageMagick tools](https://imagemagick.org)
to script special effects (on the command line).


### Polaroid-Like Photos

Let's start with a "plain vanilla" punk, that is, #2890 ![](i/punk2890.png) and
let's use the 4x (96x96) version
and turn it into a captioned polaroid-like photo:

```
$ magick convert punk2890x4.png \
          -gravity center -set caption "Punk #2890" \
          -caption '%c' \
          -border 5x5 \
          -bordercolor AliceBlue -background black  +polaroid \
          polaroid2890.png
```

![](i/polaroid2890.png)


And let's try some more:

![](i/polaroid7804.png)
![](i/polaroid_human_light.png)
![](i/polaroid_human_dark.png)
![](i/polaroid_dodge.png)




### Magnify 2x, 3x 4x with (Smooth) Pixel Art Scaling Algorithm

Let's start with a "plain vanilla" punk, that is, #2890 ![](i/punk2890.png) and
let's use 2x magnified (48x48) version
using a (smooth) [pixel art scaling algorithm¹](https://en.wikipedia.org/wiki/Pixel-art_scaling_algorithms)):

Note¹: ImageMagic uses the [scale2x](http://www.scale2x.it/algorithm) algorithm

<!--
  more on github @ https://github.com/amadvance/scale2x/
  -->


```
$ magick convert punk2890.png \
          -magnify \
          punk2890_magnify2x.png
```

![](i/punk2890_magnify2x.png)


And doubling again (4x):

```
$ magick convert punk2890.png \
          -magnify -magnify \
          punk2890_magnify4x.png
```

![](i/punk2890_magnify4x.png)

And doubling again (8x):

```
$ magick convert punk2890.png \
          -magnify -magnify -magnify \
          punk2890_magnify8x.png
```

![](i/punk2890_magnify8x.png)



And let's try some more:

![](i/punk7804_magnify2x.png)
![](i/punk7804_magnify4x.png)
![](i/punk7804_magnify8x.png)
![](i/human_light_magnify2x.png)
![](i/human_light_magnify4x.png)
![](i/human_light_magnify8x.png)


![](i/dodge_magnify2x.png)
![](i/dodge_magnify4x.png)
![](i/dodge_magnify8x.png)





And so on. Yes, you can.





## Questions? Comments?

Post them on the [CryptoPunksDev reddit](https://old.reddit.com/r/CryptoPunksDev). Thanks.
