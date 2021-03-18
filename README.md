# Code Refactor Assignment

## Improving the HTML accessibility and consolidating CSS

The end goal of this exercise was to improve the accessibility for users that may be using screen readers, and to optimize the readability for Search Engine Optimization. 

## Changes made to index.html

The existing code, though almost fully functional, needed changes to optimize readability for SEO and to allow full accessibility to users that may need screen readers to navigate the webpage. 

The existing code had repetitive use of the div tags which can be confusing to the reader as they provide little to no information as to what is in the tags. 

To improve readability, the div tags were appropriately replaced with semantic elements to be able to quickly and easily reference different sections of the code. The new semantic elements used are: **head**, **nav**, **main**, **section**, **aside**, and **footer**.

The headers were also edited to be listed in descending order, as not to have an **h2** below a **h3**.

Within these newly added and improved semantic elements, the reader will now be able to easily reference different sections more easily and seamlessly. 

## Changes made to style.css

The provided CSS document was consolidated by placing items under the same selectors together since they had the same styling rules. It was not necessary to separately list each selector separately with repeated stylings. 

## Links to Horiseon Webpage

[GitHub](https://github.com/joyfullyx/code-refactor)

[Horiseon](https://joyfullyx.github.io/code-refactor/)