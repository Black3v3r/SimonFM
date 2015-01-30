#**Projet le jeu Simon**

##**Spécifications**

###Analyse des besoins / Objectifs et fonctionnalités
- Interface graphique (SDL 2.x)
- Gestion des utilisateurs
 - compte (login, mot de passe)
- 3 niveaux de difficulté
 - 4, 5 ou 6 lumières
 - accélération
- Pouvoir rejouer
- Gestion des statistiques
 - Parties jouées, gagnées, perdues

###Vues (IHM)
- Écran d'accueil / menu
 - Créer un compte
 - Se connecter
- Une fois connecté
 - Jouer
 - Afficher les statistiques
 - Se déconnecter
- In game
 - 4 tuiles: une par coin
 - 5 tuiles: une par coin plus centre
 - 6 tuiles: pi/3
- En fin de partie
 - Rejouer
 - Menu principal

##**Conception détaillée**

##Fonctions

###Utilisateur
- Créer un compte
 - Vérifier l'existance
 - Demander login + mot de passe
 - hash + stockage
 - Créer fichier de stats
- Identification
 - Vérification login + mdp, si inexistant, proposer de créer un compte
- Statistiques
 - Actualiser en fin de partie
 - Afficher les statistiques


###Jeu
- Génération d'un pattern
 - Couleur et durée
- Détection du clic
 - Quitter + boutons de jeu
- Détection de l'appui de touches
 - Échap (+ boutons de jeu ?)
- Allumage bouton
- Allumage par action (enfoncé)

###Difficulté
- Sélection de la difficulté

##Fichiers
- Comptes utilisateurs (structures)
- Statistiques

##Structures
 - Compte
  - Login, mot de passe (hash), 10 meilleurs scores
 - Bouton
  - 

##Gestion des images
1 image par bouton à découper
- Neutre
- Enfoncé ( + allumé)
- Allumé

Fond universel

Plateau de jeu
