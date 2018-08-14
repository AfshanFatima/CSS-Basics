# [CSS Basics   W3Cx -  CSS.0x](https://www.edx.org/course/css-basics-w3cx-css-0x-0)
                      
   #### [During this course, I learned about]()
   * Basic selection of CSS properties
   * Fundamental CSS selectors
   * Designing  page layout through relative positioning with   CSS
   * Best practices in WEb design            

  #### [Module-1](https://courses.edx.org/courses/course-v1:W3Cx+CSS.0x+3T2017/courseware/b8efea36f1874c2a8a0fc6843d20b063/16d9ca5dc6c242eb8b25ec13f8bbb9f4/1?activate_block_id=block-v1%3AW3Cx%2BCSS.0x%2B3T2017%2Btype%40vertical%2Bblock%40d20686012d724fdd819c2b4d791fdd0f)

 ##### Hello World.

 ![alt text](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/9651b21ea92e785368a73893434f5592/asset-v1:W3Cx+CSS.0x+3T2017+type@asset+block/1-4-3_css.PNG)

 <!--
 http://127.0.0.1:55935/index1.html -->

### CSS


CSS, or Cascading Style Sheets, is a style sheet language used to describe the way an HTML or XML document should look to a user. CSS is where you specifiy the color, size, spacing, font and other visual aspects of the content that you create in your markup language document.
Most often you will see CSS used alongside HTML to describe the way a Web page looks and feels. You can have a Web page without CSS, but it would be very difficult to make it look the way you want with just HTML. This is why almost every Web page is a combination of HTML and CSS.
CSS • /si-ɛs-ɛs/ • noun 
Stands for "Cascading Style Sheets". A style sheet language for describing how to display an HTML document.

Sample CSS document:

```
 body {
    background-color: #d0e4fe;  
 }
 
 h1 {
    color: orange;
    text-align: center;
 }
 
 p {
    font-family: "Times New Roman";
    font-size: 20px;
 }
 ```

**Before and after CSS**

**Before CSS:**
*  All documents looked very similar - it was difficult for different companies to express their brand identities in documents
*  possibilities for styling were very limited and style was difficult to control and maintain - style had to be applied to content directly, so you        couldn't update style without having to touch content and vice versa. 
**After CSS:**
*   Content authors didn't have to worry about style, they could just focus on content
*  Content authors didn't have to worry about what device users would view their document on, those considerations could be handled by the CSS
*  Style became much more efficient- a single rule could apply to multiple elements and a single style sheet could apply to multiple documents.


**Bert Bos, and Håkon Lie developed CSS.**

 **Some benefits of CSS:**
*   CSS has a host of specialized tools to give you powerful control over the look and feel of your Web site, much more powerful than the tools provided  by HTML.
*  Designers can style many HTML pages with a single CSS document for a consistent look and feel across an entire Web page and less code to maintain.
*  Separation of content and presentation makes Web site maintenance much simpler as you can address updates in isolation.
*  Over time more and more devices have become internet-capable, and now there are so many different orientations in which your user can view your content. With CSS, you can specifically cater the style to each device to ensure an optimal experience.
*  Some users have specific presentation needs based on personal or technological limitations or preferences. Separating content from presentation  allows these users the option to control how they view content.
*  Before CSS visual elements were almost always achieved with static images, which can have a big affect on network performance. CSS provides an  optimized way to style your page so it can load complex visuals quickly. 


#### [Module-2](https://courses.edx.org/courses/course-v1:W3Cx+CSS.0x+3T2017/courseware/bb30325abfbf47b583784acd793db6dc/5a7d2add3d194df6a33cd131621ae75b/1?activate_block_id=block-v1%3AW3Cx%2BCSS.0x%2B3T2017%2Btype%40vertical%2Bblock%40cff61753c3bf41b89bb7beabce82406d)

##### Building CSS Rules

![alt text](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/152ba1416a059133e7dcd8af8480df6b/asset-v1:W3Cx+CSS.0x+3T2017+type@asset+block/css-intro-2-6-1.png)
<!--
http://127.0.0.1:55935/Module2.html -->


*  Review the basics of HTML.
*  Introduce you to the anatomy of a CSS "rule".
*  Introduce you to the concept of a property and give you a set of properties to get started.
*  Introduce you to selectors and how you can directly attach them to HTML tags.
*   Finally, for your module project, you'll get a get a chance to build the CSS for an HTML page from scratch.


 #### [Module-3](https://courses.edx.org/courses/course-v1:W3Cx+CSS.0x+3T2017/courseware/46a1028808b949b9af0061a363d40b8a/45395061876d4e65a7748e6323ea1669/1?activate_block_id=block-v1%3AW3Cx%2BCSS.0x%2B3T2017%2Btype%40vertical%2Bblock%4074dc1b9273914350a71222d798b10a43)

 ##### Specific HTML element targeting with CSS selectors

![alt text](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/7dca701feeda5a00fad8d50486f3d9ac/asset-v1:W3Cx+CSS.0x+3T2017+type@asset+block/3-6_sol_2.PNG)
<!--
http://127.0.0.1:55935/Module3.html -->


* How to use classes and IDs to independently target HTML elements of the same type.
*  How to apply different style to the same element based on the way the user interacts with that element using pseudo-classes.
*   How to scope style rules using contextual selectors and the HTML inheritance structure of your document.
*   What the "Cascading" part of "Cascading Style Sheets" mean.
 
**Example**

```
 p {
     color: white;     
     background-color: midnightblue;
     font-size: large;
   }
 
 .middle {
       color: darkviolet;
       background-color: lightgray;
       padding-left: 120px;
       padding-right: 120px;
       font-size: large:
   }
 
 #bottom {
       background-color: transparent;
       color: black;
       font-family: 'Franklin Gothic Medium';    
    }
 ```
 
#### [Module-4](https://courses.edx.org/courses/course-v1:W3Cx+CSS.0x+3T2017/courseware/2fb0b177f7594d2aa29f0ffa9e3b8b0a/cc87ccb0d8f243f98b2f17c1955c0298/1?activate_block_id=block-v1%3AW3Cx%2BCSS.0x%2B3T2017%2Btype%40vertical%2Bblock%408347080b2233486082d5154ee2e14ad6)

##### Layout and positioning

![alt text](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/07fb2ab374e9dcd5a05257cf25507fde/asset-v1:W3Cx+CSS.0x+3T2017+type@asset+block/4-6_Kasey_Resume.PNG)
<!--
http://127.0.0.1:50749/Module4.html -->

* How to use padding and margin to position elements relative to each other and the window.
*  How to use alignment to control how your content sits within its HTML element.
* How to use the float property to let multiple HTML elements share horizontal space.
* How to use relative positioning to design your page so that it maintains its layout regardless of screen size.

  
  The Box Model is how Web browsers see individual HTML elements. Each element is comprised of 4 areas: the element, the padding, the border and the margin.


#### [Module-5](https://courses.edx.org/courses/course-v1:W3Cx+CSS.0x+3T2017/courseware/12e8f1585d88470e95f54cf0ff6a1a00/6c9058a29dc5493fbb43332c6bc3b550/1?activate_block_id=block-v1%3AW3Cx%2BCSS.0x%2B3T2017%2Btype%40vertical%2Bblock%4089308c49a101442a8adcf2485a5ecffa)

##### Designing your Web site for your audience


*  Learn how to apply basic design principals based on the context of your HTML elements.
*  Explore CSS and HTML's accessibility features and how you can design your page to accommodate a diverse audience.
*  Introduce you to features to help internationalize your page and make it easier for those viewing it in different languages.
*  Discuss the lessons learned from historical Web design trends and give you the new tech we use instead.
*  Meet the newest fashions in Web design to help you give your Web pages a modern look and feel.


### CSS best practices


#### Executive summary


*   Logical source order: 

   The order of the HTML content should make sense even without the CSS: for accessibility, mobile optimization, device adaptability, and long-term maintainability.

*   Liquid layouts and relativity: 

   Use smart relative sizing: to optimize layouts while minimizing media query code forks.

*  Media queries: 

   Adapt to screen size changes; get font size adaptation free by using ems.

*  Prevent zombie code:

   Dead code may come alive as CSS changes. Delete it before it does, and ruins your layout.
   

#### Test in multiple browsers:


*   Your favorite browser is not always right.
*  Don't use proprietary features!
*  Keep the Web open to everyone! Don't rely on the latest -WebKit-       invention.
*  Turn off CSS:

   A well-coded page will be understandable without it. 
 
 
 #### Foundations


*  Indent your code for readability ease.
*  Learn how to code CSS before relying on frameworks (such as Bootstrap, etc).
*  Separate content and style.
*  Use semantic markup, ie., "classes for meaning, not for show". 
   Use <table> for tabular data: don't use tables for layout, but if your content is tabular like a catalog, a calendar, or a price list, then the table element is the correct markup.
*  Linearized logical source order
   The order of the HTML content should make sense even without the CSS. 


Benefits are numerous as it works best:

*  for long-term site maintainability
*  for mobile
*  for accessibility
*  as a foundation for device adaptation (media queries)
*  Linguistic variations: set the language correctly for better typography (see the section entitled "why Internationalization is important")
    
    
#### Testing
 

*   Test without CSS: turn off CSS, and if the page       makes no sense, fix your markup.
*  Test in multiple environments:
*  Resize the window.
*  Zoom the text.
*  Try a mobile browser.
*  Navigate by keyboard.
*  Test in multiple browsers: remember that just testing in Chrome does not work for everyone! 


 
#### Adaptability


*  Media queries: set media query breakpoints in em or ch, not always in px.
*  Liquid layouts and relativity: what is your sizing based on?
*  Containing block size? → Use percents.
*  Viewport size? → Use viewport units: vw, vh, vmin, vmax.
*  Font height? → Use em or rem.
*  Font pitch? → Use em or ch.
*  Content size? → Use auto or min-content/max-content.
*  Combination of the above? → Use the appropriate layout formulas: flex, min-width, max-width, etc.
   Absolute units are usually the wrong answer.
   
	
#### Defensive Coding 

*  !important means never override- to use with caution.
*  Use !important to define overriding rules, not for fixups.
*  Duplicate selectors if you need to increase specificity.
*  Simplify selectors if you need to decrease specificity.
*  Don't over-escalate: understand your code, and don't overkill.


   For example, avoid:
  ```

	      * z-index:  
          9999999999999999999999999999999999999;
	      * position: absolute; left: -10000000000px

  ```
          
*  Drop dead code: you tried something and it didn't work? Delete it right away!
*  Code to Standard.  
*  Don't rely on proprietary extensions.
*  Don't use experimental features in production or commit to keeping up-to-date.
*  Provide fallbacks / use @supports.



