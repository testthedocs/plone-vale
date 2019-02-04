==========
Plone Vale
==========

Spelling, grammar, style, and readability linter.

Custom container build for `Plone <https://plone.org>`_.


.. code-block:: shell

   docker run -it -v `pwd`:/srv/tests testthedocs/plone-vale

   /srv/tests/index.md
   1:3   suggestion  'Contributing To The            plone.Titles
                   Documentation' should be in
                   title case
   7:32  suggestion  Don't start a sentence with     plone.So
                   'so'
   31:4  suggestion  'Edit In The Cloud' should be   plone.Titles
                   in title case
   33:1  suggestion  Write short sentences (less     plone.SentenceLength
                   than 25 words).
   36:1  suggestion  Write short sentences (less     plone.SentenceLength
                   than 25 words).
   71:4  suggestion  'Editing The Docs Using Git'    plone.Titles
                   should be in title case

   ✔ 0 errors, 0 warnings and 6 suggestions in 1 file.


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

   docker run -it -v `pwd`:/srv/tests testthedocs/plone-vale


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
 
