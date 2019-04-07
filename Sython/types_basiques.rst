Types Basiques
==============

Sython est un langage où les types basiques ont quelques contraintes et méthodes.

Integer
-------

Tous les opérateurs arithmétiques sont utilisables.

Aucune méthode n'est proposé pour ce type.

Float
-----

Tous les opérateurs arithmétiques sont utilisables.

Aucune méthode n'est proposé pour ce type.

Boolean
-------

Avec ce type, on ne peut utiliser que les opérateurs logiques défini dans les conditions.

Les opérateurs arithmétiques (+, -, *, /, //, %, **, ++, --) ne fontionneront pas, quelque soit le type de la seconde opérande.


Aucune méthode n'est proposé pour ce type.

String
------

Vous pouvez addition un string avec n'importe quoi, la seconde opérande seront transformés en string.

Les autres opérations ne sont pas possibles sauf :

- Incrémentation : Va simplement additionner votre string à lui même
- Soustraction par un entier : va enlever x caractères à votre string (x étant votre entier)
- Multiplication par un entier : va afficher x fois votre string (x étant votre entier)


String contient une méthode :

- length, noté '<nom>.length()', retournera la longueur de votre string.

.. code-block:: python

    a = "Bonjour"
    show(a.length()) # Affichera 7