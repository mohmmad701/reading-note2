 ## CSS Transforms, Transitions, and Animations

 This post will introduce you to CSS transitions and CSS transforms: the CSS power couple. When used together, these properties allow you to create simple animations and add valuable interaction and visual feedback for your users.

Just remember when adding any kind of movement to your project to keep it simple, subtle, and consistent. The movement you create should convey meaning, always enhancing, not distracting from the interaction for your users.

So what are transforms and transitions? At their most basic level, transforms move or change the appearance of an element, while transitions make the element smoothly and gradually change from one state to another.

CSS transitions: an introduction
Let’s start with CSS transitions. Transitions are the grease in the wheel of CSS transforms. Without a transition, an element being transformed would change abruptly from one state to another. By applying a transition you can control the change, making it smooth and gradual.
<div class="wrap">
  <div class="container">
    <h1>Without transition</p>
    <div class="box1 box"></div>
  </div>
   <div class="container">
    <h1>With transition</p>
    <div class="box2 box"></div>
  </div>
</div>
In this post I’ll be using transitions in conjunction with transforms. However, transitions can also be used elsewhere where elements change from one style to another (e.g., when a button changes color on hover).

There are two properties that are required in order for the transition to take effect:

transition-property
transition-duration
Note: Transition Shorthand
Each transition property can be defined individually, but for cleaner and faster code, it’s recommended that you use the transition shorthand.

Here’s the full shorthand sequence. Again, the first two properties are required.


div {
  transition: [property] [duration] [timing-function] [delay];
}
transition-property (required)
The transition-property specifies the CSS property where the transition will be applied. You may apply a transition to an individual property (e.g., background-color or tranform) or to all properties in the rule-set (i.e., all).

CSS syntax examples for transition-property
div {
  transition-property: all;
  transition-property: transform;
}
transition-duration (required)
The transition-duration property specifies the time span of the transition. You can specify in seconds or milliseconds.

CSS syntax example for transition-duration
  div {
    transition-duration: 3s;
  }
Shorthand example for transition-duration
div {
  transition: all 3s;
}
transition-timing (optional)
The transition-timing-function property allows you to define the speed of the transition over the duration. The default timing is ease, which starts out slow, quickly speeds up, and then slows down at the end. The other timing options are: linear, ease, ease-in, ease-out, and ease-in-out.

Here’s an example of the different timing options (used with the transform: translate property):

.container {
  margin: 100px;
}

.circle {
  border-radius: 50%;
  height: 30px;
  width: 30px;
  margin: 10px;
  
  .container:hover & {
    transform: translateX(200px);
  }
}

.circle0 {
  @extend .circle;
  background: PaleTurquoise;
  transition: all 1.5s linear;
} 

.circle1 {
  @extend .circle;
  background: salmon;
  transition: all 1.5s ease;
}

.circle2 {
   @extend .circle;
  background: lightskyblue;
  transition: all 1.5s ease-in;
}

.circle3 {
  @extend .circle;
  background: khaki;
  transition: all 1.5s ease-out;
}

.circle4 {
  @extend .circle;
  background: mediumturquoise;
  transition: all 1.5s ease-in-out;
}

.circle5 {
  @extend .circle;
  background: thistle;
  transition: all 1.5s cubic-bezier(0,1,.98,0); 
}