# Transforms:
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings
1. two-dimensional 
2. three-dimensional
 Each of these come with their own individual properties and values

## Transform Syntax
the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
 `-webkit-transform: scale(1.5)`

    ` -moz-transform: scale()`

       `-o-transform: scale() `

       `transform: scale() `
## 2D Transforms :two-dimensional 
* work on the x and y axes, known as horizontal and vertical axes
* Three-dimensional transforms work on both the x and y axes, as well as the z axis


### 2D Rotat 
The rotate value provides the ability to rotate an element from 0 to 360 degrees.

### 2D Scale

Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

### 2D Translate

The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.

### 2D Skew

### Combining Transforms

It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.

### Transform Origin

As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically
The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.

### Perspective Depth Value

The perspective value can be set as none or a length measurement. The none value turns off any perspective, while the length value will set the depth of the perspective

## 3D Transforms : Three-dimensional
Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

### 3D Rotate

 we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ.

### 3D Scale

By using the scaleZ three-dimensional transform elements may be scaled on the z axis
### 3D Translate

Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element. 

### 3D Skew

Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale

# Transitions & Animations
With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. 

**Transitions**
 The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

**Transitional Property**

The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.


**not all properties may be transitioned**

* On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property


## Animations

To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

Once you have declared the animation-name property on an element, animations behave similarly to transitions. They include a duration, timing function, and delay if desired

# simple effects that will add life to your UI

* Fade in

Fade in effects are coded in two steps: first, you set the initial state; next, you set the change

* Change color

* Grow & Shrink
To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.

* Rotate elements

* Square to circle

* 3D shadow
 
* Swing

* Inset border

 Inset border
One of the hottest button styles right now is the ghost button; a button with no background and a heavy border. We can of course add a border to an element simply, but that will change the element’s position. We could fix that problem using box sizing, but a far simpler solution is the transition in a border using an inset box shadow.
































