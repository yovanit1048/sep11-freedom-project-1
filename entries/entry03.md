# Entry 3
##### 2/15/20

# Sources 

Over the break, I had the time to do even more research. And during that time I came across this [youtube video](https://www.youtube.com/watch?v=eQH4273wy7w)which helped re-explained some of the things I learned about Babylon and also learn something.

Along with the youtube video i found i also found this [website](https://developer.mozilla.org/enUS/docs/Games/Techniques/3D_on_the_web/Building_up_a_basic_demo_with_Babylon.js?utm_campaign) which like the video gives a basscicy of Babbylon but also code sinppets that i can follow along and create,this ends up being a 3D square.


# Engineering Design Process(EDP)

I'm currently at stage 4 Engineering Design Process: the most promising solution. I’m starting to plan over the best solutions for my project from what I’ve learned and re-learned over the course of this project I’m trying to still see what other thing out there can help me better understand Babylon and planning over what the best course of action that I will take for this project. The other plan is ways how I can make a 3D feel like the user can actually be there and experience and also plan what I will require to learn everything that Babylon offers and make a project to the best of my ability.

For the next stage Create a prototype, I plan to make a simple background with lighting and a couple of shapes which will not be that difficult since over my time doing research on Babylon those were demos and beginners steps that were recommended for people starting to work on Babylon. I will take the time until the next  entry to use what I’ve learned and make apply that to a small prototype that will display what I’ve learned and also along the way would like still to learn about possibles ways to better improve my small prototype.

# Knowledge

From the [youtube video](https://www.youtube.com/watch?v=eQH4273wy7w) and the [website](https://developer.mozilla.org/enUS/docs/Games/Techniques/3D_on_the_web/Building_up_a_basic_demo_with_Babylon.js?utm_campaign) Ive learned how to create a background and a 3D square and sphere:

```
var canvas = document.getElementById("render-canvas");
    var engine = new BABYLON.Engine(canvas);
    var scene = new BABYLON.Scene(engine);
    scene.clearColor = new BABYLON.Color3(0.8, 0.8, 0.8);
    var camera = new BABYLON.FreeCamera("camera", new BABYLON.Vector3(0, 0, -10), scene);
    var light = new BABYLON.PointLight("light", new BABYLON.Vector3(10, 10, 0), scene);

    var box = BABYLON.Mesh.CreateBox("box", 2, scene);
    box.rotation.x = -0.2;
    box.rotation.y = -0.4;

    var boxMaterial = new BABYLON.StandardMaterial("material", scene);
    boxMaterial.emissiveColor = new BABYLON.Color3(0, 0.58, 0.86);
    box.material = boxMaterial;

    var renderLoop = function () {
        scene.render();
    };
    engine.runRenderLoop(renderLoop);
```
By making this simple 3D objective learned how to create a rending loop that makes the scene visible and creating a camera that gives it the light on it. These two are important for any making anything in 3D it provides the fundamental details to start.

# Skills

The skills that I used were Attention to detail and How to Google

I’ve used the skill Attention to detail while typing this blog entry, I’ve constantly have been copying and pasting what I write down here and then transferring it into a google doc which helps to see what spelling errors and grammar correction I need to make. By doing this it would make my blog entry a lot easier to read with minimal mistakes.

I’ve used the skills How to Google while doing research for planning for my prototype I’ve constantly search what every little code did try to find easier ways to write it and even when it gave an explanation I would try to find more about that code and what it does. And also by searching up Babylon Javascript I’ve found many youtube video that was made in the last year or just a month ago which makes it more relevant because of how it has everything that I have compared to a 3-year-old video.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
