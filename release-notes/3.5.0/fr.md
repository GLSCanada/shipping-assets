## v3.5.0

Cette version apporte des améliorations majeures en matière de sécurité, de gestion des comptes et de convivialité, ainsi que des améliorations clés pour l'expédition, le suivi et les notifications.

### Sécurité et protection des comptes

#### Protection renforcée de la connexion

 - Les comptes sont temporairement verrouillés après plusieurs tentatives de connexion infructueuses afin de prévenir les accès non autorisés
 - Les réponses de connexion sont désormais identiques, qu'un compte existe ou non, ce qui réduit les risques de découverte de comptes
 - Des messages clairs expliquent lorsqu'un compte est verrouillé et quand il pourra être réutilisé


#### Gestion améliorée des sessions

 - Expérience de connexion plus fiable - les utilisateurs restent connectés pendant une utilisation normale
 - Les sessions se prolongent automatiquement pendant l'activité (jusqu'à une durée maximale)
 - Toutes les sessions sont correctement fermées lors de la déconnexion ou après un changement de mot de passe
 - Suppression de l'ancienne option « Se souvenir de moi » au profit d'une gestion moderne et sécurisée des sessions
 - Renforcement supplémentaire de la sécurité en environnement de production


### Gestion des mots de passe et des identifiants

#### Exigences de mot de passe renforcées

 - Règles de mot de passe clairement affichées avec validation en temps réel lors de l'inscription et des modifications
 - Validation cohérente côté interface et côté système
 - Option afficher/masquer le mot de passe ajoutée à tous les champs concernés
 - Prise en charge complète en français et en anglais


#### Expiration et notifications des mots de passe

 - Les mots de passe expirent désormais après 12 mois
 - Notifications envoyées avant l'expiration et lorsque le mot de passe est expiré
 - Les notifications ouvrent directement l'écran de changement de mot de passe

#### Modification simplifiée des mots de passe

 - Tous les utilisateurs peuvent modifier leur propre mot de passe
 - La fonction « Mot de passe oublié » est maintenant disponible pour tous les utilisateurs disposant d'une adresse courriel valide
 - Lorsqu'un administrateur réinitialise un mot de passe, l'utilisateur est informé et doit le modifier à la prochaine connexion

#### Améliorations des adresses courriel et noms d'utilisateur

 - Les nouveaux utilisateurs doivent utiliser un identifiant au format courriel
 - Les utilisateurs existants avec un identifiant non conforme sont invités à le mettre à jour pour améliorer la sécurité et la récupération de compte
 - Les utilisateurs peuvent modifier leur adresse courriel / identifiant directement depuis le menu utilisateur
 - Les administrateurs peuvent modifier les adresses courriel d'autres utilisateurs (selon les permissions)
 - Lorsqu'un compte principal met à jour son courriel, l'adresse de contact de l'organisation est automatiquement synchronisée

#### Notifications et alertes

 - Prise en charge de notifications planifiées et ciblées, avec date d'expiration
 - Les notifications peuvent inclure des actions directes (ex. : changer le mot de passe, mettre à jour le courriel)
 - Amélioration de la fiabilité et de l'affichage des alertes
 - Contenu des notifications entièrement localisé

### Améliorations - Expédition et suivi

#### Preuve de livraison (POD)

 - Les preuves de livraison peuvent désormais être envoyées par courriel à un ou plusieurs destinataires
 - Format de courriel professionnel avec la POD en pièce jointe

#### Marchandises dangereuses

 - Amélioration de la détection et de l'identification des marchandises dangereuses
 - Accès simplifié aux documents de marchandises dangereuses depuis les écrans d'expédition

#### Améliorations du suivi

 - Expérience de suivi modernisée avec des données et une nomenclature plus cohérentes
 - Suivi des expéditions plus clair et plus fiable

#### Validation des collectes Guest Ship

 - Validation améliorée des demandes de collecte, incluant :
   - Délais pour les collectes le jour même
   - Fenêtres horaires minimales
   - Visibilité claire des heures limites des terminaux
 - Réduction du délai d'annulation des expéditions non payées pour une meilleure précision opérationnelle


#### Inscription et localisation

 - L'inscription est désormais limitée aux adresses canadiennes
 - Corrections complètes des traductions françaises et améliorations des libellés
 - Correction des titres et du routage bilingue

### Résumé

Cette version met l'accent sur:

 - Une sécurité de niveau entreprise, avec une meilleure protection des connexions, des sessions et des mots de passe
 - Une plus grande autonomie des utilisateurs, pour la gestion et la récupération des accès
 - Une communication améliorée, grâce à des notifications plus claires et plus utiles
 - Des améliorations opérationnelles, notamment pour la POD, les marchandises dangereuses et les collectes
 - Une expérience plus fiable et plus soignée pour le suivi, l'inscription et la localisation

