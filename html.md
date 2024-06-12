# HTML Documents

1.HTML Basics:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph.</p>
</body>
</html>

2.HTML Elements


.Headings:

<h1>This is a heading</h1>
<h2>This is a subheading</h2>
<h3>This is a smaller subheading</h3>

.Paragraphs:

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

.Links:

<a href="https://www.example.com">This is a link</a>

.Images:

<img src="image.jpg" alt="Description of image">

.List:

     .Ordered List:

     <ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
    </ol>

    .Unordered List:

    <ul>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
    </ul>

3.HTML Attributes

  .Class and ID:

  <p class="intro">This is a paragraph with a class.</p>
  <p id="unique">This is a paragraph with an ID.</p>

   .Style:

   <p style="color:blue;">This is a paragraph with inline style.</p>

4.HTML Forms

  <form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <input type="submit" value="Submit">
    </form>

5.HTML Tables

  <table>
    <tr>
        <th>Heading 1</th>
        <th>Heading 2</th>
    </tr>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
    <tr>
        <td>Row 2, Cell 1</td>
        <td>Row 2, Cell 2</td>
    </tr>
   </table>

6.HTML Semantic Elements

  <header>
    <h1>My Website</h1>
</header

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>
<main>
    <article>
        <h2>Article Title</h2>
        <p>This is an article.</p>
    </article>
    <section>
        <h2>Section Title</h2>
        <p>This is a section.</p>
    </section>
</main>
<footer>
    <p>&copy; 2024 My Website</p>
</footer>

 
### HTML Document Structure

- **DOCTYPE Declaration:**

```html
<!DOCTYPE html>

.HTML Element:

<html lang="en">
    <!-- head and body go here -->
</html>

.Head Element:

 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- other meta tags, links to stylesheets, scripts etc. -->
</head>

.Body Element:

  <body>
    <!-- content goes here -->
</body>


Advanced HTML Topics

1.HTML5 Elements

 .Audio:

 <audio controls>
    <source src="audio-file.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

 .Video:

   <video controls>
    <source src="video-file.mp4" type="video/mp4">
    Your browser does not support the video element.
</video>

 .Canvas:

  <canvas id="myCanvas" width="200" height="100"></canvas>
<script>
    var c = document.getElementById("myCanvas");
    var ctx = c.getContext("2d");
    ctx.fillStyle = "#FF0000";
    ctx.fillRect(0, 0, 150, 75);
</script>

  .SVG

    <svg width="100" height="100">
    <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
</svg>

2. Responsive Design

  .Viewport Meta Tag:

   <meta name="viewport" content="width=device-width, initial-scale=1.0">

    .Media Queries:

     <style>
    body {
        font-size: 16px;
    }
    @media (max-width: 600px) {
        body {
            font-size: 14px;
        }
    }
</style>

3. Forms and Validation

  .Required Fields:

   <input type="text" required>

   .Pattern Validation:

    <input type="text" pattern="[A-Za-z]{3}">

4. Accessibility

   .Alt Text for Images:

    <img src="image.jpg" alt="Description of image">

    .ARIA Roles:

     <div role="navigation">
    <!-- navigation links -->
</div>

     

  **Thanks & Regards <br>
  Manish kumar jha <br>
  KeenAble Computers Pvt. Ltd.**       

           
