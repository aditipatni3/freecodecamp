The loading attribute on an img element can be set to lazy to tell the browser not to fetch the image resource until it is needed (as in, when the user scrolls the image into view). As an additional benefit, lazy loaded elements will not load until the non-lazy elements are loaded - this means users with slow internet connections can view the content of your page without having to wait for the images to load.


font-size property set to 62.5%. This will set the default font size for your web page to 10px (the browser default is 16px).This will make it easier for you to work with rem units later, as 2rem would be 20px.


the content to have a three-column layout by adding a grid-template-columns property with a value of 1fr 94rem 1fr. This will create three columns where the middle column is 94rem wide, and the first and last columns are both 1 fraction of the remaining space in the grid container.