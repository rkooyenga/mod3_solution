# [Responsive Restaurant Layout](https://rkooyenga.github.io/mod3_solution/)

My submission for the Module 3 challenge in the Johns Hopkins University, Web Programming course. 
## Assignment Specs  

Responsive design with layouts for large, medium, and small screens according to assignment spec and the folllowing restrictions:  
- no inline styles, assignment required a styles file
- assignment requires leveraging bootstrap as much as possible
- Use of semantic, accessible HTML.  
- Consistent color scheme and readable typography.  

1. Follows the Development Setup Video (beginning of Module 1) instructions on how to create a repository and set it up such that you can host and view your finished web pages on GitHub Pages, i.e., GitHub.io domain name. You will need to provide that URL for your peer review.

2. Create a folder in your repository that will serve as a container folder for your solution to this assignment. You can call it whatever you want. For example, `module3-solution` or `mod3_solution`, etc. Create an `index.html` file inside the solution container folder, e.g., `module3-solution/index.html`.

3. The implementation of the page you will be creating should follow the mockup illustrations shown below. You are provided 3 mockups: desktop and tablet (same), mobile, and mobile with mobile menu dropdown shown. Your implementation has to be JUST 1 page. In other words, you will be creating a single, responsive page.

4. Your page must include a CSS file. No inline styles allowed. Your CSS file should be placed into a `css` folder under the solution container folder, e.g., `module3-solution/css`.

5. For this assignment, you are to use Twitter Bootstrap CSS Framework as much as possible. I suggest you start with copying the starter bootstrap files and folders we discussed in Lecture 25 part 6. If you've cloned/downloaded the code example repository, it should be in the `examples/Lecture25` folder. Copy the contents of `examples/Lecture25` to your solution container folder (e.g., `module3-solution`) as a starting point..

7. Since we are using Bootstrap for this assignment, instead of specifying pixel ranges, I will define our desktop, tablet, and mobile views in terms of Bootstrap CSS class prefixes, i.e., `md`, `sm`, and `xs`.
  * Desktop mockup illustration should correspond to Bootstrap `md`-based classes
  * Tablet mockup illustration should correspond to Bootstrap `sm`-based classes
  * Mobile mockup illustration should correspond to Bootstrap `xs`-based classes

8. Navbar: Create a navbar that scrolls away together with the page (the navbar should become invisible and is not fixed to the top when you scroll the page down). The navbar should have a company name (i.e., `navbar-brand` class) called "Food, LLC" that is aligned to the left side of the navbar. (*See* [https://getbootstrap.com/docs/3.3/components/#navbar](https://getbootstrap.com/docs/3.3/components/#navbar). *Make the browser window narrower to see the mobile menu button appear in the first example shown at the provided link.*)
<br><br>
For desktop and tablet view, the navbar should not contain anything else. No other buttons should be visible. (_Hint: use 'visible-xs' class._)

9. Navbar - Mobile View: Create a simple menu button (3 horizontal bars). When the user clicks that button, a dropdown menu should appear (as illustrated in Mobile Open Menu illustration below.) The dropdown menu should contain 3 items: Chicken, Beef, and Sushi.
<br><br>
The dropdown menu should take up the entire width of the browser window. Make sure the dropdown menu has a background color set that distinguishes it from the rest of the content.
<br><br>
(_Hint: See_ [_https://getbootstrap.com/docs/3.3/components/#navbar_](https://getbootstrap.com/docs/3.3/components/#navbar) _and Lecture 31 for examples on how to accomplish this._)

10.  Page Heading. The page heading that says Our Menu should be centered within the browser window. You must use a Bootstrap class to accomplish this.
<br><br>
(_Hint: look for a Bootstrap class that centers text, see_ [_https://getbootstrap.com/docs/3.3/css/#type-alignment_](https://getbootstrap.com/docs/3.3/css/#type-alignment)_._)

11.  Create a single really tall section that will use the Bootstrap Grid and take up the entire width of the browser window (minus some margins, of course) for all views: desktop, tablet, and mobile. To make the section really tall, you can either fill it out with a LOT of text or simply set its height to something like 1000px. It needs to be tall enough to cause scrolling down to be required to view the bottom of the section. Make sure its background color is set to distinguish it from the rest of the content. (_Hint: don't forget to have an element with a class='container' or class='container-fluid' wrapping your grid. Remember that to have the grid do something "always", i.e., no matter what browser window size, use the `col-xs-`... classes. In this case, since we want the section to take up the entire row, use `col-xs-12`._)


Both the tablet view and the desktop view of what's graded and required is the same. Here is the mockup illustration of the desktop & tablet version of the site (only required graded parts shown):

 ![Desktop and Tablet](images/desktop.png)


Here is the mockup illustration of the mobile view (only required graded parts are shown):

 ![mobile collapsed](images/menu-collapsed.png)

 ![mobile expanded](images/mobile-expanded.png)


**&#42;&#42;&#42; REQUIRED GRADED ASSIGNMENT ENDS HERE &#42;&#42;&#42;**  
<br>
<br>
<br>


<!--
## Extras

- Self-hosted WOFF2 fonts compressed from True Type Files using [ttf-to-woff2](https://rkooyenga.github.io/ttf-to-woff2/)
- A logo and dummy company branding aligned demonstrating Flexbox.  
- 3D animations and shadows for a polished look.

-->

## Peer Review Stage: 


- Does the implementation use inline CSS styles at all (not allowed) or does it reference an external CSS file?

- Is the default navbar implemented such that it scrolls away with the page, i.e., it's not statically attached to the top of bottom of the screen?

- Does the brand name "Food, LLC" properly aligned to the left of the navbar and does it use navbar-brand class?

- Is the dropdown menu button only visible when the browser is narrow enough to be in mobile view?

- Does clicking the dropdown menu button make the dropdown menu to slide down? Does it take up the entire width of the browser (minus some margins)? Is the label of the each menu item (e.g., "Chicken")  centered using a Bootstrap class?

- Is the page heading, "Our Menu", centered on the screen using the Bootstrap class?

- Is the single cell section (or multiple sections as per optional part of the assignment) using the Bootstrap Grid System and is the section tall enough to force the viewer to scroll if they wanted to get to the bottom of the page.


-by [Ray Kooyenga](@rkooyenga)

