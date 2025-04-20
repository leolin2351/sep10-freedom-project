# Entry 5
##### 4/11/25

<h1>CONTEXT AND SOURCE:</h1>
<p>In this blog entry we continued where we left off on blog 4. We have to choose a tool on blog 4 but tinker a little bit with it. But in this blog entry we had to continue where we left off in blog 4. I chose A-frame because when watching A-frame I was able to see a 3d visual of a scene and I got curious about how I could do it. I started to tinker with what I was curious about. During this week I was tinkering around with the particle and added camera perspective. I was able to learn these codes because I watched <a href="https://www.youtube.com/watch?v=8BeoaNm5kzw">Sulaeman</a>. He taught me how to add particles into my webpage and showed me different types of particles. Which got me curious and made me want to try it myself. Here my code and what i did:</p>

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
      <a-scene>
        <a-entity id="rain" particle-system="preset: rain; color: #24CAFF; particleCount: 5000"></a-entity>
        <a-scene>
          <a-entity id="smoke" particle-system="preset: smoke; color: white; particleCount: 5000"></a-entity>
          <a-scene>
            <a-entity id="dust" particle-system="preset: dust; color: brown; particleCount: 5000"></a-entity>
      <a-entity id="box" geometry="primitive: box"
                material="color: #EFEFEF; shader: flat"
                position="0 2 -5"
                rotation="0 45 45"
                scale="3 3 3"
                color="red" 
                light="type: point; intensity: 5"
                animation="property: position; easing: easeInOutQuad; dir: alternate; dur: 1000; to: 0 -0.10 -5; loop: true"></a-entity>
                <a-camera>
                  <a-cursor fuse=“true” fuse-timeout=“5000”></a-cursor>
                </a-camera>
      <a-entity id="ocean" ocean="density: 20; width: 100; depth: 50; speed: 4"
                material="color: blue; opacity: 0.75; metalness: 0; roughness: 1"
                rotation="-90 0 0"></a-entity>

      <a-sky-background top-color="#EBEBF5" bottom-color="#B9B9D2"></a-sky-background>

      <a-entity id="light" light="type: ambient; color: #888"></a-entity>
      <a-sky color="#222"></a-sky>
    </a-scene>
    </a-scene>
  </body>
</html>
```
<p>These codes show the value I learned from tinkering with A-frame. Some values I learned were using particles, animation, cursor-fuse/fuse-time out, light, geometry, background and ocean. The code particle adds weather into my webpage like snow and rain. Animation helped move my box up and down. CUrsor-fuse/fuse-time helps improve virtual reality in my webpage. The light allowed my box to start glowing in a white color. The background allows me to create a sky which I colored it black. And the ocean allows to create an ocean ecosystem. </p>
<p>Another source I used was <a href="https://jsbin.com/?html,output">jsbin</a>. I will explain what you would see when applying these codes into jsbin. When applying these codes you would create an ocean in the night sky with snow particles, dust particles, smoke particles, and rain particles. There would be a glowing box in the center. And you can enter full screen on the right side of your screen. If you move out you would see smoke creating fireworks and make it look relaxing. This inspiration I created was during my time on the fourth of july i saw many fireworks coming out of the water and saw many different 3d fake particles which inspired me to create what i saw.</p>

<h1>SKILLS:</h1>
<p>Here are some experiences and skill i learned from this blog entry 5.</p>

*Creativity
  * I experienced this skill because at first I didn't know what I wanted to create but when I closed my eyes I was able to picture something I saw in the past which gave me inspiration to create this.

*Time management
  * I experienced this skill because I had a lot of work to finish in school which didn't give me time to fully learn and tinker with my tool. During spring break I was able to tinker with the lost time I had in school which deepened my understanding in A-frame. I was able to finish a lot of my homework which enabled me to finish my Blog before the time limit.
<h1>NEXT STEP</h1>
<p>For my next step I will create a wireframe of my freedom project topic which is business.</p>
[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)



