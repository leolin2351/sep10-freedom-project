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

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
