# More ImageMagic Command Line Examples


## Wall Street Bets

Let's make a (light skintone) human punk
![](original/human-male_light.png)
with regular shades
![](original/regularshades.png)
and a wall street bets hairdo
![](misc/wallstreetbets-hair.png)
from scratch:


```
$ magick convert human-male_light.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
            -background none -flatten wallstreetbets_human_light.png
```

![](i/wallstreetbets_human_light.png)  4x ![](i/wallstreetbets_human_lightx4.png)


Let's add a smile ![](original/smile.png):


```
$ magick convert human-male_light.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
                 smile.png \
            -background none -flatten wallstreetbets_human_light_smile.png
```

![](i/wallstreetbets_human_light_smile.png) 4x  ![](i/wallstreetbets_human_light_smilex4.png)


Let's add a pipe ![](original/pipe.png):


```
$ magick convert human-male_light.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
                 smile.png \
                 pipe.png \
            -background none -flatten wallstreetbets_human_light_pipe.png
```

![](i/wallstreetbets_human_light_pipe.png) 4x ![](i/wallstreetbets_human_light_pipex4.png)


Let's try a super rare alien ![](original/male-alien.png):

```
$ magick convert alien-male.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
            -background none -flatten wallstreetbets_alien.png
```

![](i/wallstreetbets_alien.png) 4x ![](i/wallstreetbets_alienx4.png)


Let's change to 3D glasses ![](original/3dglasses.png):

```
$ magick convert alien-male.png \
                 wallstreetbets-hair.png \
                 3dglasses.png \
            -background none -flatten wallstreetbets_alien_3dglasses.png
```

![](i/wallstreetbets_alien_3dglasses.png) 4x ![](i/wallstreetbets_alien_3dglassesx4.png)



And so on. Yes, you can.


