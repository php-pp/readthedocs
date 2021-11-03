Découpage en composants
===

PHP++ est un ensemble de composants.

Vous pouvez utiliser chaque composant séparément, aucun composant n'est obligatoire :
c'est à vous de choisir d'installer ce dont vous avez besoin !

Chaque composant peut être séparé en plusieurs repositories en fonction des besoins.

Les composants
---

+-------------------------------------------------+----------------------------------------------------------+
| Component                                       | Description                                              |
+=================================================+==========================================================+
| `collection <component/collection/index.html>`_ | Modèle objet pour remlacer ``array`` par une liste typée |
+-------------------------------------------------+----------------------------------------------------------+

Les composants pour le développement
---

.. note::

   Ces composants peuvent être installés dans n'importe quel environnement de Composer,
   via ``composer require`` ou ``composer require --dev``.
   Ils sont cependant pensés pour être utilisés dans un environnement de développement.

+-----------------------------------------------------+-----------------------------------------------------+
| Component                                           | Description                                         |
+=====================================================+=====================================================+
| `backtrace <component/backtrace/index.html>`_       | Recherche et affichage de la stack trace            |
+-----------------------------------------------------+-----------------------------------------------------+


Les composants pour la CI
---

.. note::

   Ces composants peuvent être installés dans n'importe quel environnement de Composer,
   via ``composer require`` ou ``composer require --dev``.
   Ils sont cependant pensés pour être utilisés dans une CI.

+-----------------------------------------------------+-----------------------------------------------------+
| Component                                           | Description                                         |
+=====================================================+=====================================================+
| `code-sniffer <component/code-sniffer/index.html>`_ | Code sniffer for PHP++ code style                   |
+-----------------------------------------------------+-----------------------------------------------------+
