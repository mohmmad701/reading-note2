### CSS "Layout"
![layout](https://getflywheel.com/layout/wp-content/uploads/2018/02/Feature_Image_Animated_1800x500_forever-1-1280x356.gif)
##### Key concepts in Positioning Elements:
##### Building Blocks: css treats each HTML element as if its in its own box, and this box will either be block-level box or inline box.
##### Block-level elements: h1, p, ul, li
##### Inline elements: img, b, i
##### Containing Elements: if one block-level element sits inside another block-level element, then the outer box is the contianing/ parent element.
##### Controlling the Position of Elements
##### Positioning Schemes: allow you to control the layout of a page
##### Normal Flow: every block-level element appears on a new line, causing each item to appear lower down the page than the previous one
##### position:static
##### Relative Positioning: this moves an elelment from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.
##### position:relative
##### Absolute Positioning: the positions the element in relation to its containing element
##### position:absolute
##### Fixed Positioning: this is a form of absolute positioning that positions the element in relation to the browser window
##### position:fixed
##### Floating Elements: floating an elelment allows you to take that element out of the normal flow and position it to the far left or far right of a cointained box
##### float
##### Box offset property tells the browser how far from the top or bottom and left or right the box should be placed.
##### z-index property allows control over which box appears on top
##### Using float to place elements side-by-side: a lot of layouts place boxes next to each other. The float property is used to achieve this. When elements are floated, the height of the boxes can affect where the following elelments sit
##### Clearing floats: the clear property allows you to say that no element should touch the left or right-hand sides of a box. It can take the following values:
##### left
##### right
##### both
##### none
##### Parents of floated elements: problem - if contianing element only contains floated elements, some browsers will treat it as is its zero pixels tall
##### Parents of floated elements: solution - the pure CSS solution adds two CSS rules to contain the element:
##### the overflow property is given a value auto
##### the width property is set to 100%
##### Creating multi-column layout with floats: is achieved using div element to represent each column, and these three properties are used to position the columns next to each other:
##### width
##### float
##### margin Screen Sizes & Screen Resolutions
##### Screen size - your design needs to be able to work on a large range of different screen sizes
##### Screen resolutions - resolution refers to the number of dots a screen shows per inch
##### Page Sizes
##### Due to screen sizes and screen resolutions varying so much, designers often try to create pages around 960-1000 pixels wide.
##### Fixed Width Layouts
##### These designs don't change size as the user increases or decreases size of their browser window. Measurements are in pixels.
##### Advantages:
##### pixel sizes are accurate at controlling size and positioning of elements
##### there is greater controlover the position and appearance of items
##### can control lenghts of lines of text
##### size of image will always remain the same
##### Disadvantages:
##### can end up with wide gaps
##### the text can look smaller and harder to read on a high resolution screen
##### text might not fit onto the page
##### text might not fit into alloted spaces
##### page will take up more verticle space
##### Liquid Layouts
##### These designs stretch and contract as user increases or decreases the size of their browser window, and use percentages.
##### Advantages
##### Pages expand to fill the entire browser window
##### pages can contract to fit smaller screen
##### design is tolerant ofuser setting font size larger
##### Disadvantages
##### unexpected gaps can appear around certain elements or squash them
##### lines of text can appearvery long and hard to read
##### word might be squished with only a few words on each line
##### the image can flow over the text
##### A fixed width layout: to ceate it, the width of the main boxes on a page will usually be specified in pixels
##### A liquid layout: uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen Layout Grids
##### Designers use a grid structureto help position and organize items on a page.
##### Possible layouts: 960 pixels wide and a 12 column grid
##### creates a continuity between different pages which may use different design
##### helps users predict where to find information on various pages
##### makes it easier to add new content to site
##### helps people to collaborate on the design of a site consistantly
##### CSS Frameworks
##### CSS frameworks aim is to make life easier by providing code for common tasks, such as  creating layout grids, styling forms, creating printer friendly version of pages, etc.
##### Advantages - save you from repeatedly writing code for the same tasks, and are well tested
##### Disadvantages - require you to use class names in the HTML code that only controls  presentation of the page, and to satify a variety of needs CSS frameworks often contains more code than you need for a web page

