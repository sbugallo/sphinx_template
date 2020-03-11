Cheatsheet
==========

Text formatting
+++++++++++++++

================  ============================================================
Formatting        Usage
================  ============================================================
**bold**          \*\*bold\*\*
*italic*          \*italic\*
``verbatim``      \`\`verbatim\`\`
================  ============================================================


Hyperlinks
++++++++++

================  ========================================= ==============================
Type              Example                                   Usage
================  ========================================= ==============================
External          `<http://www.python.org/>`_               \`<http://www.python.org/>\`\_
Internal          :ref:`section_1`                          \:ref\:\`rst_tutorial\`
================  ========================================= ==============================

Lists
+++++

.. code-block:: rst

    * This is a bulleted list.
    * It has two items, the second
      item uses two lines. (note the indentation)

    1. This is a numbered list.
    2. It has two items too.

    #. This is a numbered list.
    #. It has two items too.

    * This is a  nested list

      1. one
      2. two
      3. three
      4. four
      5. five

    Definition list
        The term is a one-line phrase, and the definition is one or more paragraphs or body elements, indented relative
        to the term. Blank lines are not allowed between term and definition.

Result:

* This is a bulleted list.
* It has two items, the second
  item uses two lines. (note the indentation)

1. This is a numbered list.
2. It has two items too.

#. This is a numbered list.
#. It has two items too.


* This is a  nested list

  1. one
  2. two
  3. three
  4. four
  5. five

Definition list
    The term is a one-line phrase, and the definition is one or more paragraphs or body elements, indented relative
    to the term. Blank lines are not allowed between term and definition.

Footnotes and citations
+++++++++++++++++++++++

This is a footnote [#]_.

.. [#] And this is the explanation.

This is a citation [CIT2002]_.

.. [CIT2002] Bugallo, S. (2020). Sample article. Sample Journal.

Quotes
++++++

Block quotes are just:

    Indented paragraphs,

        and they may nest.

Tables
++++++

.. code-block:: rst

    +------------+------------+-----------+
    | Header 1   | Header 2   | Header 3  |
    +============+============+===========+
    | body row 1 | column 2   | column 3  |
    +------------+------------+-----------+
    | body row 2 | Cells may span columns.|
    +------------+------------+-----------+
    | body row 3 | Cells may  | - Cells   |
    +------------+ span rows. | - contain |
    | body row 4 |            | - blocks. |
    +------------+------------+-----------+

    =====  =====  ======
       Inputs     Output
    ------------  ------
      A      B    A or B
    =====  =====  ======
    False  False  False
    True   False  True
    False  True   True
    True   True   True
    =====  =====  ======

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======

Transitions
+++++++++++

A transition marker is a horizontal line of 4 or more repeated punctuation characters.

.. code-block:: rst

    ------------

------------

A transition should not begin or end a section or document, nor should two transitions be immediately adjacent.

Directives
++++++++++

Figures
-------

.. code-block:: rst

    .. figure:: ./assets/lena.png
       :width: 30%
       :align: center

Result

.. figure:: ./assets/lena.png
       :width: 30%
       :align: center

Code blocks
-----------

.. code-block:: rst

    .. code-block:: python

        from pathlib import Path

        a = Path(".")


Result

.. code-block:: python

    from pathlib import Path

    a = Path(".")

Admonitions
-----------

.. code-block:: rst

    .. seealso:: Sample text

    .. note:: Sample text

    .. warning:: Sample text

    .. attention:: Sample text

    .. caution:: Sample text

    .. danger:: Sample text

    .. error:: Sample text

    .. hint:: Sample text

    .. important:: Sample text

    .. tip:: Sample text


.. seealso:: Sample text

.. note:: Sample text

.. warning:: Sample text

.. attention:: Sample text

.. caution:: Sample text

.. danger:: Sample text

.. error:: Sample text

.. hint:: Sample text

.. important:: Sample text

.. tip:: Sample text


Math
++++

.. code-block:: rst

    .. math::

       (a + b)^2 = a^2 + 2ab + b^2

       (a - b)^2 = a^2 - 2ab + b^2

Result

.. math::

   (a + b)^2 = a^2 + 2ab + b^2

   (a - b)^2 = a^2 - 2ab + b^2