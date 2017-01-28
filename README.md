
markup-viewer
====================

A webcomponent which adds a viewer of files written in markup language

Now supports:

*   Commonmark

Powered by:

*   [webcomponents.js](https://github.com/webcomponents/webcomponentsjs)
*   [commonmark.js](https://github.com/jgm/CommonMark)


Live Demo
====================

When you put `<markup-viewer>` tag in a HTML file,
You can view files on a **static webserver** using `markup` query.
Inline links and **links to other markup files** are available.

*   <http://kozom.github.io/markup-viewer/index.html?markup=demo.md>


Usage
====================

If you use cdnjs:

1.  Just put markup-viewer.html and markup files, on a static webserver

2.  Add below three lines on a HTML file

    ```
    <script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.7.23/webcomponents-lite.min.js"></script>
    <link rel="import" href="markup-viewer.html" />
    <markup-viewer></markup-viewer>
    ```

If you use bower:

1.  Install from bower on a webserver

        bower install markup-viewer

2.  Add below three lines on your HTML file

    ```
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="bower_components/markup-viewer/dist/markup-viewer.html" />
    <markup-viewer></markup-viewer>
    ```
