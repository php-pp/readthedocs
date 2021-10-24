Welcome to PHP++ documentation!
===============================

[PHP++](https://github.com/php-pp) is a PHP library with this behaviors:
 * Work with objects, do not use old functions (example: ``fileatime()`` -> ``FileUtils::getAccessedAt()``)
 * Do not care about ``E_NOTICE`` and it's friends, all PHP errors are catched and replaced by an exception
 * Replace ``array`` by ``Collection`` with only one type allowed (example: ``StringCollection``, ``DateTimeNullableCollection``)

Compatibles PHP versions: from 7.4 to the latest.

**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
