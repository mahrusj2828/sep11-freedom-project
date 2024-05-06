# Entry 2
##### 12/17/23

I am still experimenting with [EarSketch](https://earsketch.gatech.edu/landing/#/), a website that teaches you how to make music using Python or Javascript (in my case, I am using Javascript). With EarSketch, I want to be able to make a song that would fit in the horror genre. As I have been experimenting with EarSketch, I have noticed that I am not finding enough sounds that would fit in the song that I am hoping to make. I looked at the curriculum, which showed instructions on how to use EarSketch, and I read that I could sign up on [Freesound](https://freesound.org/people/TGN.LiveOrganism/sounds/537780/) so that I could download songs and add them on EarSketch. I found sounds that would fit in my song. I then experimented with the sounds that I found on Freesound to see what sounds the best. I have also been trying to figure out how to increase the volume of a sound over time (crescendo) as well as how to lower it over time (diminuendo). This is what I have so far.

```js
setTempo(100);

fitMedia(MOOSEMAN_CAVE_AMBIENCE, 1, 1, 60)
fitMedia(MOOSEMAN_DEVIOUS___THEME,2, 6, 23.033)
fitMedia(MOOSEMAN_700249_MARTIAN_HORROR_TV_LOGO, 4, 10, 60)
fitMedia(MOOSEMAN_SCARYVIOLINS_OGG, 5, 30, 35)
```
```js
fitMedia(MOOSEMAN_DEVIOUS___THEME,2, 6, 23.033)
setEffect(2, VOLUME, GAIN, 10);
```

For this blog, I am currently between the Creating and Testing part of the Engineering Design Process (EDP). While working on this blog, I have been working on the skill of "How to Learn". This is an important skill for me to learn because I have to learn the different parts of the tool that I am using and how I am going to be able to manipulate the parts I need to use to get my end product. "Consideration" is another skill that is important for me to learn since I am going to be adding things from outside sources to make my product while using my tool. "Creativity" is another important skill for me to learn. It will help me when using a wider variety of sources when using my tool and how to combine those sources with the tool that I am using. 

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)