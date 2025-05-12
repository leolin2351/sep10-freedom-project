# Entry 6
##### 5/11/25


<h1>CONTEXT:</h1>
<p>For this blog entry i had to create a MVP of my topic of choice. My topic of choice was business because I was influenced on social media of how many entrepreneurs start at a young age and become successful. For the MVP I had to create a website and include my context, business softwares, business hardwares, timeline and use bootstrap. During the start of the school year my teacher told us to research the context, software, hardware and timeline of your choice which would be used for later on in the school year. I had to do many deep dive researches because i had to make my topic of choice for interesting rather than simple. Now after the research I acquired since the start of the school year I was able to create my MVP. During this time I had to create a wireframe of my website for both mobile and computer versions. I had to use my imagination and plan out how  my website should look. It took me some time to complete this assignment because I was overthinking if it should be quick and easy or complex. I chose both because I didn't want to chase the grade but I was spending too much time on it. After this part i had to move on to the create a plan for my website on what bootstrap component i should use and how it would look. This step made me create a schedule I should follow inorder to complete my goals for this website. I needed to create a realistic and doable plan so I could finish it on time. I included carousels, cards, navbar, scroll bar, accordion and many more. All of this led to my final step is to create my website. </p>
<h1>Challenge And Takeaway:</h1>
<h5>During my journey of completing the mvp i had encountered many challenges and takeaways. I had to solve the problem by myself sometimes but also ask my friends and teacher to explain what's wrong. here are 2 challenges i faced and the takeaway i experienced:</h5>
<p>One challenge I faced was my carousel. During class I had to create a carousel to include 3 present day softwares. Here's part of my codes and mistake:</p>


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
<p>As you input the code into JSbin you can see it is unable to generate a capsule because I forgot a script that prevents it from generating.</p>


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
<p>A takeaway I learned during this challenge is that I had the css script. I didn't have the java script which didn't allow me to generate an image because without that script you were not allowed to generate a carousel or your accordion wouldn't work also.</p>
<p>Another challenge I faced was doing an a-frame tinker of my hardwares. I created this to show a simple model of an AI-assistant because many AI-assistance have a lot of flows which make them unable to be global. I created an AI model using an A-frame by using a sphere, box, text bubble, and a hat to add realisticness. My challenge at first was figuring out how I would tinker with my AI-assistant using A-frame. Heres my Aframe code before i added details: </p>


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
  <a-entity html embed></a-entity>
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
<p>A takeaway i learn from this A-frame tinker was i had to be creative because i only knew how to add the head and body of my AI-assistant but i had to add detail so i got creative and usee spheres for the eyes, use cylinder to add a hat and also add a text message. I learned that if I wanted to show my classmates and teachers what I learned from a-frame I had to play around with shapes and a-frame to create this.</p>
<h1>Source:</h1>
<p>When creating my MVP i needed to use some sources to help me build my website. One source i used was <a href="https://getbootstrap.com/docs/5.3/getting-started/introduction/">Bookstrap</a>. This was one of the most important sources I used because Bootstrap is an open-source framework designed to help developers create responsive, mobile-first websites quickly and efficiently. Bootstrap was able to help me complete 50 percent of my MVP because they give you components that you believe best suit your website. I used Bookstrap to add carousels, card, navbar, scroll bar, accordion and many more because bootstrap gave me the code and I had to change some of the things so it worked. Another source i used was <a href="https://aframe.io">A-frame</a>. This is a source i used because i was assigned to create a A-frame model of my hardwares. I didn't feel confident to create a model of my hardwares because I didn't have a lot of skill on designing an AI assistant because I didn't know how much detail needed. But when i went through the A-frame website i was able to get a idea of the model i should create.</p>
<h1>EDP:</h1>
<p>I'm in engineering design 6 because I created a prototype of my hardware which was AI-assistant using Aframe. Now I need to test my prototype because I know there are better ways to improve my model of AI-assistant using a-frame like adding arms and legs to it. After I finished this step of testing my protype i needed to evaluate my prototype because I know it isn't the best prototype model I can create but I used what I had and created a model of it but added some small details to it. I tested how it would be presented to my friends and teachers and how i can improve it during my time in class. </p>
<h1>SKills</h1>
<p>One skill I learned when creating my MVP was being creative because throughout this project I needed to use my creativity and knowledge to create a MVP on my topic of choice. I needed to create a frame first before beginning to plan it. This skill was very important to me because I wanted my website to be different but also outstanding compared to my classmates. I needed to be creative and spend a lot of time designing and making my MVP.</p>
<p>Another skill I learned was Time management because I had to create a plan.md on how I will contribute to my MVP throughout the week. There was a challenge i needed to overcome in order to manage my time which was the camping trip. This was a skill that was challenging because I wasn't allowed to bring electrons to the camping trip. I needed to find a different way to continue my plan which I needed to overlap during my saturday and sunday plan. This was challenging because I needed to complete a lot of school work before continuing my goal of the week. </p>





[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
