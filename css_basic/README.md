Tasks
Some early styling

Copy into this folder index.html and tweets.html that you created in the previous project:Create an empty styles.css.Create the file base.css and set the content of this file In each of your HTML files, add these 2 lines within the <head> tag (do not confuse with the <header> tag!):

<link href="base.css" rel="stylesheet">
<link href="styles.css" rel="stylesheet">
If you refresh your webpages in your browser, they should now look a bit better! We just told your webpages to use the CSS rules described in those two files, and to apply them to your HTML code.

1. Positioning
Even though each element of your webpages now has a different style, you may notice they still are stacked on top of each other, and that’s probably not what you want. CSS brings a few different approaches to positioning that one may use depending on cases.For this project, we’re going to use CSS Flexbox, a recent set of CSS properties that work with recent browsers.Our goal is to get a layout that looks like this: