Contracts
=========

Quand c'est possible, un composant n'est qu'une implémentation d'interfaces, qu'on appelle des contrats.

Ces interfaces se trouvent dans un repository qui a le même nom que le composant, avec le suffixe ``-contract``.

Vous pouvez créer votre propre implémentation tant que vous respectez tous les contrats.

Composants avec des contrats
----------------------------

+-------------------------------------------------+-------------------------------------------------------------+
| Composant                                       | Contrat                                                     |
+=================================================+=============================================================+
| `collection <component/collection/index.html>`_ | `collection-contract <component/collection/contract.html>`_ |
+-------------------------------------------------+-------------------------------------------------------------+

Example d'utilisation
---------------------

Si vous utilisez le composant `collection <component/collection/index.html>`_,
vous pouvez typer un paramètre avec ``StringCollection``.

Cette façon de typer votre paramètre forcera l'appelant à utiliser
une certaine implémentation du contrat ``StringCollectionInterface``, alors que vous n'avez peut-être pas besoin
de cette implémentation très précisément.

Il vaut alors mieux utiliser ``StringCollectionInterface`` comme typage, pour laisser à l'appelant le choix d'utiliser
l'implémentation qu'il veut.
Dans ce cas, vous pouvez également installer la dépendance
`php-pp/collection-contract <https://github.com/php-pp/collection-contract>`_ au lieu de
`php-pp/collection <https://github.com/php-pp/collection>`_.

.. code-block:: php

    <?php
    // Vous forcez l'utilisation de StringCollection
    function foo(StringCollection $strings): void
    {
    }

    // Vous laissez le choix à l'appelant d'utiliser l'implémentation qu'il veut
    function bar(StringCollectionInterface $strings): void
    {
    }
