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
    
       Examples of some HTML elements:
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>

 ###     Start tag	     Element content	        End tag
          <h1>	         My First Heading	       </h1>
          <p>	          My first paragraph.	      </p>
          
         
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
   
        -Attributes provide additional information about 
        elements
     

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

 ```
 ###  The alt Attribute
      The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason 
      cannot be displayed. This can be due to a slow connection, or an error in the src attribute.
      
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
  
      **The following example specifies English as the language:**
```jsx
           <!DOCTYPE html>
            <html lang="en">
             <body>
             ...
            </body>
            </html>
```

```
###  The title Attribute
      The title attribute defines some extra information about an element.
      The value of the title attribute will be displayed as a tooltip when you mouse over the element:

**Example**
```jsx
              <p title="I'm a tooltip">This is a paragraph.</p>
```

###   Comments      
      
      HTML comments are not displayed in the browser, but they can help document your HTML source code.

**Example**
 ```jsx
             <!-- Write your comments here -->
 ```    

**Example**
```jsx
             <!-- This is a comment -->
```

##  3. Text Formatting
     Formatting elements were designed to display special types of text:
     -<b> - Bold text
     -<strong> - Important text
     -<i> - Italic text
     -<sub> - Subscript text
     -<sup> - Superscript text

   
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
       A paragraph always starts on a new line, 

**Example**
```jsx
                    <p>This is a paragraph.</p>
                    <p>This is another paragraph.</p>
 ```
 ##  4. Links and Anchors 

 ###  What is the HTML <link> tag?

      The HTML <link> tag establishes a link between the current document and an external resource.

**Example**
 ```jsx
          <link rel="relationship_value" 
```

###   What is Anchor Tag?
      The Anchor tag in HTML can be defined as a means to create a hyperlink that can link your current page to another page.
 ```

 ```    
 ## 5. Images and Multimedia
 ###   HTML Image 
      The HTML <img> tag is used to embed an image in a web page.
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

**Example**
```jsx
          <img src="img_chania.jpg" alt="Flowers in Chania">
```
###  The alt Attribute
       The required alt attribute provides an alternate text for an image, if the user for some reason cannot view image(because 
       of slow connection.)
       
       The value of the alt attribute should describe the image:
      
**Example**
 ```jsx 

           <img src="img_chania.jpg" alt="Flowers in Chania">
```

###    What is Multimedia?
       Multimedia comes in many different formats. It can be almost anything you can hear or see, like images, 
        Audio, videos, records etc.

       **Web pages often contain multimedia elements of different types and formats.**

###    Multimedia Formats
       -Multimedia elements (like audio or video) are stored in media files.
       -Multimedia files have formats and different extensions like: .mp3, .mp4 -etc

 ###   The HTML <video> Element
       To show a video in HTML, use the <video> element:

**Example**
 ```jsx
     <video width="320" height="240" controls>
     <source src="movie.mp4" type="video/mp4">
     </video>      
```   

###    HTML <video> Autoplay
       To start a video automatically, use the autoplay attribute:

**Example**
```jsx
     <video width="320" height="240" controls autoplay>
     <source src="movie.mp4" type="video/mp4"></video>
```
###   The HTML <audio> Element
      To play an audio file in HTML, use the <audio> element:

**Example**
```jsx      
         <audio controls>
          <source src="horse.mp3" type="audio/mpeg">
        </audio>
```

###    HTML <audio> Autoplay
       To start an audio file automatically, use the autoplay attribute:
        
**Example**
 ```jsx       
          <audio controls autoplay>
            <source src="horse.mp3" type="audio/mpeg">
          </audio>
```
##  6.Lists
       HTML lists allow web developers to group a set of related items in lists.

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

## 9.Semantic HTML
###  What are Semantic Elements?
     Semantic tags in HTML are used to clearly define the structure and meaning of web content

###  example of semantic elements
  
```jsx
.<article>
.<details>
.<footer>
.<header>
.<nav>
```

## 10.HTML5 Features
   Now let’s have a look at all the new features that were added in HTML5 that make it better than HTML :

###  .Intro of audio and video: 
     Audio and Video tags are the two major addition to HTML5. It allows developers to embed a video or audio on their website. 

**Example:**
```jsx
<!DOCTYPE html> 
<html> 
<body> 
<h2>Example of video and audio tag</h2> 
    
  <video  width = "300" height = "200" controls autoplay> 
       <source src = "/html5/foo.mp4" type = "video/mp4" />    
   </video> 
    
   <audio controls autoplay> 
       <source src = "/html5/audio.ogg" type = "audio/ogg" /> 
       <source src = "/html5/audio.wav" type = "audio/wav" /> 
   </audio> 
</body> 
</html> 
```
## 11.References
 ### https://www.w3schools.com/html/default.asp
 ### https://www.geeksforgeeks.org/html-introduction/
