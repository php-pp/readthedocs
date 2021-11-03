Welcome to PHP++ documentation!
===

`PHP++ <https://github.com/php-pp>`_ is a PHP library with this features:
 * Install only what you need: PHP++ is a set of reusable components
 * Work with objects, do not use functions (example: ``fileatime()`` -> ``FileUtils::getAccessedAt()``)
 * Do not care about ``E_NOTICE`` and it's friends, all PHP errors are catched and replaced by an exception
 * No more problems with parameters position or multiple return types: everything is typed and errors are converted as exception
 * Replace ``array`` by ``Collection`` with only one type allowed (example: ``StringCollection``)

Compatibles PHP versions: from ``7.4`` to the ``latest``.

.. note::

   This project is under active development.

Components
---

`See the list of components. <components.html>`_

Issues
---

If you find an issue, go to `github.com/php-pp <https://github.com/php-pp>`_, select the component that has a problem
and create a ticket in the ``Issue`` tab.

.. toctree::
   :caption: PHP++
   :maxdepth: 1
   :hidden:

   components
   contracts

.. toctree::
   :caption: Composants
   :maxdepth: 1
   :hidden:

   component/collection/index

.. toctree::
   :caption: Composants pour le développement
   :maxdepth: 1
   :hidden:

   component/backtrace/index

.. toctree::
   :caption: Composants pour la CI
   :maxdepth: 1
   :hidden:

   component/code-sniffer/index
