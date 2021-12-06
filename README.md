# landing-page <img src="./images/eggplant.svg" alt="Eggplant" width="150px" height="150px">

### Description
A simple webpage designed to put into practice the numerous flexible box layout properties CSS has to offer us. Through this exercise I was able to apply the knowledge I have been gathering over the past few days on amazing sources such as **MDN** and **The Odin Project**. 

The following aims to be a detailed self reflection of my thought process when designing this webpage. I understand it may get very monotonous and dull for someone who is familiar with flexbox, but do understand this was written with the intent of internalizing knowledge, as well as laying out my thought processes for later review.

The website is divided in multiple sections:

##### Navbar
The navbar was made by setting the value of flex-direction property to row, removing the style of my unordered list and the extra padding and margin that comes with it by design.

As I had done so before on a previous project, pummaroro, I imported a font from google fonts to add some extra flavour to it all.

The list was then made into a flex container itself, and its content was justified using the value of space-around for the property justify-content, which distributes the space evenly on either side of the flex-items within it.

The list elements were initially too crammed, so I made sure to use the new gap feature to increase the space between them. 

##### Hero
The hero section was trickier than expected. Knowing that I had to use an image, I immediately set out to find one that would best fit a responsive website, so an .svg image. 

I created two containers, one for text and the other to store the image in, then centered them both vertically and horizontally using the align-items and justify-content properties respectively. Flex direction was once again the default, row. 

I encountered some difficulties in effectively centering the image: while it indeed was right at the center, it wouldn't grow to fill the container and would default at a very small size. For that reason I set the width of the image flex container to be 20% of the whole parent flex container, only to allow the image to fill 70% of the available container space.

This solution worked and I am satisfied with the way it looks, though I imagine having an image with a width greater than the height would have helped the overall look of it all.

The text portion arrangement was quite smoother: heading, paragraph and button are all elements who have an innate value of block on the property display, so they automatically broke into a new line and needed no more work than what was required for styling.

##### Information
The information section is very common on modern websites, and flexbox provides us with all the tools needed to accomplish this design with ease.

##### Quote and Call To Arms

#### Footer


Eggplant SVG taken from here: https://www.svgrepo.com/svg/312094/eggplant
