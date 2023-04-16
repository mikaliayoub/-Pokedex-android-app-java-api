# Pokedex App

Il s'agit d'une application Pokedex basée sur Java qui utilise l'API HTTP pour afficher des informations sur les Pokémon.
L'application comprend une section de recherche où les utilisateurs peuvent chercher un Pokémon par son nom, et en cliquant sur un Pokémon, une nouvelle disposition s'affiche montrant ses détails tels que le poids, la taille, et les statistiques comprenant la PV, l'attaque, la défense, et la vitesse. L'image du Pokémon est affichée sous forme de GIF.
L'application est simple et facile à utiliser.

# Features:

Liste de tous les Pokémon avec leurs noms et images.
Barre de recherche pour chercher un Pokémon par nom.
Page de détails pour chaque Pokémon affichant leur poids, taille et statistiques (PV, attaque, défense, vitesse).
Image GIF animée pour chaque Pokémon.
Pagination pour charger plus de Pokémon lorsque l'utilisateur fait défiler.

# Technologies:

Android SDK : Fournit les fondations de l'interface utilisateur et du comportement de l'application.
Java : Utilisé comme langage de programmation principal pour la logique de l'application.
Picasso : Une bibliothèque de chargement et de mise en cache d'images puissante qui aide à afficher les images de Pokémon dans l'application.
AppCompat : Fournit une interface utilisateur cohérente sur différentes versions d'Android.
ConstraintLayout : Permet aux développeurs de créer des mises en page complexes de manière flexible et efficace.
JUnit : Un framework de test utilisé pour les tests unitaires dans l'application.
Espresso : Un framework de test utilisé pour les tests d'interface utilisateur dans l'application.
CardView : Fournit une disposition de style cartes Material Design pour afficher les détails de Pokémon.
Legacy Support Library : Fournit une compatibilité ascendante pour les anciennes versions d'Android.
Glide : Une bibliothèque de chargement et de mise en cache d'images rapide et efficace utilisée pour afficher les images de Pokémon dans l'application.

# API utilisée:

Cette application n'utilise pas d'API externe. Au lieu de cela, elle utilise un fichier JSON (disponible à l'adresse https://raw.githubusercontent.com/Biuni/PokemonGO-Pokedex/master/pokedex.json) pour stocker les informations sur les Pokémon.
Cela permet à l'application de fonctionner hors ligne et sans dépendre d'un service externe.

# Démarrage:

Clonez ou téléchargez le dépôt pour votre application Pokedex.
Ouvrez le projet dans Android Studio.
Exécutez l'application sur un émulateur ou un appareil physique.
La liste des Pokémon devrait être affichée sur l'écran principal.
Utilisez la barre de recherche pour chercher un Pokémon par son nom.
Cliquez sur un Pokémon pour afficher ses détails sur un nouvel écran.

