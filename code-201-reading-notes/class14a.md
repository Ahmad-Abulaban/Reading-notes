# Transitions & Animations: 

**As mentioned, for a Transitions to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the `:hover`, `:focus`, `:active`, and `:target` pseudo-classes.**

**There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.**
**In the example below the box will change its background color over the course of 1 second in a linear fashion.**

`.box {`
>  `background: #2db34a;`

>  `transition-property: background;`

>  `transition-duration: 1s;`

>  `transition-timing-function: linear;`

`}`

`.box:hover {`
>  `background: #ff7b29;`

`}`

***

## Transitional Property

**The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.**

* background-color
* background-position
* border-color
* border-width
* border-spacing
* bottom
* clip
* color
* crop
* font-size
* font-weight
* height
* left
* letter-spacing
* line-height
* margin
* max-height
* max-width
* min-height

***

## Transition Duration

**The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.
When transitioning multiple properties you can set multiple durations, one for each property. As with the transition-property property value, multiple durations can be declared using comma separated values. The order of these values when identifying individual properties and durations does matter. For example, the first property identified within the transition-property property will match up with the first time identified within the transition-duration property, and so forth.
If multiple properties are being transitioned with only one duration value declared, that one value will be the duration of all the transitioned properties.**

## Animation Name

**Once the keyframes for an animation have been declared they need to be assigned to an element. To do so, the animation-name property is used with the animation name, identified from the @keyframes rule, as the property value. The animation-name declaration is applied to the element in which the animation is to be applied to.**

***

* 2D Transforms

**Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.**

* 2D Rotate

**The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from `0` to `360` degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, `50%` `50%`, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.**

* 2D Scale

**Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between `.99` and `.01` makes an element appear smaller while any value greater than or equal to `1.01` makes an element appear larger.**

***

