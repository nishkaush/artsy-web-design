# artsy-web-design
simple yet a bit artsy website

Main Challenges Faced and Lessons Learnt:

(1) Floating an element doesn't effect its children, they still maintain their own internal flow.

(2) If the parent element is floating left or right, it can still be given the property of "position:relative" just so that its children can have "position:absolute" and move freely on the page.

(3) Background image's dimensions will only be shown in accordance with the height of the element it has been applied to. If the div it has been applied to is only 100px high, then only the corresponding background image will show itself. This is if the image has been set up as background-size:cover.

(4) Absolutely positioned elements should be positioned in "% and ems" and not pixels. This makes the design more responsive.

(5) With vertical menus, use ul and li elements since using divs is quite complicated and not nearly as fluid especially when pseudo classes like hover are applied.

(6) "&copy" is a nice way to show the copyright symbol inside the html document.

(7) Although, I didnt do it in this project but if I needed to build an image slider for multiple changing backgrounds, I could design that in javascript or jquery. For making the next and previous arrows, I could make a div and cut out its corners using border-radius property and then put the text "&gt" or "&lt" inside.

(8) Always use the HTML tag - "button" and then style the button. Never use input element to design a button even though it gives you the option. It messes up all dimensions of the button.

(9) When you need to design the hover effect where elements get bigger when hovered on, always ensure that the container element is high or wide enough to accomodate the change in size of its children elements. This makes the effect look nicer since all other elements and containers stay in place and don't shift relative to each other.
