# bootstrap-Adhoc
1.Before we touch the code, look over Adhoc’s design spec provided in the introduction. Notice that the design spec includes information about what Bootstrap utility classes components are used.

And keep in mind that the website is designed to be responsive so that it accommodates desktop and mobile screens. Therefore, as you work through the project, resize your browser to see both the desktop and mobile versions!

Also, check out the links provided for the images used on the website.

Lastly, look over the provided code in index.html. You’ll see some starter code that you’ll have to edit in order to have a functioning site.
Editing the Navbar
2.
Let’s first tackle the navbar.

It’s a good starter template but we still have to edit this code to fit our needs. Therefore, remove the code that renders these elements:

the dropdown option.
the disabled link.
the search bar.
3.
Add Adhoc’s logo to the navbar.

Locate the element with class "navbar-brand". Delete the text Navbar and replace it with an <img> element with an src value of "https://content.codecademy.com/courses/learn-bootstrap-4/adhoc/logo.png".

Remember to assign an appropriate value to the alt attribute.


4. 
According to the design spec, we should have 4 links (not including the brand) in the navbar.

Use the second link as a template and make 2 additional links. Change the text of the links to follow the design spec.

5. the navbar, there’s a <div> that we’re going to turn into our jumbotron!

It currently has some inline CSS that renders a background image.

Provide it with a class of "jumbotron" and "jumbotron-fluid" to get a jumbotron that spans the entire screen/viewport.



6.
Inside the jumbotron, add another <div>. This new <div> is going to act as a background and container for the text we want to insert. Therefore, inside the <div> add an <h1> element followed by a <p>.

Use the design spec and add the appropriate text inside both the <h1> and the <p> elements.


Stuck? Get a hint
7.
Time to style the elements we just added. We want the new <div> to have:

a grey background.
white and centered text.
larger top and bottom margins by assigning a class of "my-5". This utility class targets and increases the vertical margins of an element.
Also, give the <h1> element a display heading by assigning a class of "display-3".



8.
Let’s style the quote under the jumbotron using utility classes.

Follow the design spec. Provide the <h2> element with

italic font.
a light font-weight.
Notice the stying of the name, it:

is aligned to the right
has a bold and italic font
the text inside the <span> has a normal weight.
Finish up the quote styling by increasing the top and bottom margins of the column containing the quote. You can do so by assigning a class of my-5.



Why Adhoc? - Cards
9.
Locate the <h2> element with text Why Adhoc?.

Center the text and give it a display heading that follows the design spec.



10.
In the next row, we’re going to continue following the design spec and add one card in each column.

In each column, add a card that:

Does not have a border.
Has an image icon on the top.
Has centered text on the bottom.
Here are the linked icons for convenience:

experienced icon.
fun icon.
smart icon.


11.
While the columns look good on a large screen, the contents look squished on a smaller screen. Change the width of the column so that it has a width of 4 on medium, and larger, sized screens.

For extra small and small-sized screens, it should have a width of 8.


Stuck? Get a hint
12.
Let’s also have the row center the columns containing the cards.


Stuck? Get a hint
13.
Increase the vertical margins of the row with the text Why Adhoc and the row containing the cards to space out the rows.

Meet the Team - Carousel
14.
Locate the row with the text Meet the Team. According to the design spec, provide that row with utility classes that render a dark background with rounded top border.


Stuck? Get a hint
15.
Now let’s style <h2> element that has the text Meet the Team.

Apply the following styling for the <h2> element:

Make the text white.
Center the text.
Make it a Bootstrap display header.


16.
Time to style the row below the text Meet the Team.

Give the bottom row a dark background and a rounded bottom border.



17.
Take a look at the code that renders a carousel. It was copied directly from Bootstrap’s carousel with controls example.

Like with the navbar, we’re going to modify the code to fit our needs. For each <div> with a class of "carousel-item", assign the nested <img>‘s src a URL to the provided pictures in the intro’s image assets. Also, provide an appropriate value for the alt attribute.

Here are the linked images for convenience:

picture of Brian M. the CEO.
picture of Andy C. the CFO.
picture of Angela W. the COO.
picture of Amie S. the CTO.


18.
With the slides set up, we can add some captions to each slide.

Style the captions so that it has a black background, no vertical padding, and a rounded-pill border.

Inside the captions, add the appropriate text and style it according to the design spec.



19.
Change the sizing of the carousel to only take up 50% of the width and set the margin to automatically center its contents.

Then go back and adjust the spacing of the rows to follow the design spec.



Finishing up
20.
The last element we have to style is the <footer>, center the text.

Some useful links:
To set the width of an element, use Bootstrap’s sizing utility classes.

To set the margin to center an element’s contents, check out Bootstrap’s horizontal centering example.

To change the spacing of the rows, edit the row’s padding using Bootstrap’s spacing utility classes.
 provide a dark background, use Bootstrap’s background color utility class.

To apply a rounded bottom border, use Bootstrap’s border-radius utility class.

