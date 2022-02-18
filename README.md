# Challenge 1

For this challenge, the task is to refactor an existing webpage to make it clearer to read as it is important and best practice for typing clean code.

The impotance of clean code:
* Helps clients and collaborators navigate and read through the code
* Makes it easier to understand each elements and the purpose of each line
* Ensures it more accessible for people with dissabilities 
* Optomized for search engines
* Help the clients avoid litigations

By the end of it, the website should still look the same but the html and css code should look much cleaner and concise.

What I did to the HTML
* Changed all the div element to a more discriptive element such as
    * section to indicate a new section, this way you can distingush each part of the webpage 
    * nav for the search bar up top to indicate its used to navigate to another page
* change some div into sections to indicate which part of the webpage each code is used for so its easier to read while you inspect elements
* took out the id for footer and made it a footer section instead of the body, since its assumed the watermarks are going to be on every page on the site
* made use of white spaces so whoever is reading it the eyes have an easier time following 

What I did to the CSS
* consolodidated similar css attributes to make it less redundant
* organized by id to make it easier to navigate the css page if there was a change a collaaborator or you would like to make
* Since I changed the footer from a class, I had to changed the selector to a element selector

What I learned:
* By the end of it, although the webpage still looked the same, the html and css was much easier for me to navigate and make adjustments. 
* Each line of code made more sense after all the div elements were changed to something more topical to the use of the page
* my eyes were not as overwhelmed looking at it when the sections had white spaces. My brain was able to process each section one at a time instead of trying to look at everything.