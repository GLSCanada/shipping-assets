## v3.0.17

### Nouvelles fonctionnalités et améliorations

#### Recherche de destinataires

Dans la continuité de notre mise à jour précédente, nous avons continué à affiner notre recherche de destinataire. Vous obtiendrez désormais des résultats plus précis lors de la recherche de destinataires, ce qui vous permettra de trouver facilement la personne que vous recherchez. Nous avons également optimisé les performances, de sorte que les recherches sont plus rapides et plus réactives dans la plupart des scénarios.

En plus de nos méthodes de recherche existantes `Nom` (anciennement appelées `Par défaut`) et `ID unique`, nous avons également ajouté deux nouvelles méthodes, `Adresse` et `Avancée`. Ces nouvelles méthodes de recherche vous permettent d'adapter l'application à votre flux de travail, au lieu de devoir ajuster votre flux de travail en fonction de celui-ci.

![Liste déroulante des méthodes de recherche](https://raw.githubusercontent.com/GLSCanada/shipping-assets/7634f3136d650c4b252f5ff743e14d4a1b2d7352/release-notes/3.0.17/assets/search-method-options.webp)

- La recherche `Nom` a été grandement améliorée pour classer plus précisément les résultats pertinents.
- La recherche `ID unique` devrait être plus performante.
- La recherche `Adresse` vous permet de rechercher des destinataires par ligne de rue et/ou code postal.
- La recherche `Avancée` est une recherche générique qui permet de trouver des destinataires à partir de presque toutes les informations, y compris toutes les informations ci-dessus, mais également les noms de contact, les adresses e-mail, les numéros de téléphone, etc. Bien qu'elle soit très flexible, en raison de sa nature étendue, les performances sont plus variables et les résultats peuvent ne pas toujours apporter les résultats escomptés, car elle a plus de chances de correspondre à de nombreux champs différents.

Expérimentez les différentes méthodes de recherche et choisissez celle qui vous convient le mieux.

#### Descriptions des colis de fret

Lorsque vous ajoutez des colis à votre expédition de fret, vous avez désormais la possibilité de remplir un champ de description facultatif. Toutes les informations que vous renseignez ici apparaîtront sur votre connaissement.

![Description field on package details](https://raw.githubusercontent.com/GLSCanada/shipping-assets/7634f3136d650c4b252f5ff743e14d4a1b2d7352/release-notes/3.0.17/assets/parcel-description-field.png)

### Correctifs & Autres Modifications Diverses

- Amélioration de la fiabilité de l'importation en masse des destinataires
- Amélioration de la détection des adresses résidentielles
- Correction d'un problème qui, dans de rares cas, planifiait un ramassage pour l'expéditeur par défaut au lieu de l'expéditeur actuellement sélectionné
- Correction d'un problème qui affichait de manière trompeuse une erreur lors de la mise à jour d'un utilisateur même si aucune erreur ne s'était produite
- Correction d'un problème qui empêchait la suppression d'un utilisateur
- Améliorations mineures de la localisation
