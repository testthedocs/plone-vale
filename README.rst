==========
Plone Vale
==========

Spelling, grammar, style, and readability linter.

Custom container build for `Plone <https://plone.org>`_.


Features
========

Flexible English language linter with dozens of predefined checks.


Dependencies
============

- `Docker <https://docker.com>`_


Installation
============

Pull the image:

.. code-block:: shell

   docker pull testthedocs/plone-vale

Usage
=====

Run `ttd-vale` from in your docs directory:

.. code-block:: shell

   docker run --rm -it -v $(pwd)/styles:/srv/styles --rm -v $(pwd)/source:/srv testthedocs/plone-vale


Contribute
==========

- `Issue Tracker <https://github.com/testthedocs/plone-vale/issues>`_
- `Source Code <https://github.com/testthedocs/plone-vale/tree/master/ttd-vale>`_


Support
=======

If you are having issues, please let us know.


License
=======

`MIT <https://choosealicense.com/licenses/mit/>`_
 
