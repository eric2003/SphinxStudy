reStructuredText
================

Getting started
---------------
Bullet lists:

- This is item 1
- This is item 2

- Bullets are "-", "*" or "+".
  Continuing text must be aligned
  after the bullet and whitespace.

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   
   /inline-markup/index
   /escape
   /sections
   /lists/index
   /blocks/index
   /tables/index
   /transitions/index
   



Note that a blank line is required
before the first item and after the
last, but is optional between items.

Enumerated lists:

3. This is the first item
4. This is the second item
5. Enumerators are arabic numbers,
   single letters, or roman numerals
   
6. List items should be sequentially
   numbered, but need not start at 1
   (although not all formatters will
   honour the first index).
#. This item is auto-enumerated

Preparing your project on GitHub
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To start, `sign in to GitHub <https://github.com/login>`_
and navigate to `the tutorial GitHub template <https://github.com/readthedocs/tutorial-template/>`_,
where you will see a green :guilabel:`Use this template` button.
Click it to open a new page that will ask you for some details:
*emphasis* emphasis

Getting started
---------------

- This is the first bullet list item.  The blank line above the
  first list item is required; blank lines between list items
  (such as below this paragraph) are optional.

- This is the first paragraph in the second item in the list.

- This is the third item of the main list.

This paragraph is not part of the list.

* **Overview of core features**:
  :doc:`features`
  
.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Features

   /features

How-to Guides
-------------

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
