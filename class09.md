### Forms
##### Form: printed document that contains spaces for you to fill in information
##### Best known form is the search box that is used to google things
##### Form control: used to collect information from visitors
##### Adding text: text input, password input, & text area
##### Making choices: radio buttons, checkboxes, & drop-down boxes
##### Submitting forms: submit buttons & image buttons
##### Uploading files: file upload
##### How forms work: a user fills ina form and then presses a button to submit information to the srever, the name of each form control is sent to the server with the value the user enters or selects, the server processes the information using a prograaming language, and then the server creates a new page to send back to the browser based on the information recieved
##### A form may have several form controls, each gathering different information, and the server needs to know which piece of input data corresponds with which form element
##### HTML5 forms
##### form validation
##### date input
##### email & URL input
#####  search input
##### HTML & CSS Ch 14 "Lists, Tables, & Forms" (pp 330-357)
### Lists
##### Bullet point styles: list-style-type
##### Images for bullets: list-style-image
##### Positioning the marker: list-style-position
##### List Shorthand: list-style
##### Tables
##### Table properties: width, padding, text-transform, letter-spacing, font-size, border-top,border-bottom, text-align, background-color, :hover
##### Tips for styling tables:
##### give cells padding
##### distinguish headings
##### shade alternative rows
##### align numerials
##### online extra
##### Border on empty cells: empty-cells
##### Gaps between cells: border-spacing, border-collapse
##### Forms
##### Styling forms: text inputs and text areas, submit buttons, and labels on forms
##### Styling text inputs: font-size, color, background-color, border, border-radius, :focus,:hover, background-image
##### Styling submit buttons: color, text-shadow, border-bottom, background-color, :hover
##### Styling fieldsets and legends: width, color, background-color, border, border:radius, padding
##### Cursor styles: cursor element with these values for this property
##### auto, crosshair, default, pointer, move, text, wait, help, and url("cursor.gif");
##### Web Developer Toolbar
##### Helpful extention that provides tools to show you the CSS styles that apply to an element when you hover over it, along with the structure of the HTML
##### JS Ch 6 "Events" (pp 243-292)
##### Events
##### Interactions create events
##### Events trigger code
##### Code responds to users
##### Different Event Types
##### UI Events
##### Keyboard Events
##### Mouse Events
##### Focus Events
##### Form Events
##### Mutation Events
##### Terminology to know:
##### Events are fired or raised, which means they have occured
##### Events are said to trigger a function or script
##### How Events Trigger JS Code
##### When users interact with HTML, there are 3 steps involved in getting it to trigger JS code
##### Select the element node(s) you want the script to respond to
##### Indicate which event on the selected node(s) will trigger the response
##### State the code you want to run when the event occurs
##### 3 ways to bind an event to an element:
##### HTML event handlers (DO NOT USE)
##### traditional DOM event handlers
##### DOM level 2 event listeners
##### Using parameters with event handlers & listeners: becuase you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a work around
##### Event Flow
##### Event flow: HTML elements nest inside other elements, If you hover or click on a link, you  will also be hovering or clicking on its parent elements.
##### Event bubbling: the event starts at the most specific nodes and flows outwards towards the least specific one
##### Event capturing: the event starts at the least specific node and flows inwards to the most specific one
#####  the flow of events only really matters when your code has event handlers on an element and  one of its ancestors or descendant elelments
##### Event Object
##### when a event occurs, the event object tells you information about the event, and the element  it happened upon.
##### Event Delegation
##### creates event listeners for a lot of elements can slow down a page, but event flows allows you to listen for an event on a parent element
##### benefits: works with new elements, solves limitations with this keyword, and simpilfies code
##### Changing Event Behavior
##### the event object has methods that change: the default behavior of an element and how the element's ancestors respond to the event
##### Which element did an event ocuur on?
##### When calling a fuction, the event object's target property is the best way to determine which element the event ocuured on
##### Different Types of Events
##### W3C DOM Events
##### HTML5 Events
##### BOM Events
##### User Interface Events
##### Focus & Blur Events
##### Mouse Events
##### Keyboard Events
##### Form Events
##### Mutation Events
##### Where Events Occur
##### The event object can tell you where the cursor was positioned when an event was triggered
##### screen
##### page
##### client