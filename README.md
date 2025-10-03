# Celo---Devinette-nombre

Fonctionnalités principales :
Démarrer une partie :

nouvellePartie() - Génère un nombre aléatoire entre 1 et 10 et démarre une nouvelle partie

Jouer :

deviner(uint256 _nombre) - Propose un nombre et reçoit une réponse :

✅ "GAGNÉ !" si c'est le bon nombre (la partie se termine)
⬆️ "PLUS HAUT" si le nombre secret est plus grand
⬇️ "PLUS BAS" si le nombre secret est plus petit



Gestion :

abandonner() - Révèle le nombre secret et termine la partie
obtenirInfosPartie() - Affiche le nombre de tentatives et l'état de la partie

Statistiques :

obtenirStatistiques() - Nombre de victoires, total de tentatives, moyenne
Chaque joueur a ses propres statistiques sauvegardées

Caractéristiques techniques :

Chaque joueur a sa propre partie indépendante
Le nombre est généré de façon pseudo-aléatoire en utilisant le timestamp, prevrandao, l'adresse du joueur et le numéro de bloc
Les tentatives sont comptabilisées automatiquement
Des événements sont émis pour suivre l'historique du jeu
Pas de fonds impliqués, c'est un jeu purement ludique !

Le jeu encourage les joueurs à améliorer leur stratégie pour gagner en moins de tentatives possible ! 🎯
