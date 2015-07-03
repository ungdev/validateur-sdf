# validateur-sdf

Page de validation des entrées des Soirées des Finaux de l'UTT.

Les préventes doivent être rentrées dans le fichier index.html avec le format suivant :
`{ "last_name":"Doe", "first_name": "John", "student_id":null, "card_id":53 }`. D'habitude, les préventes sont rentrées dans un document Google Docs et sont converties en ce format via [https://shancarter.github.io/mr-data-converter/](https://shancarter.github.io/mr-data-converter/).

Il n'y a aucune communication avec un serveur puisque les cartes évènement sont reprises lors de l'entrée et tout sortie est définitive : il n'est alors pas possible d'entrer plusieurs fois, il n'y a aucune vérification à faire. 

## Contributeurs

Le code de base a été écrit par Gabriel JUCHAULT (@extaze), quelques correctifs ont été apportés depuis.
