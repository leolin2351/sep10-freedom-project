# Entry 6
##### 5/11/25

<h1>CONTEXT:</h1>
<p>For this blog entry i had to create a MVP of my topic of choice. My topic of choice was business because i was influenced on social media of how many entrupear start on a young age and beomce successful. For the MVP i had to create a website and include my context, business softwares, business hardwares, timeline and use bookstrap. During the start of the school year my teacher told us to research the context, software, hardware and timeine of your choice which would be use for later on the school year. I had to do many deep dive researches because i had to make my topic of choice for interesting rather than simple. Now after the research i accuqired since the start of the school year i was able to create my MVP. During this time i had to create a wire frame of my website for both moblie and computer verision. I had to use my imagination and plan out how  my website should look like. It took me some time to complete this assignment because i was overthinking if it should be quick and easy or complex. I choice both because i didnt want to chase the grade but i was spending to much time on it. After this part i had to move on to the create a plan for my website on what bootstrap component i should use and how it would look. This step made me create a schudele i should follow inorder to complete my goals of this website. I needed to create a realistic and do able plan so i can finish it on time. I included carousels, card, navabar, scroll bar, accodion and many more. All of this led to my final step is to create my website. </p>
<h1>Challenge And Takeaway:</h1>
<h5>During my journey of completing the mvp i had encounter many challenges and takeaway. I had to solve the problem by myself sometimes but also ask my friends and teacher to explain whats wrong. here are 2 challenges i faced and the takeaway i exprienced:</h5>
<p>One challenge i faced was my carosuel. During class i had to create a carousel to included 3 present day softwares. Heres part of my codes and mistake:</p>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Business</title>
    <link rel="icon" type="image/x-icon" href="assets/favicon.ico" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet"> 
    <div class="col-xl-5 col-xxl-6 d-none d-xl-block text-center">
            <div id="carouselExampleIndicators" class="carousel slide">
                <div class="carousel-indicators">
                  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="Quickbook.png" class="d-block w-100" alt="...">
                  </div>
                  <div class="carousel-item">
                    <img src="hubspot2.png" class="d-block w-100" alt="...">
                  </div>
                  <div class="carousel-item">
                    <img src="google-workspace1.png" class="d-block w-100" alt="...">
                  </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
        </div>
      </div>
    </div>
  </section>
```
<p>As you input the code into jsbin you can see it unable to generate a caosuel because i forgot a script that prevent it from generating.</p>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Business</title>
    <link rel="icon" type="image/x-icon" href="assets/favicon.ico" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet"> 
    <div class="col-xl-5 col-xxl-6 d-none d-xl-block text-center">
            <div id="carouselExampleIndicators" class="carousel slide">
                <div class="carousel-indicators">
                  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js" integrity="sha384-j1CDi7MgGQ12Z7Qab0qlWQ/Qqz24Gc6BM0thvEMVjHnfYGF0rmFCozFSxQBxwHKO" crossorigin="anonymous"></script>
    <script src="https://aframe.io/releases/1.6.0/aframe.min.js"></script>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="Quickbook.png" class="d-block w-100" alt="...">
                  </div>
                  <div class="carousel-item">
                    <img src="hubspot2.png" class="d-block w-100" alt="...">
                  </div>
                  <div class="carousel-item">
                    <img src="google-workspace1.png" class="d-block w-100" alt="...">
                  </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
        </div>
      </div>
    </div>
  </section>
```
<p>A takeaway i learned during this challenege is that i had the css script i didnt have the java script which didnt allow me to generate a image because without that script you werent allow to generate a carousel or your accodion wouldnt work also.</p>
<p>Another challenge i faced was doing a a-frame tinker of my hardwares. I created this to show a simply model of a AI-assisant because many AI-assistance have alot of flows which make them unable to be global. I created a AI model using A-frame by using sphere, box, text bubble, and a hat to add realistic. My challenge at first was figuring out how i would tinker my AI-assistant using A-frame. Heres my Aframe code before i added details: </p>

```
<!-- Assistant avatar group -->
<a-entity id="assistant" position="0 1.5 -3">
  <!-- Head -->
  <a-sphere radius="0.5" color="#FFC65D"></a-sphere>
<a-box position="0 0.7 -3" color="#4CC3D9"
       event-set__click="_event: click; color: #FF6347"
       onclick="
         document.querySelector('#assistantText').setAttribute('text','value','Hi there! How can I help?');
         document.getElementById('assistant').setAttribute('animation','property: rotation; to: 0 360 0; loop: false; dur: 1000');
       ">
</a-box>
</a-scene>
</body>
```
<p>This is what i had at first because i thought this is all to A-frame but everything was about to change when i got creativity</p>

```
 <!--aframe scene-->
         <body>
<a-scene class="aframebox" embedded>
  <a-entity htmlembed></a-entity>
<!-- Sky background -->
<a-sky color="black"></a-sky>

<!-- Assistant avatar group -->
<a-entity id="assistant" position="0 1.5 -3">
  <!-- Head -->
  <a-sphere radius="0.5" color="#FFC65D"></a-sphere>
  <!-- Left Eye -->
  <a-sphere position="-0.18 0.12 0.45" radius="0.07" color="#222"></a-sphere>
  <!-- Right Eye -->
  <a-sphere position="0.18 0.12 0.45" radius="0.07" color="#222"></a-sphere>
  <!-- Mouth -->
  <a-torus position="0 0 0.48" radius="0.13" radius-tubular="0.025" arc="180"
           rotation="0 0 180" color="#D2691E"></a-torus>
  <!-- Hat Brim -->
  <a-cylinder position="0 0.42 0" radius="0.33" height="0.05" color="#222"></a-cylinder>
  <!-- Hat Top -->
  <a-cylinder position="0 0.62 0" radius="0.18" height="0.22" color="#222"></a-cylinder>
</a-entity>

<!-- Assistant "response" as text -->
<a-entity id="assistantText"
          text="value: Hello! Click the box to greet me.; color: black; width: 2"
          position="0 2.4 -3">
</a-entity>

<!-- Interactive box for user to "ask" -->
<a-box position="0 0.7 -3" color="#4CC3D9"
       event-set__click="_event: click; color: #FF6347"
       onclick="
         document.querySelector('#assistantText').setAttribute('text','value','Hi there! How can I help?');
         document.getElementById('assistant').setAttribute('animation','property: rotation; to: 0 360 0; loop: false; dur: 1000');
       ">
</a-box>
</a-scene>
</body>
```
<p>A takeaway i learn from this A-frame tinker was i had to be creative because i only knew how to add the head and body of my AI-assistant but i had to add detail so i got creative and usee spheres for the eyes, use cylinder to add a hat and also add a text message. I learned that if i wanted to show my classmate and teachers what i learned from a-frame i had to play around with shapes and a-frame to create this.</p>
<h1>Source:</h1>
<p>When creating my MVP i needed to use some sources to help me build my website. One source i used was </p>
[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
