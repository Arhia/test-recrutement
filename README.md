## Test de recrutement Arhia

Objectif de l'exercice : Réaliser une todo app.

### Specs :

  - 1 - Pouvoir ajouter une tâche
  -  2 - Pouvoir indiquer qu'une tâche est faite (avec la date de réalisation) ou à faire
  -  3 - Pouvoir supprimer une tâche.
  -  4 - Pouvoir modifier une tâche existant (en cliquant dessus, affiche une fenêtre modale correspondant à la spec 7).
  -  5 - Filtre (checkbox) pour afficher les tâches effectuées ainsi que la date a laquelle elles ont été effectués.
  -  6 - Créer une tâche de manière aléatoire via un bouton sur l'interface. La description de la tâche sera générée de cette façon : piocher une action dans la liste d'actions actions.json (déjà incluse dans le repo), un objet aléatoire dans objects.json (déjà incluse dans lerepo) et les concaténer pour former une phrase qui sera utiliser comme description de la tâche.
  -  7 - Cliquer sur la description d'une tâche affiche une fenêtre modale contenant la description, l'état (fait/pas fait) (les modifs d'un todo sont faites dans cette box) ainsi qu'une photo de chat aléatoire (histoire de mettre un peu de gaieté dans cette TODO list) grâce a ce endpoint : http://aws.random.cat/meow

### Infos supp :

- Lorsque l'utilisateur coche une tâche, elle ne doit plus affichée à l'utilisateur (sauf si on affiche les tâches effectuées avec le filtre)
- Les tâches sont triées par ordre d'insertion
- Les données doivent être stockées coté browser uniquement (il n'y a pas de back)

### Technos :

- Front :  React ou ExtJS
- Back : n/a

### Rendu :
s
- Le design et les couleurs sont libres.
- Sur un repos Github
- README.md (les choses nécessaires à une reprise de projet, setup dépendance etc...)

### Bonus

- Si l'application est responsive, c'est un +

### Exemple de TODO app "basique" :

-> http://todolistme.net/