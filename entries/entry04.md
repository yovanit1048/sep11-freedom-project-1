# Entry 4
##### 4/26/21

# Sources

Last week, I had time to review the next steps that I wrote on my EDP(Engineering Design Process), making a prototype with lighting and camera POV. Which today I came across this video's helping me understand both [Cameras](https://www.youtube.com/watch?v=Cib3Y64GVWE) and [Lights](https://www.youtube.com/watch?v=_fTS5W0RPkc). These videos helped me understand the basics of what I need to start with and were the foundation of my project because of how they are needed to start anything that is created in Babylon.


# Engineering Design Process(EDP)

I’m currently at stage 5 Engineering Design Process: Create a Prototype. I’ve used the planning from stage 4 of the EDP and further research to start to create a [Prototpe](https://playground.babylonjs.com/). The prototype is a playground where Babylon has provided the user with a starter code and it’s up to me to start to tinker with add my ideas that I’ve learned from the past change around the code to fit my liking. I will also use the MVP plan to start the code little by little making small changes that will coincide with what I’ve made. The prototype is a playground where Babylon has provided the user with a starter code and it’s up to me to start to tinker with add my ideas that I’ve learned from the past change around the code to fit my liking. I will also use the MVP plan to start the code little by little making small changes that will coincide with what I’ve made.

For the next stage Test and evaluate the prototype, I would like to test everything I’ve tried to implement and see what needs to be improved on and what needs to be added to make it better, or even what needs to be removed to make my prototype easier to code. I would also like to talk to people who are also doing Babylon to see their Babylon project and see what is similar and different and is there anything we can take from both projects that we can see as helpful to us and our project.

# Knowledge

From the 2 youtube videos about [Cameras](https://www.youtube.com/watch?v=Cib3Y64GVWE) and [Lights](https://www.youtube.com/watch?v=_fTS5W0RPkc), I've learned th basics of both featuers to start my protoype.

```
var light = new BABYLON.HemisphericLight("light", new BABYLON.Vector3(0, 1, 0), scene);
light.intensity = 0.9;
camera.attachControl(canvas, true);
```
This first line of code makes the light radiant up 1 of the y axis and changing makes the light radiant change by changing the x and y-axis. While the second line of code changes the brightness of the light by the amount that is inputted by the user. And the last code just attach the camera so it stays in one place.
```

```
[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
