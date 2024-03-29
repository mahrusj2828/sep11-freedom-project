# Entry 3
##### 02/11/24

I am still experimenting with [EarSketch](https://earsketch.gatech.edu/landing/#/), a website that teaches you how to make music using Python or Javascript (in my case, I am using Javascript). With EarSketch, I have been creating a song that you would hear in a horror show or a horror game. There has been a lot that I have learned through EarSketch such as using different sound effects using the `setEffect` element and I have discovered many new sounds to use from EarSketch and from sites like [Freesound](https://freesound.org/people/TGN.LiveOrganism/sounds/537780/). There are many other elements to use that EarSketch has to offer like beat strings, reverb and pitch. However, I have used a select few to use for my song because of how simple I want to make my song. I have learned more methods of tinkering with some of the sounds that I have chosen such as volume gain which allows me to lower or increase the volume of a certain sound and delay which adds an echo effect to a sound. I learned how to properly use them through Youtube videos such as [VOLUME in EarSketch tutorial](https://www.youtube.com/watch?v=hCk9Ipv5mbU&t=237s) and [setEffect in EarSketch - Delay Echo](https://www.youtube.com/watch?v=VgY7VhN7QKo&t=242s).

```js
fitMedia(MOOSEMAN_700249_MARTIAN_HORROR_TV_LOGO, 4, 10, 60)
fitMedia(MOOSEMAN_661624_NUNCACONOCI_MAN_WALKING_ON_SOGGY_GROUND, 7, 10, 65)
fitMedia(MOOSEMAN_690436_CRUNCHYMANIAC_SCARYPIANO, 8, 9, 64)

setEffect(4, VOLUME, GAIN, 4, 10);
setEffect(7, VOLUME, GAIN, -10);
setEffect(7, DELAY, DELAY_TIME, 40)
```

I am close to finishing my song and I am hoping to work on using another tool called [Zdog](https://zzz.dog/getting-started), which uses JavaScript code to make 3D models. With Zdog, I am hoping to make a scene of a deteriorating hospital where I can try pairing it with the song that I am almost done making. After exploring some of the models shown on Zdog, I want to try to make an 3D environment like [this](https://codepen.io/desandro/pen/vdwMyW). I want to try making my model of a broken down hospital that works in a similar way as [this](https://codepen.io/desandro/pen/vdwMyW) when you try turning it. After making a model, I plan on combining what I have created using the tools that I have chosen to use onto one page where the song plays on repeat in the background of the page while a version of the model that I have created will be shown where you could also interact with it to see the details.

For this blog, I am currently between the Testing and Improving part of the Engineering Design Process (EDP). While working on this blog, I have been working on the skill of "Attention to Detail". This skill is important for me to learn because I need to know which sounds play at which timesa so that it could all sound good when playing the song. It an important skill also because I need to be sure which sounds I am using when making my song. "Consideration" is also another important skill for me to learn. It is important for me to learn because I need to know how the combinations of different sounds would make people feel/react with it.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
