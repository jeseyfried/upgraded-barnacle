---
title: Getting Started
layout: base
date: 2024-10-24
---

{% include jumbotron.html
  height="50"
  image-url="/assets/bg-images/27688283.jpg"
  title="Late Fourteenth-Century Catalan Paleography"
%}


### Paleography is the study of handwritten scripts
The documents on this page are samples of the paleography of the late fourteenth-century Crown of Aragon.

Documents like these can be found by searching in PARES, a database of digitized images of archival documents maintained by the government of Spain.


{% include bg.html
  height="220"
  image-url="/assets/bg-images/27688286.jpg"
  pre-box-space="100"
  box-content=" 
       This is a letter from Violant de Bar."
%}




### Scrolly boxes on fixed images
Just above, wee see how to have a large background image "revealed" by the page scrolling up off of it, meaning it looks stationary while text scrolls past it.

As you can see below, you can also have a large backgrtound image scroll into view (instead of remaining still), as is happening below. 

The image freeze it when it gets to the top of the viewport, and a textbox can scroll past, grabbing the background with it as it scrolls away. Check it!


{% include bg-sticky.html
  height="220"
  image-url="/assets/bg-images/hike-4.jpg"
  pre-box-space="100"
  box-content="
       This text box is scrolling. And as soon as it leaves the viewport, the background image will begin to scroll away. 
<hr/>
       This text box is scrolling. And as soon as it leaves the viewport, the background image will begin to scroll away. 
  <p/>     
       This text box is scrolling. And as soon as it leaves the viewport, the background image will begin to scroll away. 
    <p/>   
       This text box is scrolling. And as soon as it leaves the viewport, the background image will begin to scroll away.   "
%}


## That's a wrap 
That's all for basic images. We can also do [background switching](bg-switch) and [side scrolling](side-scroll).
