Types Complexes
===============

Sython possède aussi quelques types complexes. Actuellement, seulement un est implémenté : List

List
----

Ce type représente tout simplement une liste d'élément.

Pour la créer il fait faire '<nom> = [<elements>]' avec chaque élément séparé par une virgule.

.. code-block:: python

    a = [1, 2, 3]
    show(a) #Affichera [1, 2, 3]

Vous pouvez aussi afficher l'élément à l'index x avec '<nom>[<index>]'.

.. code-block:: python

    a = [1, 2, 3]
    show(a[0]) #Affichera 1

.. note :: ATTENTION : Les indexes des listes commencent à 0

Les listes possèdes aussi 2 méthodes :

- length, noté '<nom>.length()' qui retournera le nombre d'élément dans la liste
- remove, noté '<nom>.remove(<index>)' qui effacera l'élément d'index <index> et le retournera.

.. code-block:: python

    a = [1, 2, 3]
    show(a.remove(0)) #Affichera 1
    show(a) # Affichera [2, 3]