# Entry 1
##### 12/11/23

  So far, I have been tinkering with [EarSketch](https://earsketch.gatech.edu/landing/#/), which is a website that teaches you how to make music using Python or Javascript (in my case, I am using Javascript). I chose to tinker with EarSketch because I always listen to music and have thought about making my own song. With EarSketch, I want to be able to make a song that would fit in the horror genre. I have followed some of the tutorials shown on the site. At first, I found it confusing and didn't know what some of the parts meant. For example, when I read `fitMedia(Y18_DRUM_SAMPLES_2, 2, 1, 5)`, I didn't know what the numbers at the end meant `fitMedia(Y18_DRUM_SAMPLES_2, 2, 1, 5)`<-(These). After looking at more tutorials and more research on the Website, I realized that they specify which row the song is placed (the first number) on the soundboard and when and how long the sound plays for (the second # tells when the sound starts and the third # tells when the sound ends). So when I learned this, I tried making a song that would fit into the pop genre and added different sounds at different points like bass-8 being the first sound on the sound board and starting first, going on for 30 seconds, with key pluck-1 being the second sound on the soundboard, starting after four seconds and going on for 20 seconds, and then main-beat-20 being the third sound on the soundboard, starting after 4 seconds and going on for 25 seconds.
Ex:
```js
// description: 
setTempo(120);

fitMedia(RD_POP_ARPBASS_8, 1, 1, 30)
fitMedia(RD_POP_KEYPLUCK_1, 2, 4, 20)
fitMedia(RD_POP_MAINBEAT_20, 3, 4, 25)
```
  For this blog, I am currently between the Research and Brainstorming part of the Engineering Design Process (EDP). While working on this blog, I have been working on the skill of "How to Learn". This is an important skill for me to learn because I have to learn the tool that I am going to use and how I am going to organize the different components while I am tinkering with it. "Growth Mindset" is another important skill for me to learn because I need to need to be patient and try things that might not be to my liking or might not go my way. "Creativiy" is also another important skill. This is important skill for me to learn because I have to come up with something that is I came up with from experimenting with different components. This goes especially with the tool that I am using since I have to make a song that not only sounds good, but also original and unique.

[Next](entry02.md)

[Home](../README.md)
