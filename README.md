# MES-TACHES_quotidienne
Conçue pour simplifier le quotidien, Mes Tâches vous permet de planifier ce que vous avez à faire aujourd'hui comme dans les semaines à venir, avec des catégories claires, des niveaux de priorité et des notes pour ne rien oublier. L'application veille pour vous : une alarme se déclenche au moment voulu 

# Mes Tâches

Application web personnelle de gestion de tâches quotidiennes, pensée pour planifier, organiser et ne rien oublier au quotidien. Le tout dans un seul fichier HTML autonome.

## Aperçu

Mes Tâches vous aide à planifier vos journées et garder le rythme grâce à des rappels sonores. Travail, ministère, santé ou maison, chaque tâche trouve sa place dans une catégorie, avec un niveau de priorité et un horaire de rappel. L'application veille pour vous : une alarme se déclenche au moment voulu et tout votre historique reste accessible d'un simple geste.

## Fonctionnalités

- **Planification multi-jours** : ajoutez des tâches pour aujourd'hui, demain ou n'importe quelle date à venir
- **Six catégories** : Travail, Perso, Études, Santé, Maison et Ministère, chacune avec son icône et sa couleur
- **Trois niveaux de priorité** : basse (vert), moyenne (jaune), haute (rouge)
- **Rappels sonores** : choisissez une heure pour chaque tâche, l'alarme sonne en boucle jusqu'à ce que vous l'arrêtiez
- **Notifications du navigateur** : recevez une alerte système même quand l'onglet n'est pas au premier plan
- **Notes attachées** : ajoutez des détails, un lieu ou un lien à chaque tâche
- **Modification facile** : un clic sur le crayon pour ajuster n'importe quel champ d'une tâche existante
- **Navigation rapide** : flèches gauche/droite pour changer de jour, calendrier intégré pour sauter à une date précise
- **Filtres intelligents** : basculez entre "À faire" et "Terminé", filtrez par catégorie
- **Persistance automatique** : tout est sauvegardé dans le navigateur, rien ne se perd au rafraîchissement
- **Responsive** : interface optimisée pour mobile et bureau, même fichier dans les deux cas
- **Suivi de progression** : barre de progression visuelle et compteur de tâches terminées par jour

## Démarrage rapide

Pas besoin d'installation, de serveur ou de compilation. Téléchargez le fichier et ouvrez-le.

```bash
git clone https://github.com/votre-utilisateur/mes-taches.git
cd mes-taches
```

Puis double-cliquez sur `mes-taches.html` ou ouvrez-le dans votre navigateur préféré (Chrome, Firefox, Edge, Safari).

### Mise en ligne

Pour héberger l'application sur le web, déposez simplement le fichier sur n'importe quel hébergeur statique : GitHub Pages, Netlify, Vercel, ou un serveur web classique.

## Utilisation

### Ajouter une tâche

1. Cliquez sur **Ajouter une tâche**
2. Renseignez le titre
3. Choisissez la date, la catégorie et la priorité
4. Définissez un rappel si souhaité
5. Ajoutez une note pour des détails supplémentaires
6. Validez avec **Ajouter la tâche**

### Activer les rappels

Lorsque vous créez votre première tâche avec un rappel, l'application vous demande la permission d'envoyer des notifications. Acceptez pour recevoir l'alerte au moment prévu, même si l'onglet est en arrière-plan.

L'alarme sonne en continu jusqu'à ce que vous fermiez la bannière rouge ou cochiez la tâche comme terminée.

### Naviguer entre les jours

- **Flèches gauche/droite** : reculer ou avancer d'un jour
- **Cliquer sur la date** : ouvrir le calendrier pour sauter à n'importe quelle date
- **Bouton "Revenir à aujourd'hui"** : apparaît automatiquement quand vous êtes sur un autre jour

## Compatibilité

Compatible avec tous les navigateurs modernes :

- Chrome / Edge (version 90+)
- Firefox (version 88+)
- Safari (version 14+)

Les notifications système nécessitent que l'onglet du navigateur reste ouvert. Sur certains navigateurs, l'audio peut nécessiter une première interaction de l'utilisateur (un clic) avant de fonctionner, conformément aux politiques de sécurité du Web.

## Stockage des données

Toutes vos tâches sont enregistrées localement dans le `localStorage` du navigateur, sous la clé `mes-taches-data`. Aucune donnée n'est envoyée à un serveur externe. Vos informations restent entièrement privées et accessibles uniquement depuis votre appareil.

Pour effacer les données, videz le stockage local du site dans les paramètres de votre navigateur.

## Technologies

- **HTML5 / CSS3 / JavaScript vanilla** : aucune dépendance d'exécution
- **Tailwind CSS** : compilé en statique et intégré dans le fichier
- **Lucide Icons** : icônes vectorielles via CDN
- **Web Audio API** : génération du son d'alarme sans fichier externe
- **Notifications API** : alertes système du navigateur
- **localStorage** : persistance des données

## Structure du projet

```
mes-taches/
├── mes-taches.html    # Application complète, autonome
└── README.md          # Ce fichier
```

Tout est contenu dans un seul fichier : HTML, CSS, JavaScript, images encodées en base64 (logo, photo de profil, icône d'alarme et arrière-plan).

## Personnalisation

Pour adapter l'application à vos besoins, vous pouvez modifier directement les constantes en haut du script :

- `CATEGORIES` : ajouter, retirer ou renommer des catégories
- `PRIORITIES` : modifier les niveaux et leurs couleurs
- `USER_PHOTO` : remplacer la photo de profil
- `LOGO_ICON` : changer le logo de l'application

## Auteur

Application développée pour un usage personnel, fonctionnelle hors ligne et facile à partager.

## Licence

Libre d'utilisation pour un usage personnel et éducatif.
