# Entry 5
##### 5/5/24

I have finished my MVP by using [EarSketch](https://earsketch.gatech.edu/landing/#/) to make my own song. I have used different sounds available in EarSketch to create my song. I have also used other sources like [Freesound](https://freesound.org/people/TGN.LiveOrganism/sounds/537780/) to find other sounds to create my song. By using the sounds that I have found on EarSketch and Freesound, I have made a song that could used in horror based games or movies. To make my song, I have also looked at the curriculum in the EarSketch website and on Youtube to find out if I could use different effects on the sounds that I have used for my song. There are many elements to use that EarSketch has to offer like beat strings, reverb and pitch. Out of all of the elements, I have decided to only use a few. I learned how use a sound by first using the `fitMedia()` which allows me to put the specific sound that I want, select a track (like a row), and select the start and end times for it.

```js
fitMedia(MOOSEMAN_CAVE_AMBIENCE, 1, 1, 60)
fitMedia(MOOSEMAN_DEVIOUS___THEME,2, 6, 23.033)
fitMedia(MOOSEMAN_700249_MARTIAN_HORROR_TV_LOGO, 4, 10, 60)
fitMedia(MOOSEMAN_661624_NUNCACONOCI_MAN_WALKING_ON_SOGGY_GROUND, 7, 10, 65)
fitMedia(MOOSEMAN_690436_CRUNCHYMANIAC_SCARYPIANO, 8, 9, 64)
```

These are the sounds that I have used while using the `fitMedia()` element. I have also done research on elements like volume gain and `delay`/`delay_time` using the `setEffect()` element. I have search on Youtube for videos like [VOLUME in EarSketch tutorials](https://www.youtube.com/watch?v=hCk9Ipv5mbU&t=237s) and [setEffect in EarSketch - Delay Echo](https://www.youtube.com/watch?v=VgY7VhN7QKo&t=242s) to help learn how to use the two different effects for my song. Through these tutorials, I have learned that I could use `VOLUME` to either raise or lower the volume of a sound that I have used to create a distant sound in the background feeling. I also learned that with the `delay`/`delay_time` element, I could use it so that any sound that I apply it to, it would create an echoing sound to make it sound like someone is in a very open cave-like or empty environment.

```js
setEffect(4, VOLUME, GAIN, 4, 10);
setEffect(7, VOLUME, GAIN, -10);
setEffect(7, DELAY, DELAY_TIME, 40)
```

This is how I have used these effects. Although it is already implemented when creating a new song, I also utilized the `setTempo` effect, which allows me to change the tempo of the entire song. `setTempo(70);` I used the 70 tempo to get a slow song that could feel eery.

For this blog, I am currently between the "Improve as Needed" and "Communicate the Results" part of the Engineering Design Process (EDP) where I am improving on the parts of my work sharing the results of my finished work. While working on this blog, I have been working on the skill of "Attention to Detail". This is an important skill for me to learn because it helps me become more likely to catch errors in my work and be able to create something that people would be interested in because of how detailed something could be or so that everything can run smoothly. I have also been working on the skill of "Growth Mindest". This is an important skill for me to learn because I need to able to use the things I have around me to my advantage, such as the internet or my peers to help me with an issue or even to learn from a mistake so that I could find a way to fix it.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)