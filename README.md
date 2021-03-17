# 01 HTML, CSS, and Git: Code Refactor Homework Assignment

## Completed Tasks

For this assignment, I refactored the exsisting code from [code-refactor] (.Code/homework/code-refactor/index.html) to make it cleaner and easier to read for the viewer. 

The first steps were to improve and update the semantics of the existing code, making it easier to read and to find and reference the different sections of the code. 

The existing code came with a lot of <div> elements that made it difficult to follow and read, so I was able to replace them with appropriate semantic elements to help the flow of the code. 

I used the <head> element at the top of the code that includes the link to the stylesheet, as well as the title for the tab of the webpage. 

I used the <header> element and nested <nav> into it for the header of the web page. When changing the <div> to <nav>, I found that I had to change .header div on line 27 in style.css to .header nav for the stylesheet to work properly in alignment with the new semantic element. 

I wrapped the main content on the webpage containing the Search Engine Optimization, Online Reputation Management and Social Media Marketing sections into <main> because it contains the bulk of the main information found on the web page, and wrapped the three header sections and their images appropriately in <section>. 

I was uncertain about line 27 containing the class="hero" and why there was a url to the image in style.css instead of using <img>. After doing some research, I came to the conclusion that it is because the image does not contain any informational content, and is for design and styling purposes only. It also would not be a necessary image to be printed, should the user decide to print the page since it does not contain any information beyond the image itself.

For the information in the box on the right side of the webpage, I used the <aside> element since it is not part of the main content of the page and displayed to the side. 

The footer was appropriately wrapped in the <footer> element. 

The other important change that was made was to make the entire webpage accessible. The first image was missing the alt attribute, so one was added with the appropriate value of "search engine optimization."

