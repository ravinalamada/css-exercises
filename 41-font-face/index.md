# CSS exercise 41: Font-face

Webfonts are strongly tied to a site's design and its visual identity.

But before we can use them, there are a few things we need to know:

1. There are several types of font formats, e.g. `WOFF`, `TTF`, etc.? Name at least 2 other font file formats.
=> woff2, SVG, OTF, EOT.
2. Which of these font file formats is a good candidate to use in all browsers?
=> woff
3. The font-face syntax is also different to other @-blocks. What are the differences between a `@font-face` block and `@keyframes` / `@media` queries / `@supports` blocks, etc.

=>We don't need to set the name of thing which we want to manupilate anymor. We need source property. The thing that makes font-face unique is that it is a combination of all font property.

4. Some fonts come with licencing restrictions. What does this mean?

=> This means we can't use it for free.

5. A designer has assigned you a mockup to turn into HTML/CSS. You've tabled the list of fonts used in the document as follows:

font-family | font-weights | italic?
--- | --- | ---
'Roboto' | 400, 700 | Both
'Proxima Nova' | 100, 300, 600, 800 | No

How many font-face blocks do we need to provide if we want to support all the chosen fonts?
=> There are about 8 font-face blocks that we need to provide.

6. At roughly 20KB per font file, how many kilobytes of fonts would each of our users have to download in the example above?

=> If we have 8 files, it means that each of our users have to download roughly 160KB

7. If we chose to offer WOFF2 as well as WOFF, what syntax would we use? How many files would we have, according to question 5?

=>   We use url which are separated by comma, local() must be set first and then woff2 and then woff.

8. Most of our users would probably have the exact font we want to serve already installed on their devices. How can we make sure the user's browser doesn't download the fonts they might al

=> We use both `local()` or system and 'url' so that if they don't have font-fave that they want to set , the url provided then will be downloaded.

9. Sometimes we have to assign fallback fonts for our custom webfonts we add via `@font-face`. What are some things to keep in mind when it comes to selecting these fallback fonts?

=> It should be similar type of the font-face we want to apply.
=> We need to figure out the width and height before we choose the font-face.

10. The browser can use one of several strategies for loading the fonts, e.g. showing nothing until the font is downloaded, or using a fallback font first. What property can we use to help the browser decide on which strategy to use?

=>  It renders the falback font first
=>  Blank until downloaded
=>  font-display
