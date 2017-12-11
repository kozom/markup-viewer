
markup-viewer
========

A webcomponent which adds a viewer of files written in markup language.

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
You can view files on a __static Web server__ using _markup_ query.
__Inline links__ and __links to other markup files__ are available.

*   <http://kozom.github.io/markup-viewer/index.html?markup=demo.md>


Usage
========

Just put below files on a static Web server:

*   markup-viewer.html: Webcomponent which defines markup-viewer HTML tag
*   mv.html:            The simplest example using markup-viewer HTML tag
*   demo.md:            Commonmark demo
*   demo.adoc:          Asciidoc demo

Then open `mv.html?markup=demo.md` on your web browser.
