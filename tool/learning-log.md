# Tool Learning Log

## Tool: Aframe

---

### 3/3/25:

<a href="https://aframe.io/" >Aframe</a>

* A-Frame is not just a 3D scene graph or a markup language; the core is a powerful entity-component framework that provides a declarative, extensible, and composable structure to three.js.
* a-Frame is a web framework for building virtual reality (VR) experiences
* Inorder to you create an .html file and include A-Frame in the head.
* you can create many different types of shape like circle, boxs, cylinder, and etc.
*you can create different types of scenes like a plane and a sky.
<p>These are the notes that i took when just looking at the website because i want to understand the basic of the website before doing deeper research. </p>

### 3/9/25:
<p>Today i decided to do more researchs on A-frame but not using the website but using different sources.</p>
<a href="https://www.w3docs.com/snippets/css/how-to-add-a-frame-around-an-image.html" >w3doc</a>

<h2>Create Html</h2>

* Create a div element with a class name "frame".
* Define an img tag in the div element.
* Set the alt attribute for the image.

```bash
<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <div class="frame">
      <img src="/uploads/media/default/0001/01/b408569013c0bb32b2afb0f0d45e93e982347951.jpeg" alt="Nature">
    </div>
  </body>
</html>
```
<h2>Add CSS</h2>

* Set the height and width for the frame.
* Specify the style, the width and the color of the border with the border shorthand property.
* Set a background-color.
* Set the margin to "auto" and the padding with two values. The first value sets the top and bottom sides, and the second one sets the right and left sides.
*Set the width and height of the image to 100%.

```bash
.frame {
  width: 300px;
  height: 250px;
  border: 3px solid #ccc;
  background: #eee;
  margin: auto;
  padding: 15px 10px;
}

img {
  width: 100%;
  height: 100%;
}
```
<h1>3/23/25</h1>
<p>During this learning log i was able to search up and find some Aframe simulations to tinker around with.</p>
<a href= "https://codepen.io/tmd45/pen/OEVowY">A frame sample</a>

```bash
<html>
  <head>
    <!-- from https://github.com/aframevr/aframe/ -->
    <script src="https://aframe.io/releases/0.7.0/aframe.min.js"></script>
    <script src="https://unpkg.com/aframe-animation-component@3.2.1/dist/aframe-animation-component.min.js"></script>
    <script src="https://unpkg.com/aframe-particle-system-component@1.0.x/dist/aframe-particle-system-component.min.js"></script>
    <script src="https://unpkg.com/aframe-extras.ocean@%5E3.5.x/dist/aframe-extras.ocean.min.js"></script>
    <script src="https://unpkg.com/aframe-gradient-sky@1.0.4/dist/gradientsky.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-entity id="rain" particle-system="preset: rain; color: #24CAFF; particleCount: 5000"></a-entity>

      <a-entity id="sphere" geometry="primitive: sphere"
                material="color: #EFEFEF; shader: flat"
                position="0 0.15 -5"
                light="type: point; intensity: 5"
                animation="property: position; easing: easeInOutQuad; dir: alternate; dur: 1000; to: 0 -0.10 -5; loop: true"></a-entity>

      <a-entity id="ocean" ocean="density: 20; width: 50; depth: 50; speed: 4"
                material="color: #9CE3F9; opacity: 0.75; metalness: 0; roughness: 1"
                rotation="-90 0 0"></a-entity>

      <a-entity id="sky" geometry="primitive: sphere; radius: 5000"
                material="shader: gradient; topColor: 235 235 245; bottomColor: 185 185 210"
                scale="-1 1 1"></a-entity>

      <a-entity id="light" light="type: ambient; color: #888"></a-entity>
    </a-scene>
  </body>
</html>
```
<p>This was something that i used to create a simulation but later on i found out that when using this html i didn't know why it wasn't working before but when i used JSbin i was able to see the code in action and how it played a role of what i can do with Aframe.</p>
<p>Important notes i learn is the server because at first i didnt have the correct server which didnt allow me to see what the code can do</p>
<p>The second note i learn is to explore and expand my curiousity throughout studying Aframe.</p>

<h3>3/31/25</h3>
<p>During this learning i was able to fool around with my imagingation. I was very bored when doing A-frame but something caught my eyes when i was tinkering around. I was able to change the weather, the setting and make something glow.</p>

```bash
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
    <script src="https://unpkg.com/@c-frame/aframe-particle-system-component@1.2.x/dist/aframe-particle-system-component.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/c-frame/aframe-extras@7.5.0/dist/aframe-extras.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@fern-solutions/aframe-sky-background/dist/sky-background.umd.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-entity id="snow" particle-system="preset: snow; color: #24CAFF; particleCount: 5000"></a-entity>

      <a-entity id="box" geometry="primitive: box"
                material="color: #EFEFEF; shader: flat"
                position="0 2 -5"
                rotation="0 45 45"
                scale="3 3 3"
                color="brown" 
                light="type: point; intensity: 5"
                animation="property: position; easing: easeInOutQuad; dir: alternate; dur: 1000; to: 0 -0.10 -5; loop: true"></a-entity>

      <a-entity id="ocean" ocean="density: 20; width: 50; depth: 50; speed: 4"
                material="color: #9CE3F9; opacity: 0.75; metalness: 0; roughness: 1"
                rotation="-90 0 0"></a-entity>

      <a-sky-background top-color="#EBEBF5" bottom-color="#B9B9D2"></a-sky-background>

      <a-entity id="light" light="type: ambient; color: #888"></a-entity>
      <a-sky color="#222"></a-sky>
    </a-scene>
    </a-scene>
  </body>
</html>
```
<p> This was something that shocked my curiousity because i didnt know that i was able to change alot of the code to make my scene look something i dreamed about. This made me wonder if A-frame was so boring because i was able to learn from my imgaination and create something that i never knew was possible.</p>
