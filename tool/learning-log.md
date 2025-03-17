# Tool Learning Log

## Tool: A-Frame

---

### X/X/XX:
* Text

### 03/10/2025:
* A-Frame is a web framework that allows devellopers to create virtual reality expierences directly within web browsers using simple HTML codes.

To learn more about A-Frame I visted sites like their own which was <a href="https://aframe.io/"> A-Frame </a>. The wbsite introduced me to what A-Frame was and showed me some projects people have craeted using the A-Frame codes.

Other websites I used was:

1) <a href=".mozilla.org"> A-Frame Guide On MDN </a>
  - This website had a guide on how to create basic demos with A-frame.
- I Learned:
 - One of the features of A-Frame is its declarative HTML- like syntax for creating 3D objects.
 - A-Frame uses a compentemt based architecture. The components are resuable buildig blocks for 3D objects.

 2) <a href="https://aframe.io/>"> A-Frame document offical</a>
 - A-Frame works across a wide range of devices. It is built to be device-agnostic, ensuring a broad reach.
 - A- Frame is built on top of Three.js, whihc is a 3D javascript library.

 To get a visuale of how the codes of A-Frame really work and the things thet are able to create I used jsbin. With the facts I learned and youtube vifeos I watched, I used some of their codes combined with some I leanred to create a 3D heart.

 The Code:
 <!DOCTYPE html>
  <html lang="en">
   <head>
   <meta charset="UTF-8" />
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   <title>3D Red Heart</title>
   <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    </head>
    <body>
    <a-scene>
     <!-- Camera -->
      <a-camera position="0 1.6 5"></a-camera>
       <!-- 3D Heart made of spheres and boxes -->
       <!-- Left half of the heart -->
       <a-sphere
        position="-1 1 0"
        radius="1"
         color="red"
         segments-width="32"
          segments-height="32">
          </a-sphere>
           <!-- Right half of the heart -->
            <a-sphere
            position="1 1 0"
            radius="1"
            color="red"
            segments-width="32"
             segments-height="32">
              </a-sphere>
            <!-- Bottom triangle to complete the heart shape -->
                <a-box
                 position="0 -0.5 0"
                 width="2"
                 height="2"
                 depth="1"
                 color="red"
                 rotation="0 0 45">
                    </a-box>
                   </a-scene>
                  </body>
                 </html>

That is my process so far.

### 03/17/2025

This time I visted youtube videos instead of websites to learn about my tool. The youtube videos I watched 

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
