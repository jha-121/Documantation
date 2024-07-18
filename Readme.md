# HTML
<img src= "html5_bg_no_icons.png" alt="formats" width="" height="" >
 
## TABLE OF CONTENT
### 1.  Introduction to HTML
### 2.  HTML Basics
### 3.  Text Formatting
### 4.  Links and Anchors   
### 5.  Images and Multimedia   
### 6.  Lists
### 7.  Tables   
### 8.  Forms    
### 9.  Semantic HTML
### 10. HTML5 Features
### 11. References

 ## 1. Introduction to HTML
       
  ###  What is HTML?
       - HTML stands for Hyper Text Markup Language.
       - HTML is the standard markup language for creating Web pages.
       - HTML describes the structure of a Web page.

 ###   History of HTML
       HTML was created by Sir Tim Berners-Lee in late 1991 but was not officially released.
       It was published in 1995 as HTML 2.0. HTML 4.01 was published in late 1999 and was a major version of HTML.
 ###   Year	        Version
       1989	        Tim Berners-Lee invented www
       1991	        Tim Berners-Lee invented HTML
       1993	        Dave Raggett drafted HTML+
       1995	        HTML Working Group defined HTML 2.0
       1997	        W3C Recommendation: HTML 3.2
       1999	        W3C Recommendation: HTML 4.01
       2000	        W3C Recommendation: XHTML 1.0
       2008	        WHATWG HTML5 First Public Draft
## 2.  HTML Basics
       
       - All HTML documents must start with a document type declaration: <!DOCTYPE html>.

       - The HTML document itself begins with <html> and ends with </html>.

       - The visible part of the HTML document is between <body> and </body>. 
       
**Example**
  ```jsx  
        <!DOCTYPE html>
         <html>
         <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
        </body>
        </html>  
 ``` 
 ###   HTML Tags and Elements
       
       The HTML element is everything from the start tag to the end tag:
       <tagname>Content goes here...</tagname>
       Examples of some HTML elements:
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>

 ###       Start tag	           Element content	         End tag
            <h1>	               My First Heading	          </h1>
            <p>	                   My first paragraph.	      </p>
            <br>	                   none	                   none
            **Example**
  ```jsx          
      <!DOCTYPE html>
     <html>
    <body>

       <h1>My First Heading</h1>
       <p>My first paragraph.</p>

      </body>
    </html>
 ```  
 ###  Attributes
       
       -All HTML elements can have attributes
       -Attributes provide additional information about 
        elements
       -Attributes are always specified in the start tag
       -Attributes usually come in name/value pairs like: name="value"

###  The href Attribute
      
      The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:  

**Example**              
  ```jsx
                <a href="https://www.w3schools.com">Visit W3Schools</a>
  
  ```   
 ###  The src Attribute   
       The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be 
        displayed:

**Example**
  ```jsx
        
                  <img src="img_girl.jpg">
  ```
###   The width and height Attributes
      The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in 
      pixels):
      
**Example**
 ```jsx
                  <img src="img_girl.jpg" width="500" height="600">
 ```
 ###  The alt Attribute
      The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason 
      cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a 
      screen reader.
      
**Example**
 ```jsx
                  <img src="img_girl.jpg" alt="Girl with a jacket">
```
###  The style Attribute
     
     The style attribute is used to add styles to an element, such as color, font, size, and more.
     
**Example**
```jsx
                   <p style="color:red;">This is a red paragraph.</p>
```
###  The lang Attribute
      You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. 
      This is meant to assist search engines and browsers.
      **The following example specifies English as the language:**
```jsx
           <!DOCTYPE html>
            <html lang="en">
             <body>
             ...
            </body>
            </html>
```
      Country codes can also be added to the language code in the lang attribute. So, the first two characters define the 
      language of the HTML page, and the last two characters define the country.

**The following example specifies English as the language and United States as the country:**
```jsx

       <!DOCTYPE html>
       <html lang="en-US">
        <body>
        ...
       </body>
       </html>
```
###  The title Attribute
      The title attribute defines some extra information about an element.
      The value of the title attribute will be displayed as a tooltip when you mouse over the element:

**Example**
```jsx
              <p title="I'm a tooltip">This is a paragraph.</p>
```
###   Chapter Summary
      All HTML elements can have attributes
      The href attribute of <a> specifies the URL of the page the link goes to
      The src attribute of <img> specifies the path to the image to be displayed
      The width and height attributes of <img> provide size information for images
      The alt attribute of <img> provides an alternate text for an image
      The style attribute is used to add styles to an element, such as color, font, size, and more
      The lang attribute of the <html> tag declares the language of the Web page
      The title attribute defines some extra information about an element.

###   Comments      
      
      HTML comments are not displayed in the browser, but they can help document your HTML source code.

**Example**
 ```jsx
             <!-- Write your comments here -->
 ```     
###   Add Comments
    
    With comments you can place notifications and reminders in your HTML code:

**Example**
```jsx
             <!-- This is a comment -->

             <p>This is a paragraph.</p>

             <!-- Remember to add more information here -->
```
##  3. Text Formatting
     Formatting elements were designed to display special types of text:
     -<b> - Bold text
     -<strong> - Important text
     -<i> - Italic text
     -<em> - Emphasized text
     -<mark> - Marked text
     -<small> - Smaller text
     -<del> - Deleted text
     -<ins> - Inserted text
     -<sub> - Subscript text
     -<sup> - Superscript text
###  HTML <b> and <strong> Elements
     
     The HTML <b> element defines bold text, without any extra importance.

**Example**
 ```jsx
              <b>This text is bold</b>
```
     The HTML <strong> element defines text with strong importance. The content inside is typically displayed in bold.
     
**Example**
```jsx
               <strong>This text is important!</strong> 
```    
###  HTML <i> and <em> Elements
      The HTML <i> element defines a part of text in an alternate voice or mood. 
      The content inside is typically displayed in italic.

      Tip: The <i> tag is often used to indicate a technical term, a phrase from another language, 
      a thought, a ship name, etc.

**Example**
 ```jsx
            <i>This text is italic</i>
```
      The HTML <em> element defines emphasized text. The content inside is typically displayed in italic.

      Tip: A screen reader will pronounce the words in <em> with an emphasis, using verbal stress.

**Example**
```jsx
            <em>This text is emphasized</em>
```
###  HTML <small> Element
      The HTML <small> element defines smaller text:

**Example**
```jsx
               <small>This is some smaller text.</small>
```
###   HTML <mark> Element
         The HTML <mark> element defines text that should be marked or highlighted:
         
**Example**
```jsx
      <p>Do not forget to buy <mark>milk</mark> today.</p>
```
###  HTML <del> Element
          The HTML <del> element defines text that has been deleted from a document. 
          Browsers will usually strike a line through deleted text:

**Example**
```jsx
                  <p>My favorite color is <del>blue</del> red.</p>
```
###  HTML <ins> Element
          The HTML <ins> element defines a text that has been inserted into a document.
           Browsers will usually underline inserted text:
           
**Example**
```jsx
                  <p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
```
###  HTML <sub> Element
           The HTML <sub> element defines subscript text. Subscript text appears half a character below the normal line,
            and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:
           
 **Example**
```jsx
                  <p>This is <sub>subscripted</sub> text.</p>\
```
###  HTML <sup> Element
            The HTML <sup> element defines superscript text. Superscript text appears half a character above the normal line, 
            and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:
           
 **Example**
```jsx
                   <p>This is <sup>superscripted</sup> text.</p>
```
##   HTML Headings
       HTML headings are defined with the <h1> to <h6> tags.

       <h1> defines the most important heading. <h6> defines the least important heading.
       
**Example**
```jsx
                   <h1>Heading 1</h1>
                   <h2>Heading 2</h2>
                   <h3>Heading 3</h3>
                   <h4>Heading 4</h4>
                   <h5>Heading 5</h5>
                   <h6>Heading 6</h6>
 ```
 ##  HTML Paragraphs
       The HTML <p> element defines a paragraph.

       A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before 
       and after a paragraph.

**Example**
```jsx
                    <p>This is a paragraph.</p>
                    <p>This is another paragraph.</p>
 ```
 ##  4. Links and Anchors 

 ###  What is the HTML<link> tag?

      The HTML <link> tag establishes a link between the current document and an external resource.This tag is usually used to 
      link to an external stylesheet, add a favicon to a website, or preload resources to improve page load performance. Here's 
      its basic structure: 

**Example**
 ```jsx
          <link rel="relationship_value" 
          type="MIME_type" 
          href="resource_location" 
          media="media_type" 
          sizes="widthxheight" 
          hreflang="language_code" 
          as="resource_type">     
```
###   Hypertext 
        Hypertext can be defined as the text shown on your web browser's screen, which contains hyperlinked data 
        (data here means from which document it will go to which document) and hence leads readers to different 
        web pages by clicking on them. In this chapter, you will learn how to create your hyperlinks and use them 
        to build websites and web pages.

###   What is Anchor Tag?
      The Anchor tag in HTML can be defined as a means to create a hyperlink that can link your current page on 
      which the text is being converted to hypertext via <a> (anchor tag) to another page. This anchoring from 
      one page to another is made possible by the attribute "href", which can be abbreviated (hypertext reference).

###   Href attribute
       The attribute 'href' of the Anchor tag is implemented for defining the address or path to which this hypertext will
        get linked. In other words, it can be said that it directs you out of your page to that destination page, whose link
        you have mentioned within the double quotes of the href attribute as value. The syntax for an anchor tag with 
        href attribute looks something like this:

**Example**
 ```jsx     
      <a href="URL">Text Here</a>
 ```   
 ###  Appearance of HTML <a> tag

      Since Anchor tags are used for giving hyperlinks, you might have noticed that they change color based on certain 
      situations, such as unvisited, clicked, visited, etc. Let's see their color code concerning their activity:

      -An unvisited link gets displayed with properties like underlined, and the color is blue.

      -A link that is visited gets displayed as underlined with color as purple.

      -A link that is an active link gets displayed as underlined with red color.

       Still, many web developers will deposit their link colors in their web pages to match their site's color scheme.
       Here's the format:

**Example**
 ```jsx
              <body bgcolor="red" text="yellow" link="blue" alink="#FFFF00" vlink="#FF00FF">
 ```
        You can also provide hex code for colors (as you can see from the above example), or else you can use specific 
        words for each color, which is acceptable by the browser.

 ```    
 ##  5.Images and Multimedia
 ###   HTML Image 
      The HTML <img> tag is used to embed an image in a web page.

      Images are not technically inserted into a web page; images are linked to web pages. The <img> 
      tag creates a holding space for the referenced image.

      The <img> tag is empty, it contains attributes only, and does not have a closing tag.

      The <img> tag has two required attributes:

      src - Specifies the path to the image
      alt - Specifies an alternate text for the image
      
**Example**
```jsx
         <img src="url" alt="alternatetext">
```
###  The src Attribute
      The required src attribute specifies the path (URL) to the image.

      -Note: When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it 
       into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, 
       otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser 
       cannot find the image.

**Example**
```jsx
          <img src="img_chania.jpg" alt="Flowers in Chania">
```
###  The alt Attribute
       The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because 
       of slow connection, an error in the src attribute, or if the user uses a screen reader).

       The value of the alt attribute should describe the image:
      
**Example**
 ```jsx 

           <img src="img_chania.jpg" alt="Flowers in Chania">
```
###   Image Size - Width and Height
      You can use the style attribute to specify the width and height of an image.
      
**Example**
 ```jsx     
         <img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
```
        Alternatively, you can use the width and height attributes:
         
**Example**
```jsx
         <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
```
###    What is Multimedia?
       Multimedia comes in many different formats. It can be almost anything you can hear or see, like images, 
       music, sound, videos, records, films, animations, and more.

       **Web pages often contain multimedia elements of different types and formats.**

###    Browser Support
       The first web browsers had support for text only, limited to a single font in a single color.
       Later came browsers with support for colors, fonts, images, and multimedia!

###    Multimedia Formats
       -Multimedia elements (like audio or video) are stored in media files.
       -The most common way to discover the type of a file, is to look at the file extension.
       -Multimedia files have formats and different extensions like: .wav, .mp3, .mp4, .mpg, .wmv, and .avi.

###    Common Video Formats
    	 -There are many video formats out there.
       -The MP4, WebM, and Ogg formats are supported by HTML.
 <img src= "pic_video.jpg" alt="formats" width="" height="" >
 
 -The MP4 format is recommended by YouTube.

 ###   The HTML <video> Element
       To show a video in HTML, use the <video> element:

**Example**
 ```jsx        
               <video width="320" height="240" controls>
               <source src="movie.mp4" type="video/mp4">
              <source src="movie.ogg" type="video/ogg">
             Your browser does not support the video tag.
               </video>   
```   
###   How it Works
       The controls attribute adds video controls, like play, pause, and volume.
       It is a good idea to always include width and height attributes. If height and width are not set, 
       the page might flicker while the video loads.
       The <source> element allows you to specify alternative video files which the browser may choose from. 
       The browser will use the first recognized format.
       The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> 
       element.

###    HTML <video> Autoplay
       To start a video automatically, use the autoplay attribute:

**Example**
```jsx
          <video width="320" height="240" autoplay>
          <source src="movie.mp4" type="video/mp4">
          <source src="movie.ogg" type="video/ogg">
          Your browser does not support the video tag.
          </video>
```
###   The HTML <audio> Element
      To play an audio file in HTML, use the <audio> element:

**Example**
```jsx      
          <audio controls>
          <source src="horse.ogg" type="audio/ogg">
          <source src="horse.mp3" type="audio/mpeg">
          Your browser does not support the audio element.
          </audio>
```
###    HTML Audio - How It Works
       The controls attribute adds audio controls, like play, pause, and volume.
       The <source> element allows you to specify alternative audio files which the browser may choose from. 
       The browser will use the first recognized format.
       The text between the <audio> and </audio> tags will only be displayed in browsers that do not support
       the <audio> element.

###    HTML <audio> Autoplay
       To start an audio file automatically, use the autoplay attribute:
        
**Example**
 ```jsx       
             <audio controls autoplay>
             <source src="horse.ogg" type="audio/ogg">
             <source src="horse.mp3" type="audio/mpeg">
             Your browser does not support the audio element.
             </audio>
```
##  6.Lists
       HTML lists allow web developers to group a set of related items in lists.

**Example**

       An unordered HTML list:                       An ordered HTML list:
            Item                                         First item
            Item                                         Second item
            Item                                         Third item
            Item                                         Fourth item

###   Unordered HTML List
       An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
       The list items will be marked with bullets (small black circles) by default:

**Example**
 ```jsx      
           <ul>
            <li>Coffee</li>
            <li>Tea</li>
            <li>Milk</li>
           </ul>
```
###   Ordered HTML List
       An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
       The list items will be marked with numbers by default:

**Example**
```jsx       
                   <ol>
                      <li>Coffee</li>
                      <li>Tea</li>
                      <li>Milk</li>
                   </ol>
```
##   7.Tables 
       HTML tables allow web developers to arrange data into rows and columns.
<img src= "Screenshot 2024-06-15 123800.png" alt="" width="" height="" >

       Define an HTML Table
       A table in HTML consists of table cells inside rows and columns.

**Example**

 ```jsx
               <table>
                 <tr>
                    <th>Company</th>
                    <th>Contact</th>
                    <th>Country</th>
                  </tr>
                  <tr>
                    <td>Alfreds Futterkiste</td>
                    <td>Maria Anders</td>
                    <td>Germany</td>
                  </tr>
                   <tr>
                   <td>Centro comercial Moctezuma</td>
                   <td>Francisco Chang</td>
                   <td>Mexico</td>
                   </tr>
              </table>
```
### Table Cells
     Each table cell is defined by a <td> and a </td> tag.

**Example**
```jsx
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>
```
### Table Rows
    Each table row starts with a <tr> and ends with a </tr> tag.

**Example**
```jsx
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```
### Table Headers
    Sometimes you want your cells to be table header cells. In those cases use the <th> tag instead of the <td> tag:

**Example**
```jsx
<table>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```
##  8.Forms 
    An HTML form is used to collect user input. The user input is most often sent to a server for processing.
<img src= "Screenshot 2024-06-17 150707.png" alt="formats" width="" height="" >  

### The <form> Element
    The HTML <form> element is used to create an HTML form for user input:
```jsx
<form>
.
form elements
.
</form>
```
###  Text Fields
     The <input type="text"> defines a single-line input field for text input.

**Example**
A form with input fields for text:
```jsx
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```
## 9.Semantic HTML
###  What are Semantic Elements?
     A semantic element clearly describes its meaning to both the browser and the developer.
     Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.
     Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.

###  Semantic Elements in HTML
     Many web sites contain HTML code like: <div id="nav"> <div class="header"> <div id="footer"> to indicate
     navigation, header, and footer.
     In HTML there are some semantic elements that can be used to define different parts of a web page:  
```jsx
.<article>
.<aside>
.<details>
.<figcaption>
.<figure>
.<footer>
.<header>
.<main>
.<mark>
.<nav>
.<section>
.<summary>
.<time>
```
<img src= "img_sem_elements.gif" alt="formats" width="" height="" >  

###  HTML <section> Element
     The <section> element defines a section in a document.
     According to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading."

**Examples of where a <section> element can be used:**
```jsx
.Chapters
.Introduction
.News items
.Contact information
```
     A web page could normally be split into sections for introduction, content, and contact information.

###  Example
```jsx
 Two sections in a document:
<section>
<h1>WWF</h1>
<p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
</section>

<section>
<h1>WWF's Panda symbol</h1>
<p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section>
```
## 10.HTML5 Features
   Now let’s have a look at all the new features that were added in HTML5 that make it better than HTML :

###  .Intro of audio and video: 
     Audio and Video tags are the two major addition to HTML5. It allows developers to embed a video or audio on their website. 
     HTML5 video can use CSS and CSS3 to style the video tag. You can change the border, opacity, reflections, gradients, 
     transitions, transformations, and even animations. HTML5 makes adding video super-fast and without having to build a video 
     player. This saves time for the developer and offers the client a superior and more affordable solution.

**Example:**
```jsx
<!DOCTYPE html> 
<html> 
<body> 
<h2>Example of video and audio tag</h2> 
    
  <video  width = "300" height = "200" controls autoplay> 
       <source src = "/html5/foo.ogg" type ="video/ogg" /> 
       <source src = "/html5/foo.mp4" type = "video/mp4" /> 
        Your browser does not support the video element. 
   </video> 
    
   <audio controls autoplay> 
       <source src = "/html5/audio.ogg" type = "audio/ogg" /> 
       <source src = "/html5/audio.wav" type = "audio/wav" /> 
        Your browser does not support the audio element. 
   </audio> 
</body> 
</html> 
```
## 11.References
 ### https://www.w3schools.com/html/default.asp
 ### https://www.geeksforgeeks.org/html-introduction/
