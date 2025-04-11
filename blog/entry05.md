# Entry 5
##### 4/11/25

<h1>CONTEXT:</h1>
<p>In this blog entry we continued where we left off on blog 4. We have to choose a tool on blog 4 but tinker alittle bit with it. But in this blog entry we had to continue where we left off in blog 4. I choose A-frame because when watching A-frame i was able to see a 3d visual of a scene and i got curious of how i can do it. I started to tinker with what i was curioused about. During this week i was tinkering around witht the particle and added camera perspective. I was able to learn these code because i watched <a href="https://www.youtube.com/watch?v=8BeoaNm5kzw">Sulaeman</a>. He taught me how to add particle into my webpage and showed me different types of particle. Which got me curioused and made me want to try it myself. Here my code and what i did:</p>

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
<p>At first i didnt know that we can do this with A-frame but with more knowledge and watching sulaeman i was able to deeper understand more context on A-frame and understand how to change alot of things in my webpage. I didnt know their was different types of particle besides rain but after tinkering around, my friend told me that in A-frame you can ask dust,snow, smoke. These information from my friend shocked my knowledge because i didnt know these particle existed but after adding and tinkering around with these particle i was able to create something chaotic.</p>
<img src="blob:chrome-untrusted://file-manager/812b8a45-34f6-45f9-8556-96eb83c48fd6" alt="...">

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
