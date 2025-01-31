A normal block with parameters.

.. code-block:: solidity
    :force:
    :language: Solidity

    // SPDX-License-Identifier: GPL-3.0
    pragma solidity >=0.7.0 <0.9.0;

    contract C {
        function foo() public view {}
    }


.. warning::
    A Warning.

.. code-block:: solidity

    uint constant x = 42;

Text.

::

    contract C {}

A block with blank lines between block parameters.
Sphinx will treat the second one as a part of the code.

.. code-block:: solidity
    :force:

    :language: Solidity

    contract D {}
    :linenos:

Block with parameters indented less than code.
Sphinx does not complain about these.

.. code-block:: solidity
  :force:
  :linenos:

    contract E {}

More text.
