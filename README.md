# Diagramme de classe

![Classes](uml/classes.png)

## Vrai ou faux

Etant donné le diagramme de domaine ci-dessus, les assertions suivantes sont-elles vraies ou fausses ?

- Etudiant est une classe d’association, vrai
- Un étudiant peut participer à autant de cours qu’il veut, faux
- Plusieurs professeurs peuvent enseigner la même discipline, faux
- Un professeur peut enseigner plusieurs disciplines, vrai
- Un cours peut être enseigner à 2 étudiants, faux
- Un cours peut être enseigner à 20 étudiants, vrai

## Question ouverte

Représentez la même association avec la notation UML « petit losange »
Je n'ai pas réussi à le faire avec plantUML mais, il faudrait mettre le losange entre Professeur, Disipline et Etudiant et l'appeler Cours

- Quelles informations perd-on par rapport au diagramme ci-dessus ?

On perd l'information que Cours est une classe d'association. Si Cours a des attributs, on les perd aussi.
