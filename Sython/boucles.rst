Boucles
=======

Sython n'incorpore pour l'instant deux types de boucle. Mais on prévoit en plus la boucle for.

Loop
----

Cette boucle permet d'exécuter x fois une action. Sa syntaxe est 'loop <nombre> { <code> }'

Exemple :

.. code-block:: python

    a = "Bonjour"
    loop 5
    {
        show(a) 
    } # Affichera 5 fois "Bonjour"

While
-----

Cette boucle permet d'exécuter une action tant qu'une expression est vraie. Sa syxtaxe est 'while <condition> { <code> }'

Exemple :

.. code-block:: python

    a = 0
    while a < 10
    {
        a ++
        show(a)
    } # Affichera les nombres de 1 à 10 (bornes comprises)

