# Lignes directrices pour contribuer

*Les pulls requests, signalement de bug et toutes autres formes de contributions sont les bienvenues et hautement recommendés!*

> **Ce guide a pour but de donner des normes pour l'ensemble du projet afin de le rendre plus simple à lire et contribuer**

## 📖 Code de conduite
Merci de lire notre [Code de conduite](https://github.com/Margouta/PluginOpenMC/blob/main/CONTRIBUTING.md) pour assurer un moment convivial à tout les contributeurs

## 📥 Ouvrir une Issue
Avant de créer une issue, soyez sur d'avoir la version la plus récent du plugin

## 🪲 Signalement de bugs et autres problèmes
La meilleur façon de contribuer sans coder et de partager les bugs
Si vous en rencontrez un, nous apprecirons un rapport bien écris ❤️

Avant d'envoyer un ticket soyez sur de:
- **Ne pas avoir créer un doublons!**
- **Utiliser des reactions**, si vous rencontrez le même problème qu'un ticket existant, utiliser une reaction 👍 au lieu d'écrire un commentaire (sauf si votre commentaire ajoute des détails)
- **Remplissez completement le template**, le template as été écris pour simplifier le travail des contributeurs, merci de leurs facilités la vie

## 🔁 Envoyer une Pull Request
Avant de forker le repo et créer une pull request, assurez vous que les modifications que vous souhaitez apporter ne sont pas déjà en cours de développement. Dans ce cas, voyez avec le premier auteur pour collaborer !

*Note: Toutes les contributions auront la license GPL 3.0*

- **Plus petit, mieux c'est**. Envoyer **une seule** pull request par bugfix ou fonctionnalité, - **Ne pas** changer du code qui n'est pas lié à vitre changement, C'est mieux de faire plein de petits PR plutot qu'une grandes, Les grandes pull requests mettent du temps à être approuvé et peuvent être rejetté pour cette raison.
- **Soyez coordinée**, pour éviter de travailler sur la même choses en parallèle coordinée vous (en publique) sur qui écris quoi
- **Suivez les conventions** de code existantes, suivre les conventions permets d'avoir un code plus facile à lire et corrigé
- **[Corriger tout les conflits](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)**
- Quand vous ecrivez des commentaires, écrivez des phrases construites, sans argots

## 📝 Ecrire un message de commit
S'il vous plaît, [écrivez des bons messages de commits](https://cbea.ms/git-commit/)
1. Limiter le sujet à 50 charactères
2. Utilsez l'imperatif (example: "Corrige un bug avec les pommes")
3. Ajouter un tag si possible ([Docs], [Bug], [Features]...)
4. Ecrivez des descriptions complètes
5. Ne dépassez pas les 72 charactères en largeurs

aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa (72 chars)

```
[BUG] Corrige le bug avec les pommes

Ecrivez une descriptions complètes, séparez les paragraphes par une
lignes blanches, expliquer le problème, avec du contexte si nécessaires,
focusez vous sur comment vous l'avez résolue, l'objectif est d'écrire
un patch que les reviewers et le futur vous pourrez lires et expliquer

Notez les issues qui sont résolue via ce patch
Résous: #123
Voir aussi: #456, #789
```

## ✅ Examiner le code
- **Examinez le code, pas l'auteur**, Donnez des critiques constructives

## 💅 Style de codes
Les conventions, d'après [cette page](https://www.oracle.com/java/technologies/javase/codeconventions-namingconventions.html) sur le site d'Oracle, sont les suivates :  
Les noms doivent être en anglais, peu importe la chose nommée.  
| Chose nommée | Règle | Exemple |
|--------------|-------|---------|
| Package | Toujours en miniscules et tous les mots sont collés sans caractère entre (pas d'`_`). Le nom doit être simple et sans caractères spéciaux (uniquement les caractères ASCII, donc pas d'accents). Le nom du package doit au possible rester un seul mot. | `fr.communaywen.commands` |
| Classe, Interfaces, Enums, Records, Annotations | Toujours en PascalCase. Utilisez uniquement des noms. Évitez les acronymes ou abréviations. | `class SpawnManager;` |
| Methodes | Son nom commence par un verbe. En `camelCase` | `getInstance()` `clone()` |
| Variables | Toujous en `camelCase`, évitez les abréviations et les noms raccourcis comme `nbr`. Pas d'`_` ou de `$` au début. L'utililité de la variable devrait être devinable en regardant le nom. | `int numberOfPlayers` `String playerName` |
| Constantes et membres d'enums | Les constantes dont la déclaration commence par `static final` sont nommées en UPPER_SNAKE_CASE, avec comme les variables, un nom qui décrit clairement leur utilité. | `static final int MIN_WIDTH = 4;` |
