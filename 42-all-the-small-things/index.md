# CSS exercise 42: All the small things

We haven't covered a number of topics that are really good to know, but each one of them probably didn't deserve their own exercise.

So, let's go through as many of the more important but small properties here as we can:

- `cursor` =>SYNTAX: It contains zero or more url which are separated by commas and must be followed by keyword value so that if neither of the url are loaded, the browser then takes the keyword. We can also set numbers that separated by space in order to represent (x,y) of the image.

=> It is used to specify the type of cursor that should be displayed to the user much better to use when you have image in submit buttom in form.

- `pointer-events`=> if a developper set pointer-events with value none, the user then can't click anything. It is useful for hightline the content that is in focused.

- `outline`=> It outlines the content of the element as border does, but it oversteps its boundary.
=> Syntax: outline-color, outline-style, outline-width.

- `filter`=>It is used to control a color of the content.

- `appearance` => The -moz-appearance CSS property is used in Gecko (Firefox),
               => The -webkit-appearance property is used by WebKit-based (e.g., Safari) and Blink-based (e.g., Chrome, Opera) browsers to achieve the same thing. Note that Firefox and Edge also support -webkit-appearance, for compatibility reasons.
               => It is used : To apply platform specific styling to an element that doesn’t have it by default
                               To remove platform specific styling to an element that does have it by default.
               => Webkit and mozila have different values.

- `object-fit`=> is used to define how the replaced contents fit in its container. It has value (fill, cover, contain, scale-down, none), indeed image and video. It is useful when you want change the look of an informational image into decorational.

- `scroll-snap-align` => It contains value (start, end, none, center)

There are many more! See [the official list of all CSS properties](https://www.w3.org/Style/CSS/all-properties.en.html)

Similarly, there are a few pseudo-class selectors we should talk about:

- `:focus` => It is triggered when you click the element which is focused but it only applies to that element itself.
- `:focus-within` => It will apply to all of the elements which are part of the focused element. his is good to set in form container.

- `:visited`=> Allowable CSS properties are color, background-color, border-color, border-bottom-color, border-left-color, border-right-color, border-top-color, column-rule-color, outline-color, text-decoration-color, and text-emphasis-color.Allowable SVG attributes are fill and stroke. To way how we set it is LVHA (link, visited, hover, active)

- `:active` => We write it LHVA. It is commonly used with <a> and <buttom>

- `:target`=> You can use the :target pseudo-class to create a lightbox without using any JavaScript. This technique relies on the ability of anchor links to point to elements that are initially hidden on the page. Once targeted, the CSS changes their display so that they are shown.

- `:disabled`=> why should you use this property?
- `:empty`=> To style an empty element.
- `:not()`=> It represent the element that doesn't match a list of a selector.

- `:matches()`=> It represent the element that does match a list of a selector.

And a pseudo-element:

- `::first-letter` => used to style the first letter in a paragraph.

Then, there's the mysterious block:

- `@supports`=> There two type of @support which are basic one and function. Within the basic support is declared (a property name followed by a value, separated by a colon inside a ()).
The support ()is declared like this (@supports selector(A > B) {}) which returns true if the child combinators are supported. We also can use these oparators (not, and, or)
NOT returns true if the browsers don't support the values.
AND requires both coditions to be true
OR requires at least one is true.

And lastly, an interesting pseudo-element value function that has a promising future:

- `attr()`=> Syntax
[attr]
Represents elements with an attribute name of attr.
[attr=value]
Represents elements with an attribute name of attr whose value is exactly value.
[attr~=value]
Represents elements with an attribute name of attr whose value is a whitespace-separated list of words, one of which is exactly value.
[attr|=value]
Represents elements with an attribute name of attr whose value can be exactly value or can begin with value immediately followed by a hyphen, - (U+002D). It is often used for language subcode matches.
[attr^=value]
Represents elements with an attribute name of attr whose value is prefixed (preceded) by value.
[attr$=value]
Represents elements with an attribute name of attr whose value is suffixed (followed) by value.
[attr*=value]
Represents elements with an attribute name of attr whose value contains at least one occurrence of value within the string.
[attr operator value i]
Adding an i (or I) before the closing bracket causes the value to be compared case-insensitively (for characters within the ASCII range).
[attr operator value s]
Adding an s (or S) before the closing bracket causes the value to be compared case-sensitively (for characters within the ASCII range).


