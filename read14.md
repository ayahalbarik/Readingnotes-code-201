
# Transforms

With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

2D Transforms
Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. **Two-dimensional** transforms work on the x and y axes, known as horizontal and vertical axes. **Three-dimensional** transforms work on both the x and y axes, as well as the z axis. 


##Transitions
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

##*Transitional Property*
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions

**but not all properties may be transitioned,**

## Transition Timing
The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.

The linear keyword value identifies a transition moving in a constant speed from one state to another. The ease-in value identifies a transition that starts slowly and speeds up throughout the transition, while the ease-out value identifies a transition that starts quickly and slows down throughout the transition. The ease-in-out value identifies a transition that starts slowly, speeds up in the middle, then slows down again before ending.

Each timing function has a cubic-bezier curve behind it, which can be specifically set using the cubic-bezier(x1, y1, x2, y2) value. Additional values include step-start, step-stop, and a uniquely identified steps(number_of_steps, direction) value.

When transitioning multiple properties, you can identify multiple timing functions. These timing function values, as with other transition property values, may be declared as comma separated values.