Simple DocBook Porject with XInclude
====================================

This is a simple project to help people using DocBook to documentate sbt based projects.


This project is a plugin for [sbt 0.11](https://github.com/harrah/xsbt)
(and above) providing tasks to transform DocBook XML files to various output
formats like HTML, PDF, EPUB, and others.

The main advantage of this plugin is that you don't need to have the DocBook
stylesheets installed nor do you need any other tools to create advanced
formats like PDF. It all runs out of the box!

Usage
-----

1. Install [sbt 0.11.2](https://github.com/harrah/xsbt)
2. Clone [sbt-docbook-plugin](git@github.com:jm2dev/sbt-docbook-plugin.git) and publish localthis repository and publish locally
   <pre>
   git clone git@github.com:jm2dev/sbt-docbook-plugin.git
   cd sbt-docbook-plugin
   sbt package publish-local
   </pre>
3. Clone this project and check you can generate a valid output (pdf, xhtml, ...)
   <pre>
   git clone git@github.com:jm2dev/jm-sbt-docbook.git
   cd jm-sbt-docbook
   sbt pdf xhtml
   </pre>
4. Modify or create your docbook files.

This files will be written to the `target` subdirectory.

Misc.
-----

The following links have been very helpful to help me replace docbook maven plugin and include documentation in sbt based projects.

- [janm399 sbt docbook plugin fork](https://github.com/janm399/sbt-docbook-plugin)

- [specs2-spring](https://github.com/janm399/specs2-spring)

License
-------

Feel free to use it and promote DocBook usage.
