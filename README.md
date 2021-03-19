MDN Web Docs

Active learning: A Web Font Example

With this in mind, let's build up a basic web font example from first principles. It is difficult to demonstrate this using an embedded live example, so instead, we would like you to follow the steps detailed in the below sections, to get an idea of the process.

You should use the <a href="https://github.com/mdn/learning-area/blob/master/css/styling-text/web-fonts/web-font-start.html">web-font-start.html</a> and <a href="https://github.com/mdn/learning-area/blob/master/css/styling-text/web-fonts/web-font-start.css">web-font-start.css</a> files as a starting point to add your code to (see the <a href="https://mdn.github.io/learning-area/css/styling-text/web-fonts/web-font-start.html">live example</a>). Make a copy of these files in a new directory on your computer now. In the web-font-start.css file, you'll find some minimal CSS to deal with the basic layout and typesetting of the example.

Finding fonts

For this example, we'll use two web fonts, one for the headings, and one for the body text. To start with, we need to find the font files that contain the fonts. Fonts are created by font foundries and are stored in different file formats. There are generally three types of sites where you can obtain fonts:

1. A free font distributor: This is a site that makes free fonts available for download (there may still be some license conditions, such as crediting the font creator). Examples include <a href="https://www.fontsquirrel.com/">Font Squirrel</a>, <a href="https://www.dafont.com/">dafont</a>, and <a href="https://everythingfonts.com/">Everything Fonts</a>.

2. A paid font distributor: This is a site that makes fonts available for a charge, such as <a href="https://www.fonts.com/">fonts.com</a> or <a href="https://www.myfonts.com/">myfonts.com</a>. You can also buy fonts directly from font foundries, for example <a href="https://www.linotype.com/">Linotype</a>, <a href="https://www.monotype.com/">Monotype</a>, or <a href="https://www.exljbris.com/">Exljbris</a>.

3. An online font service: This is a site that stores and serves the fonts for you, making the whole process easier. See the <a href="https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Web_fonts#using_an_online_font_service">Using an online font service</a> section for more details.

Let's find some fonts! Go to <a href="https://www.fontsquirrel.com/">Font Squirrel</a> and choose two fonts — a nice interesting font for the headings (maybe a nice display or slab serif font), and slightly less flashy and more readable font for the paragraphs. When you find each font, press on the download button, and save the file inside the same directory as the HTML and CSS files you saved earlier. It doesn't matter whether they are TTF (True Type Fonts) or OTF (Open Type Fonts).

In each case, unzip the font package (Web fonts are usually distributed in ZIP files containing the font file(s) and licensing information). You may find multiple font files in the package — some fonts are distributed as a family with different variants available, for example thin, medium, bold, italic, thin italic, etc. For this example, we just want you to concern yourself with a single font file for each choice.
