
markup-viewer
========

A webcomponent which adds a viewer of lightweight markup language.

Now supports:

*   Commonmark
*   Asciidoc

Powered by:

*   [cdnjs](https://github.com/asciidoctor/asciidoctor.js)
*   [webcomponents.js](https://github.com/webcomponents/webcomponentsjs)
*   [commonmark.js](https://github.com/jgm/CommonMark)
*   [asciidoctor.js](https://github.com/asciidoctor/asciidoctor.js)


Live Demo
========

When you put _`<markup-viewer>`_ tag in a HTML file,
You can view markup files on a __static Web server__ using `markup` query.
__Inline links__ and __links to other markup files__ are available.

*   <http://kozom.github.io/markup-viewer/mv.html?markup=demo.md>


Usage
========

Just put below files on a static Web server:

*   __markup-viewer.html:__ Webcomponent which defines markup-viewer HTML tag
*   __mv.html:__            The simplest example using markup-viewer HTML tag
*   __demo.md:__            Commonmark demo
*   __demo.adoc:__          Asciidoc demo

Then open `mv.html?markup=demo.md` on your web browser.
