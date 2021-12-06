<img src="./images/eggplant.svg" alt="Eggplant" width="150px" height="150px">

# Landing Page

### Description
A simple webpage themed after eggplants and designed to put into practice the numerous flexible box layout properties CSS has to offer us. Through this exercise I was able to apply the knowledge I have been gathering over the past few days on amazing sources such as **MDN** and **The Odin Project**. 

The following aims to be a detailed self reflection of my thought process when designing this webpage. I understand it may get very monotonous and dull for someone who is familiar with flexbox, but do understand this was written with the intent of internalizing knowledge, as well as laying out my strategy for later review.

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

This section contained an header illustrating the purpose of the section and, under it, the information cards themlseves. 

H1 being a block type element, allowed me to avoid arranging my two elements inside a container. I added some extra margin on the bottom to create more space and allow for the two sections to breathe a little better. 

Each information portion is made of two elements: an image (supposedly, I used colored divs) and some piece of text (paragraph). My solution was to create a container div for each of these information 'cards' to be laid out in a flexbox container with a flex-direction of value row. 

I initially considered making each individual card into a container too, laying them out with a flex-direction of column so that image and text stacked on top of each other. This approach worked, but it was inefficient and required more redundant code.

I instead opted to insert a max-width for each information card and made sure to center both image and paragraph through property text-align and margin (with autos).

##### Quote and Call To Arms
I grouped these two together because the approach was extremely similar. I needed a container to be at the center of the screen, and that was achieved by using a flex container and centering on the main and cross axis using the properties justify-content and align-items.

For the Quote section, I had to put a quote and under it, aligned to the right, the name of author of said quote. For the Call To arms Section, I had to instead place a header and a paragraph next to a button that enticed them to sign up.

In regards to the Quote section, I initially set out to arrange one of the items inside of the flex container (the name of the author). This was accomplished by making it too into a flex container, specifying a justify-content property value of flex-end to ensure it would sit at the end of the main axis, as required by the original design. I noticed I was overdoing it and just settled on using the rule declaration text-align: right, cutting on some redundant code. 

As for the Call To Arms section, it sufficed to arrange the box with a flex-direction of row, one flex-item containing header and paragraph, the other containing the button.

Since the first flex item stretched to overpower the button, I made sure to specify a width of 70% on it to eliminate the problem. I thought setting a property of align-self on the button would be necessary, but some testing made me discover centering the flex items on the cross axis (with align-items) was enough to get everything into place.


#### Footer
The footer was quickly dealt with by making it into a flex container and centering the only item using justify-content and align-items. 

I gave a little flavour to the link to my GitHub profile by using the pseudostate :hover.

#### Conclusion
Having such a detailed writeup was immensely helpful, as it allowed me to see the various inefficiencies in my code as I went through it and tried to explain what I was doing.

I hope I will be able to do one of these for each one of my projects. 

If you got this far, thank you for reading.
If you are only reading this line, I don't blame you. Cheers.

#### Credits

Eggplant SVG taken from SVGREPO: https://www.svgrepo.com/svg/312094/eggplant
