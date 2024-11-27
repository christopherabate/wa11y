# Wa11y
**[Un jeu de cartes sur l'accessibilité web](https://christopherabate.github.io/wa11y/)**

## Objectif du jeu
Le but est de devenir le joueur ayant le moins de critères invalides à la fin du jeu, tout en progressant à travers les différentes étapes d'un projet de développement web. Les participants doivent utiliser des outils et collaborer pour surmonter les critères d'accessibilité, en prenant en compte les responsabilités spécifiques à leur rôle.

2 à 7 joueurs.

---

## Matériel

### 1. Cartes Déficience (7 cartes)
- **Visuel :** Difficultés à percevoir les informations visuelles, comprenant des personnes aveugles, malvoyantes ou daltoniennes.
- **Auditif :** Incapacité à entendre ou comprendre le contenu audio, comprenant des personnes sourdes ou malentendantes.
- **Moteur :** Limitations dans l'utilisation des membres, pouvant affecter l'interaction avec des dispositifs comme la souris ou le clavier.
- **Psychologique :** Troubles mentaux qui peuvent affecter la concentration et la compréhension.
- **Intellectuel :** Difficultés à comprendre l'information et les instructions, comprenant des handicaps cognitifs ou d'apprentissage.
- **Dyslexie :** Inclut des difficultés spécifiques comme la dyslexie, la dyscalculie ou la dyspraxie, affectant la lecture, l'écriture ou la coordination.
- **Maladie chronique :** Conditions de santé chroniques ou invalidantes qui peuvent affecter l'accès à l'information ou l'interaction avec le contenu numérique.

### 2. Cartes Outils (9 cartes)
- **Contrôleur de syntaxe :** Identifie et corrige les erreurs dans un éditeur de code.
- **Tests continus :** Évaluation continue de l'accessibilité à chaque version publiée.
- **Surveillance :** Suivi des changements d'accessibilité par périodes définies.
- **Contrôleur de contraste :** Analyse le contraste entre le texte et l'arrière-plan pour garantir une lisibilité optimale.
- **Extension de navigateur :** Outils intégrés dans les navigateurs pour aider la repérage d'un ou plusieurs critères non-conformes.
- **Marque-page scripté :** (ou bookmarklet) Comme une extension de navigateur, aide au repérages des critères non-conformes.
- **Inspecteur de code :** Examine le code source d'une page pour identifier les problèmes d'accessibilité.
- **Clavier :** Navigation sans souris pour valider le fonctionnement, l'ordre de prise en compte et la visiblité des composants.
- **Technologie d’assistance :** Divers outils (lecteurs d’écran, dispositifs de pointage alternatifs, etc.) permettant de palier à une situation de handicap numérique.

### 3. Cartes Critères (14 cartes)
- **Contraste :** Le contraste entre le texte et l'arrière-plan doit être suffisant pour garantir la lisibilité (WCAG 1.4.3).
- **Nom, rôle, et valeur :** Les éléments interactifs doivent avoir des noms, rôles et valeurs appropriés pour être accessibles via les technologies d'assistance (WCAG 4.1.2).
- **Information et relations :** La structure du contenu doit être correcte, permettant aux utilisateurs de comprendre les relations entre les éléments (WCAG 1.3.1).
- **Contenu non-textuel :** Les images et autres contenus non-textuels doivent avoir des descriptions alternatives (WCAG 1.1.1).
- **Ordre de focus :** L'ordre dans lequel les éléments reçoivent le focus doit suivre une séquence logique pour une navigation fluide (WCAG 2.4.3).
- **Accessibilité clavier :** Tous les éléments doivent être accessibles via le clavier sans nécessiter l'usage de la souris (WCAG 2.1.1).
- **Visibilité du focus :** Le focus des éléments interactifs doit être clairement visible pour les utilisateurs (WCAG 2.4.7).
- **Contraste du contenu non-textuel :** Les images et graphiques doivent respecter les normes de contraste pour garantir leur lisibilité (WCAG 1.4.11).
- **Utilisation de la couleur :** Les informations ne doivent pas être véhiculées uniquement par la couleur (WCAG 1.4.1).
- **Ordre séquentiel logique :** Le contenu doit être présenté dans un ordre qui facilite la compréhension (WCAG 3.2.1).
- **Étiquettes ou instructions :** Les formulaires doivent contenir des étiquettes et des instructions claires pour chaque champ (WCAG 3.3.2).
- **Contournement des blocs :** Les utilisateurs doivent pouvoir contourner les blocs répétitifs pour naviguer plus rapidement (WCAG 2.4.1).
- **Titre de page :** Chaque page doit avoir un titre clair décrivant son contenu (WCAG 2.4.2).
- **Langue de la page :** La langue principale de la page doit être spécifiée pour aider les utilisateurs des technologies d'assistance (WCAG 3.1.1).

### 4. Cartes Rôles (7 cartes)
- **Manager :** Peut échanger un de ses critères contre un autre tiré du deck lors de l'audit.
- **Project Manager :** // capacité à définir
- **Product Owner :** // capacité à définir
- **Designer :** Peut se débarrasser à tout moment des critères "Contraste" et "Utilisation de la couleur".
- **Développeur :** Peut corriger un critère sans outil lors de l'audit, "Nom, rôle, et valeur" ou "Information et relations".
- **Testeur :** Tire une carte outil au début du jeu.
- **Expert :** Peut regarder la main d’un autre joueur avant son tour.

### 5. Plateau de Jeu
Le plateau représente les étapes d’un projet de développement web, de la conception à la mise en production.

1. **Conception**
   - **Description** : Création de l’interface utilisateur avec une attention particulière à l’accessibilité visuelle (contraste, couleurs).
   - **Critères typiques** : Contraste, Utilisation de la couleur.

2. **Prototypage**
   - **Description** : Création de maquettes fonctionnelles en veillant à la structure logique des informations.
   - **Critères typiques** : Information et relations, Ordre séquentiel logique.

3. **Développement**
   - **Description** : Programmation de l’interface utilisateur, s'assurant que tous les éléments sont accessibles via le clavier et bien structurés.
   - **Critères typiques** : Accessibilité clavier, Nom, rôle, et valeur.

5. **Tests**
   - **Description** : Évaluation de l’accessibilité à l’aide d’outils et de technologies d’assistance.
   - **Critères typiques** : Ordre de focus, Visibilité du focus.

6. **Contribution**
   - **Description** : Validation finale des critères d’accessibilité avant la mise en production.
   - **Critères typiques** : Contenu non-textuel, Contraste du contenu non-textuel.

7. **Mise en Production**
   - **Description** : Publication du site en ligne, avec tous les critères d’accessibilité respectés.
   - **Critères typiques** : Titre de page, Langue de la page.

8. **Audit accessibilité**
   - **Description** : Dernière phase pour prendre en compte les critères d'accessibilité restants.

8. **Déclaration accessibilité**
   - **Description** : Analyse détaillé d'un échantillon représentation du site ou du service.

---

## Règles du jeu

### 1. Mise en place
- Les cartes Outils et Critères sont placées au centre du plateau de jeu.
- Chaque joueur tire un rôle au hasard et la pose devant lui face visible.

### 2. Tour de jeu
- Au début de chaque tour de jeu, les joueurs tirent une carte Critère.
- Ils doivent gérer cette carte en utilisant une des actions suivantes :
  - **Utiliser un Outil :** Si le joueur pense que l'outil est approprié, il peut justifier son choix, poser le Critère dans les "Done", l'outil dans la "Forge" et avancer d'une case.
  - **Tirer un Outil :** Le joueur peut choisir de tirer un outil et l’utiliser.
  - **Prendre un Outil dans la Forge :** Le joueur peut prendre un outil déjà utilisé (dans la "Forge"), mais doit attendre son tour suivant pour l’utiliser et avancer d'une case.
  - **Demander de l’aide à un Expert :** Si un joueur ne trouve pas l’outil nécessaire, il peut demander l’aide d’un autre joueur en échange d’une avance d’une case.
- Le choix est donné aux autres joueurs d'accepter ou non la justification. En cas de contestation, une justification inverse devra être proposée par le ou les autres joueurs.

### 3. Avant-dernière étape – L'audit
- Le joueur peut continuer à tirer des cartes outils ou demander l’avis d’experts sans être obligé d’avancer ou de tirer une carte critère.

### 4. Dernière étape – La déclaration
- Le joueur tire une carte de Déficience qu'il garde cachée.
- Lorsque tous les joueurs atteignent cette étape, ils révèlent leur carte Déficience et les cartes Critère qu’ils possèdent.
- Si le joueur estime que ses cartes Critères ne sont pas bloquants au regard de sa déficience, il doit le justifier. Tout comme à chaque tour, le choix est donné aux autres joueurs d'accepter ou non la justification.

### 5. Gagnant
- Le joueur ayant le moins de Critères bloquants à la fin du jeu gagne.

---

## Conclusion & Twist final
Ce jeu vise à sensibiliser aux problèmes d'accessibilité web tout en favorisant la collaboration et l'échange d'idées.

Le twist : 
- A la fin de la partie, il y a des perdants. Ce sont les utilisateurs.
- Les joueurs sont partis du principe qu'il fallait jouer les uns contre les autres. Or, en coopération il est possible que le produit final ne souffre d'aucun point bloquant et c'est tout le monde qui gagne la partie.
