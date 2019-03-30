Variables
=========

Sython est un langage où il n'est pas important de préciser le type de la variable. De plus, les conversions sont, dans la plupart des cas, implicite.

Déclaration
-----------

Actuellement, Sython comporte 4 types basiques différents :

- integer, pour les entiers
- float, pour les nombres à virgules
- string, pour les chaines de caractères
- boolean, soit vrai (true), soit faux (false)

Pour déclarer une variable, il faut suivre le paterne suivant : <nom> = <valeur>

Exemple :

.. code-block:: python

    entier = 1
    flottant = 1.0
    texte = "Bonjour"
    etat = true

.. note :: Comme vous avez pû l'apercevoir, les flottants n'utilise pas une virgule mais un point pour différencier la partie entière de la partie décimal

Affectation
-----------

Si vous voulez réaffecter une nouvelle valeur à votre variable, vous pouvez la redéclarer comme au-dessus :

Exemple :

.. code-block:: python

    // Déclaration
    entier = 1
    // Nouvelle affection
    entier = 2

.. note :: Ici, il y a aussi l'introduction des commentaires via le double symbole "//".

Opérations
----------

Actuellement, Sython supporte 4 opérations :

- Addition : '+'
- Soustraction : '-'
- Multiplication : '*'
- Division : '/'
- Modulo : '%'
- Puissance : '^'
- Division Euclidienne : '//'

Exemple :

.. code-block:: python
  
    entier1 = 2
    entier2 = 3 + 4
    entier3 = entier1 * entier2
    phrase = "Bonjour "+"tout le monde"
    entier4 += entier2

.. note :: Ici, il y a aussi l'introduction des opérateurs affectifs via la notation : <variable> <operateur>= <valeur|variable> (Dispo pour tous les opérateurs).

Conversion
----------

Malgré le fait que les conversions peuvent être fait par Sython, vous pouvez les faire par vous même :

Exemple :

.. code-block:: python
  
    nombre = "1"
    // 'nombre' contient "1"
    nombre = int(nombre)
    // 'nombre' contient 1

.. note :: Attention, si la conversion n'est pas possible, vous aurez une erreur