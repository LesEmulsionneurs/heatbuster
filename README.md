# Heatbuster

Heatbuster est une application web développée par **Les Émulsionneurs** pour le suivi thermique. Ce projet permet de récupérer et visualiser en temps réel les données issues de capteurs de température et d'humidité via une interface ergonomique et responsive.

## Fonctionnalités

- **Connexion Bluetooth**  
  Sélection et connexion à des appareils compatibles pour la récupération des données.

- **Visualisation Interactive**  
  Affichage dynamique des courbes de température et d'humidité grâce à la bibliothèque [Dygraphs](http://dygraphs.com/).

- **Interface Responsive et Moderne**  
  Conception basée sur [Bootstrap](https://getbootstrap.com/), adaptée aux écrans de bureau, tablettes et mobiles.

- **Export CSV**  
  Sauvegarde des données récupérées au format CSV pour une analyse ultérieure.

- **Feedback Utilisateur**  
  Indicateurs visuels (spinners, messages) pour informer l’utilisateur sur l’état de la connexion et des actions réalisées.

## Prérequis

- Un navigateur web moderne supportant les fonctionnalités Bluetooth et HTML5.
- Une connexion Internet (pour charger les ressources externes telles que Bootstrap et Dygraphs).

## Installation et Déploiement

1. **Cloner le dépôt**  
   Ouvrez votre terminal et clonez le dépôt :
   ```bash
   git clone https://github.com/LesEmulsionneurs/heatbuster.git
   ```
2. **Déployer la page web**  
   Vous pouvez déployer les fichiers sur un serveur web ou simplement ouvrir le fichier `index.html` dans votre navigateur.

## Utilisation

- **Connexion**  
  Cliquez sur le bouton **"Connecter l’appareil Bluetooth"** pour établir la connexion avec le capteur.

- **Configuration**  
  Utilisez le formulaire pour définir le filtre du nom Bluetooth et le nombre d'échantillons à récupérer.

- **Visualisation**  
  Les données sont affichées sous forme de graphique interactif (avec zoom, légende et sélection).

- **Export CSV**  
  Cliquez sur **"Sauvegarder en CSV"** pour exporter les données en format CSV.

## Contribution

Les contributions sont les bienvenues !  
Si vous souhaitez améliorer le projet, merci d’ouvrir une issue ou un pull request.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE.md) pour plus d'informations.

## Crédits

- **Les Émulsionneurs** – Organisation responsable du projet ERASMUS+ JEDI Track.
- [Dygraphs](http://dygraphs.com/) – Bibliothèque utilisée pour l’affichage des graphiques.
- [Bootstrap](https://getbootstrap.com/) – Framework pour une mise en page responsive et moderne.