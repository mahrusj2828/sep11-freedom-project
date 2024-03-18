# Entry 4
##### 3/17/24

I have finished making my song with [EarSketch](https://earsketch.gatech.edu/landing/#/) and I am now working on a model to pair my song with. I am using [Zdog](https://zzz.dog/getting-started) to help me make this model. Zdog is a 3D Javascript Enginewhere you can design 3D models where its geometries existin 3D but are rendered as flat shapes. So far, I have looking at examples of models shown on Zdog and when I click on the models, it shows the code behind it, using CSS, HTML, and Zdog Javascript. After exploring the different models, I followed the tutorial shown in Zdog when you click on ["Getting Started"](https://zzz.dog/getting-started). It shows the basic steps on how to use different elements to produce different results. I also searched up on [Youtube](https://www.youtube.com/watch?v=F1LZ-AdQ5yc&list=PLcpWg9m0uU9cl1b6g189AcNxlatQeIQMC) on how to set up Zdog and how to use properly use it. After researching, I tried making my own practice model. To start, I tried making a rectangle that could spin. To set it up, I had to use `new Zdog.Illustration` and `element:zdog-canvas,` to create the canvas that I am going to be making the rectangle on. Then to make the rectangle, it was similar to what I had been working on during class for the past few days using `.Rect` but I had to put it in front of a name (I used Zdog).

```js
new Zdog.Rect({
  addTo: illo,
  height: 100,
  width: 200,
  depth: 200,
  stroke: 20,
  color: '#636',
});

illo.updateRenderGraph();
```

This is what was used to create the rectangle. `.updateRenderGraph()` is what is used to update all the display properties, then render shapes on to the element.Then, as I scrolled down, I saw code on how to animate shapes. It showed an example of how to make a shape move/rotate on its own.

```js
function animate() {
  illo.rotate.y += 0.02;
  illo.updateRenderGraph();
  requestAnimationFrame( animate );
}

animate();
```

I learned that `illo.rotate.y` is used to change the speed of that shape's animation speed and that `animate();` is used to start the animation. As I continued to scroll down through the basics, I saw an example of how to drag shapes. When I saw the example of the code, I showed that you need to use `dragRotate: true,` to make it so that you could drag shapes.

```js
let illo = new Zdog.Illustration({
  element: '.zdog-canvas',
  dragRotate: true,
});
```

This allowed for my rectangle to be able to be dragged.

For this blog, I am currently between the Creating and Testing part of the Engineering Design Process (EDP) where I am creating different shapes to make a model and testing different kinds of elements to see what they do. While working on this blog, I have been working on the skill of "How to Learn". This is an important skill for me to learn because I have to learn the different kinds of code that I need to use in my tool and how I will be able to create an interactable model. "How to Google" is also an important skill for me to learn because there could parts where I am not sure how to fix if things go wrong and can use help from the internet on how to fix that specific problem so that I can figure it out on my own and will then be able to know how to fix that kind of problem again.


[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)