# CSS exercise 38: Keyframe animations

You've asked for looping and infinite animations… that's what Keyframe Animations are for!

No need for a higher-specificity selector to drive them too, you can set animations on the base styles of any element.

Let's do some research:

1. Keyframe Animation setup needs some unique code, what does it start with?
1. What makes the keyframes code different to the rest of CSS?
1. How do we use a keyframe animation we set up earlier as a property in a ruleset for an element?
1. Keyframe animations have other keywords that aren't available in `transitions`, what are these keywords?
1. How many properties can we animate at once?
1. What properties are animatable?

1- It starts with @keyframes and the name of the animation which you want to change.

2- The thing which makes animation diferent is that media keyry always expects () whereas Keyframe doesn't. And you can name the element in your own.

3- We defined the name of the animation and then call it in our selectors.Must set duration and name property.

4- These other keywords that aren't available in `transitions` : infinite, reverse, alternate, play state.

5- We can animate as much as you want as long as the element is animatable.

6- The animatable properties are:

-moz-outline-radius
-moz-outline-radius-bottomleft
-moz-outline-radius-bottomright
-moz-outline-radius-topleft
-moz-outline-radius-topright
-webkit-line-clamp
-webkit-text-fill-color
-webkit-text-stroke
-webkit-text-stroke-color
all
backdrop-filter
background
background-color
background-position
background-size
block-size
border
border-block-end
border-block-end-color
border-block-end-width
border-block-start
border-block-start-color
border-block-start-width
border-bottom
border-bottom-color
border-bottom-left-radius
border-bottom-right-radius
border-bottom-width
border-color
border-end-end-radius
border-end-start-radius
border-image-outset
border-image-slice
border-image-width
border-inline-end
border-inline-end-color
border-inline-end-width
border-inline-start
border-inline-start-color
border-inline-start-width
border-left
border-left-color
border-left-width
border-radius
border-right
border-right-color
border-right-width
border-start-end-radius
border-start-start-radius
border-top
border-top-color
border-top-left-radius
border-top-right-radius
border-top-width
border-width
bottom
box-shadow
caret-color
clip
clip-path
color
column-count
column-gap
column-rule
column-rule-color
column-rule-width
column-width
columns
filter
flex
flex-basis
flex-grow
flex-shrink
font
font-size
font-size-adjust
font-stretch
font-variation-settings
font-weight
gap
grid-column-gap
grid-gap
grid-row-gap
grid-template-columns
grid-template-rows
height
inline-size
inset
inset-block
inset-block-end
inset-block-start
inset-inline
inset-inline-end
inset-inline-start
left
letter-spacing
line-clamp
line-height
margin
margin-block-end
margin-block-start
margin-bottom
margin-inline-end
margin-inline-start
margin-left
margin-right
margin-top
mask
mask-border
mask-position
mask-size
max-block-size
max-height
max-inline-size
max-lines
max-width
min-block-size
min-height
min-inline-size
min-width
object-position
offset
offset-anchor
offset-distance
offset-path
offset-position
offset-rotate
opacity
order
outline
outline-color
outline-offset
outline-width
padding
padding-block-end
padding-block-start
padding-bottom
padding-inline-end
padding-inline-start
padding-left
padding-right
padding-top
perspective
perspective-origin
right
rotate
row-gap
scale
scroll-margin
scroll-margin-block
scroll-margin-block-end
scroll-margin-block-start
scroll-margin-bottom
scroll-margin-inline
scroll-margin-inline-end
scroll-margin-inline-start
scroll-margin-left
scroll-margin-right
scroll-margin-top
scroll-padding
scroll-padding-block
scroll-padding-block-end
scroll-padding-block-start
scroll-padding-bottom
scroll-padding-inline
scroll-padding-inline-end
scroll-padding-inline-start
scroll-padding-left
scroll-padding-right
scroll-padding-top
scroll-snap-coordinate
scroll-snap-destination
scrollbar-color
shape-image-threshold
shape-margin
shape-outside
tab-size
text-decoration
text-decoration-color
text-decoration-thickness
text-emphasis
text-emphasis-color
text-indent
text-shadow
text-underline-offset
top
transform
transform-origin
translate
vertical-align
visibility
width
word-spacing
z-index
zoom
