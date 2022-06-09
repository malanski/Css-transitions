# CSS course
  
In this project you will learn the most important topics to leverage in the world of animations using CSS.  
  
Among them the CSS Transitions using pseudo elements and pseudo classes and also CSS @keyframes.  
  
At the end of the project, we will have the construction of a portfolio using only HTML and CSS to fix the classes.

## Transitions

To create a transition effect, you must specify two things:

    the CSS property you want to add an effect to
    the duration of the effect

The transition effect will start when the specified CSS property (width) changes value.

Now, let us specify a new value for the width property when a user mouses over the <div> element:
  
Notice that when the cursor mouses out of the element, it will gradually change back to its original style.  
  
### Specify the Speed Curve of the Transition

The transition-timing-function property specifies the speed curve of the transition effect.

The transition-timing-function property can have the following values:

    ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
    linear - specifies a transition effect with the same speed from start to end
    ease-in - specifies a transition effect with a slow start
    ease-out - specifies a transition effect with a slow end
    ease-in-out - specifies a transition effect with a slow start and end
    cubic-bezier(n,n,n,n) - lets you define your own values in a cubic-bezier function
  
### Delay the Transition Effect

The transition-delay property specifies a delay (in seconds) for the transition effect.
  
### Transition + Transformation

The following example adds a transition effect to the transformation:

  
CSS Transition Properties

The following table lists all the CSS transition properties:
Property 	Description
  
    transition 	A shorthand property for setting the four transition properties into a single property
    transition-delay 	Specifies a delay (in seconds) for the transition effect
    transition-duration 	Specifies how many seconds or milliseconds a transition effect takes to complete
    transition-property 	Specifies the name of the CSS property the transition effect is for
    transition-timing-function 	Specifies the speed curve of the transition effect  
