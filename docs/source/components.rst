Components
==========

PHP++ id a set of reusable components. You can use all of them of just the one you need.

``-contracts`` components
-------------------------

When it's possible, a component has it's counterpart ``-contract`` with only interfaces.

If you don't need to use our implementation of this interfaces
(you just need a typehint, you want to create your own implementation etc),
add the ``-contract`` dependency and work with interfaces.

Example:
.. code-block:: php
    :emphasize-lines: 3
    // You need a StringCollection to work with it,
    // don't use StringCollection but StringCollectionInterface
    function foo(StringCollectionInterface $strings): void
    {
        // Do some stuff here with $strings
    }

Components
----------

+----------------------+--------------------------------------------+----------------------------------------------------------------+
| Component            | Description                                | Github                                                         |
+======================+============================================+========+=======================================================+
| collection           | Replace array by a strict typed collection | `github.com <https://github.com/php-pp/collection>`_           |
+----------------------+--------------------------------------------+----------------------------------------------------------------+
| collection-contracts | Contracts for collection                   | `github.com <https://github.com/php-pp/collection-contracts>`_ |
+----------------------+--------------------------------------------+----------------------------------------------------------------+
| collection-generator | Helps you to generate a Collection         | `github.com <https://github.com/php-pp/collection-generator>`_ |
+----------------------+--------------------------------------------+----------------------------------------------------------------+

Development components
----------------------

+----------------------+--------------------------------------------+----------------------------------------------------------------+
| Component            | Description                                | Github                                                         |
+======================+============================================+========+=======================================================+
| code-sniffer         | Code sniffer for PHP++ code style          | `github.com <https://github.com/php-pp/code-sniffer>`_         |
+----------------------+--------------------------------------------+----------------------------------------------------------------+
