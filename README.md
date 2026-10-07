TP3 - Les formulaires HTML

Ce dépôt contient les fichiers source du troisième TP portant sur la création et la validation de formulaires HTML. Il met en pratique l'utilisation des balises sémantiques, des différents types de champs de saisie, ainsi que des attributs de validation native du HTML5.

Questions

(1) Quelle est la différence entre name et id ?
L'attribut id sert principalement à identifier de manière unique un élément dans la page HTML, ce qui permet notamment de le relier à son libellé (label) via l'attribut for. En revanche, l'attribut name est utilisé pour nommer les données du formulaire lors de leur envoi vers le serveur, afin de les identifier et de les récupérer facilement.

(2) Pourquoi utiliser post plutôt que get pour un mot de passe ?
La méthode get transmet les données du formulaire en les ajoutant directement à l'URL, ce qui les rend visibles dans la barre d'adresse et dans l'historique du navigateur. À l'inverse, la méthode post envoie les données de manière invisible dans le corps de la requête HTTP, garantissant ainsi un minimum de confidentialité et de sécurité pour des informations sensibles comme un mot de passe.