Contributing to documentation
=============================

Github
------

If you are ok with using a web interface or just want to make some small change you can use the 'Edit on Github' buttons

Local Build
-----------

If you'd rather work on your own machine, in a more powerful editor, here are some steps to do this

Make sure python & pip are installed

Install Sphinx::

    pip install sphinx sphinx-autobuild

Clone the documentation repository to your machine::

    git pull https://github.com/niekcandaele/CSMM-issues

Make your changes

Build your new version::

     make html

Open index.html from the _build folder.

Autmatically rebuild when a file changes::

    sphinx-autobuild . _build/html



Once you have changes to add, open up a pull request!

