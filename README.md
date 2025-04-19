# cours-de-veille-technologique

Projet réalisé dans le cadre du cours de veille technologique de Nicolas – mars 2025

## Idées de projets

1. Créer un serveur d’IA ainsi qu'une interface utilisateur (UI) pour le faire fonctionner.
2. Créer un bot Discord pour jouer de la musique.
3. Faire une preuve de concept en Python avec le moteur de jeu Ren'Py.
4. Apprendre à utiliser WordPress et développer une preuve de concept.
5. Tenter de faire fonctionner un programme de feuille de temps dans Microsoft Excel.

## Projet sélectionné

- Créer un serveur d’IA avec une interface utilisateur pour l’exploiter.

### Pourquoi ce choix ?

J'ai choisi ce sujet parce qu’il pourrait avoir des applications pratiques dans mon milieu de stage. J’ai aussi trouvé plusieurs méthodes faciles à suivre pour le mettre en place. L’intelligence artificielle prend de plus en plus de place dans notre travail de programmation, donc je trouve pertinent de m’y intéresser pour comprendre son fonctionnement.

### Ressources nécessaires

- **Ollama** : pour fournir des modèles d’IA open source et un environnement d'exécution.
- **Open WebUI** : pour permettre une utilisation sur une page web avec une interface utilisateur et une gestion graphique côté administrateur (également open source).
- En bonus, je souhaiterais aussi faire fonctionner **Stable Diffusion** pour la génération d’images.

### Défis à prévoir

- Configuration des ports pour rendre le serveur accessible par Internet, en tenant compte que ma connexion passe directement par la box.
- La puissance graphique nécessaire : je ne sais pas dans quelle mesure ma carte graphique (RTX 4060) pourra répondre aux besoins, ce qui pourrait ralentir les réponses de l’IA.
- Les défis logiciels seront liés aux restrictions et à la configuration des différents modèles d’IA.

---

## Étape 3 – Présentation du projet

1. **Création d’un environnement web de chat IA**
2. **Objectif du projet** : créer un serveur web où les utilisateurs pourront interagir avec des modèles d’IA pour poser des questions ou effectuer des tâches.

> Le sujet de l’IA m’intéresse depuis un moment. Après une discussion avec mon directeur de stage, il s’est montré intéressé par l’idée d’une IA locale, indépendante des grandes entreprises qui collectent des données. J’ai donc pensé développer ce projet pour lui proposer une implémentation d’entreprise.

3. Rappel des idées de départ :
   - Créer un serveur d’IA avec une interface utilisateur.
   - Créer un bot Discord musical.
   - Preuve de concept en Python avec Ren'Py.
   - Apprentissage de WordPress avec une preuve de concept.
   - Feuille de temps dans Excel.

Parmi ces 5 projets, j’ai choisi celui qui pouvait servir dans le cadre de mon stage. Cela me permettra d’y travailler pendant mes heures de travail. Deux projets étaient adaptés à un usage en entreprise : la feuille de temps Excel et l’IA. Mais comme nous avons déjà vu Excel dans un autre cours, je préfère me concentrer sur l’IA.

4. **Objectif principal** : avoir une interface web pour le serveur et les IA en backend. Cela sera fait avec OpenUI. Ensuite, j’utiliserai Ollama pour accéder aux différents modèles d’IA. Enfin, j’aimerais connecter Stable Diffusion pour permettre la génération d’images.

5. **Plan de réalisation** :
   - Installer Ollama et tester les modèles d’IA.
   - Utiliser OpenUI pour configurer l’interface administrateur.
   - Configurer la connexion entre OpenUI et Stable Diffusion pour que les IA textuelles puissent générer des images.
   - Configurer le réseau pour rendre le serveur accessible publiquement.

6. **Outils utilisés** : Ollama, OpenUI, Stable Diffusion, Ubuntu. J’aurai besoin de plusieurs modèles d’IA disponibles dans la librairie Ollama. La configuration des IA se fera dans les fichiers LLM.

7. **Résultat attendu** : un prototype fonctionnel avec une interface utilisateur et les fonctionnalités d’OpenUI. Des lenteurs peuvent survenir si le projet demande trop de ressources, car mon setup personnel n’est peut-être pas assez puissant.
