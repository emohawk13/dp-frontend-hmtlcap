Assignment - HTML Capstone

I chose to replicate the wordpress site: https://wordpress.org/themes/twentytwentytwo/

A great way to practicing coding is to replicate a professional website as closely as you can. This practice helps you see new ways of building and inspires you to find solutions to new challenges.

Replicate a page layout of either a webpage or webpage template.

Replicate one of the following:
Wordpress blog webpage template
A wikipedia page
An ecommerce shop's view of products
A social media site you enjoy
Another frequently visited webpage

Try writing an HTML mockup over the template. Create a series of boxes on a blank whiteboard or paper ot represent each element on the page. Use lines in t he boxes to show where text is and an "X" through the box shows where images go. Write your tags and attributes on the inside of each box.
After developing the mockup, develop your division containers. Find the patterns wihin the template and write your classes accordingly.
Fill in each division container with the correct tags, attributes and elements from your mockup.
Focus on creating the structure of the layout. Use filler or simple information such as the "Lorem Ipsum" phrase.

Explore nested tables. Be sure to pay attention to all tag wrapping and to organize your tag structure.
Include a link to your git repository or repl in the field below.

refactor notes:
HTML file is placed with a variety of elements that help match the wordpress structure. Navigation works as expected. A wireframe has been provided that can help organize the coding process. The form page has adequate structuring in most eleements. Here are considerations: 1. In the index.html page, I removed all divs that didn't have a class name associated with them. Based on the styling in the html and css files, this made no difference in the strufture of the website. HTML elements were built with default styles that allow them to work on their own. Divs are meant to section off the website so it is easier to give all the elements in the section a similar style. We will study this more extensively in the CSS unit. Fro this assignment, go back and determine which div elements are truly creating sections and remove the rest.

        2. Along with point one, all elements, including h1 and p tags, can have class names placed on them. In the CSS and SCSS unit you will learn how to use combinators, but placing a class name directly on an element other than a div is fine.

        3. In the index.html file, an anchro tag is in the footer to navigate to the index.html file. In all other files in the pages folder, this navigation works. However, in the index.html file you have placed two periods instead of one. This means the navigation is looking in the parent folder (past the root). If you have questions, feel free to re-read the navigation lesson or ask via slack.

        4. You try creating an underline with a bottom border. There are markup tags that allow you to underline and even css. Look at the mdn web docs and find tags that will allow you to underline elements.

        5. In the form page, all radio buttons can be selected. They needed to be grouped in a way that will ensure the others are not selected while one is selected. Radio buttons are best when only one option is allowed but an option must be provided.

        6. There is an input type for files that works all the logic for you. Instead of using a button automatically, it is best to first search if html has a built-in element or type that has all the logic built-in. Then you can customize the logic with javascript rather than creating it from scratch Once you have completed this feedback feel free to reach out.
