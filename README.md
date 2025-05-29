# Atelier-4
Exercices de Programmation Asynchrone
Exercice 1 : Programmation Asynchrone Basique
Objectif : Se familiariser avec les concepts fondamentaux de la programmation asynchrone en JavaScript, notamment l'utilisation de async/await et des Promises.

Fonctionnalités :

Simulation de la récupération de données utilisateur après un délai.

Affichage des informations d'un profil utilisateur.

Affichage d'une liste d'utilisateurs dans un tableau.

Démonstration de l'enchaînement de Promises pour simuler une séquence d'actions asynchrones.

Comment l'exécuter :

Ouvrez le fichier ex1.html (ou la section correspondante si vous avez un seul fichier) dans votre navigateur web.

Observez le message de chargement, puis l'affichage progressif des données utilisateur.

Consultez la console du navigateur (F12) pour voir les logs de l'enchaînement des Promises.

Exercice 2 : Interaction API Fichier (Simulée)
Objectif : Comprendre comment interagir avec une API pour le téléchargement et la récupération de fichiers en utilisant fetch et les Promises.

Fonctionnalités :

Formulaire de téléchargement de fichier (simulé).

Affichage d'une liste de fichiers "téléchargés".

Utilisation de fetch pour simuler les requêtes POST et GET.

Remarque sur l'API : L'API Laravel est simulée entièrement côté frontend en JavaScript. Aucun backend réel n'est nécessaire pour cet exercice. Les fichiers "téléchargés" ne sont pas stockés de manière persistante.

Comment l'exécuter :

Ouvrez le fichier ex2.html (ou la section correspondante) dans votre navigateur.

Utilisez le formulaire pour "télécharger" un fichier.

Cliquez sur "Actualiser la Liste des Fichiers" pour voir les fichiers apparaître.

Exercice 3 : Gestion des Salles (CRUD, Simulée)
Objectif : Implémenter les opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) pour la gestion des salles en utilisant fetch et les Promises.

Fonctionnalités :

Formulaire unique pour la création et la mise à jour des salles.

Tableau affichant la liste des salles avec des boutons "Éditer" et "Supprimer".

Modale de confirmation personnalisée pour la suppression.

Remarque sur l'API : L'API Laravel est simulée entièrement côté frontend en JavaScript. Les données des salles sont stockées en mémoire et ne sont pas persistantes après le rechargement de la page.

Comment l'exécuter :

Ouvrez le fichier ex3.html (ou la section correspondante) dans votre navigateur.

Ajoutez de nouvelles salles, éditez-les et supprimez-les pour tester les fonctionnalités CRUD.

Exercice 4 : Suivi des Stocks en Temps Réel (Simulé avec Highcharts & Pusher)
Objectif : Créer une application de suivi des stocks en temps réel, avec visualisation des données et simulation d'événements WebSockets via Pusher.

Fonctionnalités :

Formulaire CRUD pour la gestion des articles en stock.

Tableau affichant la liste des stocks actuels.

Visualisation des quantités de stock par produit à l'aide de Highcharts.

Simulation d'événements en temps réel : Les mises à jour (création, modification, suppression) déclenchent une simulation d'événement "StockUpdated" qui est "reçu" par le frontend via une intégration simulée de Pusher.js, mettant à jour le tableau et le graphique dynamiquement.

Remarque sur l'API et Pusher : Le backend Laravel, les WebSockets et l'intégration Pusher sont simulés entièrement côté frontend en JavaScript. Pour une implémentation réelle, vous auriez besoin d'un serveur Laravel configuré avec laravel-websockets et Pusher.

Dans le code, la clé Pusher ('your-app-key') et le cluster ('mt1') sont des placeholders qui devraient être remplacés par vos propres identifiants dans une application réelle.

Comment l'exécuter :

Ouvrez le fichier ex4.html (ou la section correspondante) dans votre navigateur.

Ajoutez, modifiez ou supprimez des articles en stock.

Observez le tableau et le graphique Highcharts se mettre à jour "en temps réel" après chaque opération.

Des messages d'information apparaîtront simulant la réception d'événements Pusher.

Configuration et Exécution
Pour exécuter ces exercices :

Clonez ce dépôt GitHub sur votre machine locale.

Ouvrez le fichier ex.html (ou les fichiers HTML individuels si vous les avez séparés) dans votre navigateur web préféré.

Aucune installation de serveur web ou de dépendances Node.js n'est nécessaire pour exécuter ces démos frontend, car toutes les interactions backend sont simulées en JavaScript.

Contributions
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

Licence
Ce projet est sous licence MIT.
