
markup-viewer
====================

A webcomponent which adds a viewer of markup languages such as commonmark


Live Demo
====================

_`<markup-view>`_ tag works like below.

*   <http://kozom.github.io/markup-viewer/index.html>

You can view files on a static webserver by _markup_ query.

*   Commonmark: <http://kozom.github.io/markup-viewer/index.html?markup=demo.md>
*   Asciidoc: <http://kozom.github.io/markup-viewer/index.html?markup=demo.adoc>

These are raw files.

*   Raw Commonmark: <http://kozom.github.io/markup-viewer/demo.md>
*   Raw Asciidoc: <http://kozom.github.io/markup-viewer/demo.adoc>


Usage
====================

1.  Install from bower

        bower install markup-viewer

2.  Add below three lines on your HTML file

    ```
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="bower_components/markup-viewer/dist/markup-viewer.html" />
    <markup-viewer></markup-viewer>
    ```

3.  Open the HTML file on your browser like below

        http://your.server/your.html?markup=<uri-of-a-markup-file>

    <uri-of-a-markup-file> must contain valid file extention, e.g. md or adoc.

The markup file will be parsed to HTML and shown on your browser.
