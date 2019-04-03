Conditions
==========

Les conditions complexes n'ont pas encore été implémentés dans Sython. Cependant, vous pouvez déjà utiliser des conditions simples.

Comparateurs
------------

Sython incorpore 5 comparateurs :

- Egal, noté "=="
- Inférieur, noté "<"
- Supérieur, noté ">"
- Inférieur ou Egal, noté "<="
- Supérieur ou Egal, noté ">="

Exemple :

.. code-block:: python

    a = "1"
    b = 1
    c = type(a) == type(b) # Sera égal à Faux vu que a et b ont pas le même type.


Opérateurs Logiques
-------------------

Sython incorpore 3 opérateurs logiques :

- Et, noté "and" ou "&&"
- Ou, noté "or" ou "||"
- Non, noté "not" ou "!"

Exemple :

.. code-block:: python

    a = 18
    b = 20
    c = a == 18 && b == 20 # Sera égal à True

.. note :: Ici, vous pouvez remplacer && par and.

Conditions
----------

Sython n'incorpore pour l'instant que des conditions simples :

- If, noté 'if <condition> { <code> }'
- If-Else, noté 'if <condition> { <code> } else { <code> }'

Exemple :

.. code-block:: python

    a = enter("Votre age :")
    a = int(a)
    if a >= 18
    {
        show("Vous etes majeur")
    }else
    {
        show("Vous etes mineur")
    }

.. note :: ATTENTION : Il ne doit pas y avoir de retour à la ligne entre le } et else. Sinon vous aurez une erreur.