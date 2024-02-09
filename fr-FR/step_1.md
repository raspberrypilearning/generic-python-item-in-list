Il est facile de vérifier si un élément se trouve dans une liste en Python : tu peux utiliser le mot-clé `in` comme dans l'exemple ci-dessous. Si l'élément est dans la liste, le message « Trouvé ! » s'affiche.

```python
element_a_chercher = "feuille"
elements = ["pierre", "feuille", "ciseaux"]

if element_a_chercher in elements:
    print("Trouvé !")
```

Tu peux également utiliser une boucle pour continuer à exécuter un bout de code jusqu'à ce qu'un élément figure dans une liste donnée. Ceci est utile pour valider les données saisies. Dans l'exemple ci-dessous, nous utilisons l'opposé du mot-clé `in`  : `not in`.

```python
direction = ""
while direction not in ["N", "S", "E", "O"]:
    direction = input("Veuillez entrer une direction (N, S, E ou O) : ")
print(direction)
```

Cette boucle continuera à demander une direction jusqu'à ce que l'utilisateur en saisisse une qui se trouve dans la liste. Une fois que l'utilisateur aura saisi l'une des options proposées, cette direction s'affichera.
