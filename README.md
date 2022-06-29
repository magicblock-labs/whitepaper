---
description: >-
  An immersive AR mobile game that helps clean up the planet -
  https://www.garbles.fun/
---

# Garbles Universe

<style>
body {
  background: #8acdeb;
}
#container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.steam {
  position: absolute;
  height: 150px;
  width: 150px;
  border-radius: 50%;
  background-color: #fff;
  margin-top: -75px;
  margin-left: 75px;
  z-index: 0;
  opacity: 0;
}

#steam1 {
  -webkit-animation: steam1 4s ease-out infinite;
  animation: steam1 4s ease-out infinite;
}

#steam3 {
  -webkit-animation: steam1 4s ease-out 1s infinite;
  animation: steam1 4s ease-out 1s infinite;
}

@-webkit-keyframes steam1 {
  0% {transform: translateY(0) translateX(0) scale(0.25); opacity: 0.2;}
  100% {transform: translateY(-200px) translateX(-20px) scale(1); opacity: 0;}
}

@keyframes steam1 {
  0% {transform: translateY(0) translateX(0) scale(0.25); opacity: 0.2;}
  100% {transform: translateY(-200px) translateX(-20px) scale(1); opacity: 0;}
}

#steam2 {
  -webkit-animation: steam2 4s ease-out 0.5s infinite;
  animation: steam2 4s ease-out 0.5s infinite;
}

#steam4 {
  -webkit-animation: steam2 4s ease-out 1.5s infinite;
  animation: steam2 4s ease-out 1.5s infinite;
}

@-webkit-keyframes steam2 {
  0% {transform: translateY(0) translateX(0) scale(0.25); opacity: 0.2;}
  100% {transform: translateY(-200px) translateX(20px) scale(1); opacity: 0;}
}

@keyframes steam2 {
  0% {transform: translateY(0) translateX(0) scale(0.25); opacity: 0.2;}
  100% {transform: translateY(-200px) translateX(20px) scale(1); opacity: 0;}
}

#cup {
  z-index: 1;
}

#cup-body {
  position: absolute;
  height: 200px;
  width: 300px;
  border-radius: 0 0 150px 150px;
  background-color: #fff;
  margin: auto;
  display: inline-block;
  overflow: hidden;
  z-index: 1;
}

#cup-shade {
  position: relative;
  height: 300px;
  width: 200px;
  background-color: #F3F3F3;
  display: inline-block;
  margin-left: 42%;
  margin-top: -3px;
  transform: rotate(50deg);
  z-index: 1;
}

#cup-handle {
  position: relative;
  height: 75px;
  width: 80px;
  border-radius: 0 150px 150px 0;
  border: 15px solid #F3F3F3;
  margin-bottom: 95px;
  margin-left: 250px;
  display: inline-block;
  z-index: 0;
}

#saucer {
  position: absolute;
  height: 30px;
  width: 300px;  
  border-radius: 0 0 100px 100px;
  background-color: #F9F9F9;
  margin-top: -32px;
  margin-left: 5px;
  z-index: 2;
}

#shadow {
  height: 10px;
  width: 300px;
  border-radius: 50%;
  margin-top: -5px;
  margin-left: 6px;
  background-color: #7bb8d4;
}
</style>

<div id="container">
  <div class="steam" id="steam1"> </div>
  <div class="steam" id="steam2"> </div>
  <div class="steam" id="steam3"> </div>
  <div class="steam" id="steam4"> </div>

  <div id="cup">
    <div id="cup-body">
      <div id="cup-shade"></div>
    </div>
    <div id="cup-handle"></div>
  </div>

  <div id="saucer"></div>

  <div id="shadow"></div>
</div>

## Summary

![](.gitbook/assets/andrea-cau-nV7GJmSq3zc-unsplash.jpg)

Welcome to the world of Garbles!&#x20;

\
Trash has become so abundant on our planet that humans don't know how to store it anymore. Luckily, a group of smart scientists (we call them Cleantists) has found a way to cultivate goofy creatures that happen to be the perfect solution to the problem.\
&#x20;\
Garbles are cute, clumsy monsters that originate from garbage. Help them dove into our dumpsters and gobble up every plastic bottle they can find! Every time you create a Garble you are removing actual C02 from the environment. Assemble an army of lovable creatures and embark on a journey to populate the planet...while cleaning it!

****

**Official links**

**🌐** [**Website**](https://www.garbles.fun/)****\
**👾** [**Discord**](https://discord.gg/yKvddrZ25u)****\
**🐦** [**Twitter**](https://twitter.com/garblesfun)
