# Dépenses Tracker — site

Site vitrine de **Dépenses Tracker**, une application Android de suivi des dépenses en dirhams marocains (MAD), qui fonctionne entièrement hors ligne.

🌐 **Site** : https://mobenlamine.github.io/depenses-tracker-site/
🔒 **Politique de confidentialité** : https://mobenlamine.github.io/depenses-tracker-site/confidentialite.html

---

## À propos de l'application

Dépenses Tracker vous aide à savoir où part votre argent, sans compte, sans serveur et sans publicité.

- **Suivi en MAD** : enregistrez vos dépenses et vos revenus en dirhams.
- **Budgets intelligents** : une alerte à 80 % du budget, une alerte au dépassement, le reste à dépenser par jour et une projection de fin de mois.
- **Scan de tickets** : la reconnaissance du texte se fait sur l'appareil, grâce à ML Kit.
- **Assistant IA local** : un modèle installé sur le téléphone répond à vos questions sur vos dépenses, sans rien envoyer dehors.
- **Exports** : rapports et exports CSV ou PDF, générés sur le téléphone.
- **Verrouillage biométrique** : empreinte ou code de l'appareil.
- **Sauvegarde optionnelle** : vers votre propre Google Drive, si vous le souhaitez.

Application disponible sur Android. Publication sur Google Play à venir.

## Confidentialité

Vos données restent sur votre téléphone. L'application ne crée pas de compte et n'envoie aucune donnée à un serveur, à l'exception de la sauvegarde Google Drive, qui reste optionnelle et vers votre propre espace Drive. Le détail est dans la [politique de confidentialité](https://mobenlamine.github.io/depenses-tracker-site/confidentialite.html).

## Le site

Le site est un site statique : HTML, CSS et JavaScript, sans étape de build ni dépendance à installer.

```
.
├── index.html          # page d'accueil
├── confidentialite.html # politique de confidentialité (français et arabe)
├── assets/             # logos, icônes et images
├── robots.txt
└── sitemap.xml
```

La démonstration de la page d'accueil tourne dans le navigateur, avec des données d'exemple. Aucune donnée réelle n'est envoyée.

### Lancer en local

```bash
git clone https://github.com/MoBENLAMINE/depenses-tracker-site.git
cd depenses-tracker-site
python3 -m http.server 8000
```

Ouvrez ensuite http://localhost:8000 dans votre navigateur.

### Publication

Le site est publié avec **GitHub Pages**, depuis la branche `main`, à la racine du dépôt. Chaque `push` sur `main` met le site à jour en quelques minutes.

## Marques

Google Play et le logo Google Play sont des marques de Google LLC.
