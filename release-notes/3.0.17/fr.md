## v3.0.17

### Nouvelles fonctionnalités et améliorations

#### Recherche de destinataires

Dans la continuité de notre mise à jour précédente, nous avons continué à affiner la recherche de destinataires. Vous obtiendrez désormais des résultats plus précis lors de la recherche de destinataires, ce qui vous permettra de trouver facilement la personne que vous recherchez. Nous avons également optimisé les performances, de sorte que les recherches sont plus rapides et plus réactives dans la plupart des scénarios.

En plus de nos méthodes de recherche existantes `Nom` (anciennement appelées `Par défaut`) et `ID unique`, nous avons également ajouté deux nouvelles méthodes : `Adresse` et `Avancée`. Ces nouvelles méthodes de recherche vous permettent d'adapter l'application à votre flux de travail, plutôt que d'ajuster votre flux de travail en fonction de l'application.

![Liste déroulante des méthodes de recherche](https://raw.githubusercontent.com/GLSCanada/shipping-assets/7634f3136d650c4b252f5ff743e14d4a1b2d7352/release-notes/3.0.17/assets/search-method-options.webp)

- La recherche `Nom` a été grandement améliorée pour classer plus précisément les résultats pertinents.
- La recherche `ID unique` devrait être plus performante.
- La recherche `Adresse` vous permet de rechercher des destinataires par ligne de rue et/ou code postal.
- La recherche `Avancée` est une recherche générique permettant de trouver des destinataires à partir de presque toutes les informations, y compris celles mentionnées ci-dessus (noms de contact, adresses e-mail, numéros de téléphone, etc.). Bien qu'elle soit très flexible, les performances peuvent être plus variables, et les résultats peuvent ne pas toujours correspondre aux attentes, car elle a plus de chances de correspondre à différents champs.

Expérimentez ces méthodes et choisissez celle qui correspond le mieux à votre flux de travail.

#### Descriptions des colis de fret

Lors de l'ajout de colis à votre expédition de fret, vous avez désormais la possibilité de remplir un champ de description facultatif. Les informations renseignées apparaîtront sur le connaissement.

![Descriptions des colis de fret](https://raw.githubusercontent.com/GLSCanada/shipping-assets/7634f3136d650c4b252f5ff743e14d4a1b2d7352/release-notes/3.0.17/assets/parcel-description-field.png)

### Correctifs & Autres Modifications Diverses

- Amélioration de la fiabilité de l'importation en masse des destinataires.
- Amélioration de la détection des adresses résidentielles.
- Correction d'un problème qui, dans de rares cas, planifiait une cuillette pour l'expéditeur par défaut au lieu de l'expéditeur actuellement sélectionné.
- Correction d'un problème qui affichait de manière trompeuse une erreur lors de la mise à jour d'un utilisateur, même si aucune erreur ne s'était produite.
- Correction d'un problème qui empêchait la suppression d'un utilisateur.
- Améliorations mineures de la localisation.
