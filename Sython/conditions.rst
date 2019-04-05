Conditions
==========

Pour contruire vos conditions, Sython vous propose 3 types d'outils : les comparateurs, les opérateurs logiques et les conditions en elle-même.

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

Sython n'incorpore 4 types de conditions :

- If, noté 'if <condition> { <code> }'
- If-Else, noté 'if <condition> { <code> } else { <code> }'
- If-ElseIf, noté 'if <condition> { <code> } else if <condition> { <code> }' ou 'if <condition> { <code> } elseif <condition> { <code> }'
- If-ElseIf-Else, noté 'if <condition> { <code> } else if <condition> { <code> } else { <code> }' ou 'if <condition> { <code> } elseif <condition> { <code> } else { <code> }'

Exemple :

.. code-block:: python

    a = enter("Entrez un nombre entre 1 et 3 :")
    a = int(a)
    if a == 1
    {
        show("Process 1")
    }else if a == 2
    {
        show("Process 2")
    }elseif a == 3   # Ecrire else if ou elseif n'a pas d'importance.
    {
        show("Process 3")
    }else
    {
        show("Erreur : Votre nombre n'est pas entre 1 et 3.")
    }

.. note :: ATTENTION : Il ne doit pas y avoir de retour à la ligne entre } et else et entre } et else if. Sinon vous aurez une erreur.
