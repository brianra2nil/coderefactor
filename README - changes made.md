https://brianra2nil.github.io/coderefactor/



GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements

*** 3 <div> elements changed to <nav> <aside> and <footer>

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

<nav> is on top and corresponds to the navigation bar up top and listed first, <aside> cooresponds to the sidebar that has lead generation, brand awareness and cost management
<footer> is at the bottom and last


WHEN I view the image elements
THEN I find accessible alt attributes

Added the attributes: alt="search engine optimization" following anything with an img src=.


WHEN I view the heading attributes
THEN they fall in sequential order

Moved the link element to the end of the <head> tag as opposed to where it was in the middle.

WHEN I view the title element
THEN I find a concise, descriptive title

changed from "website" to "Horiseon" which is the name of the company or website.