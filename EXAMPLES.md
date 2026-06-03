# 💡 Exemples Concrets d'Utilisation

## Scénario 1 : Créer une API REST

### Situation
Tu dois créer une API REST pour gérer des utilisateurs (CRUD complet).

### Étapes avec les Skills

**1. Phase de Brainstorming**
```
Je dois créer une API REST pour gérer des utilisateurs.
Utilise le skill brainstorming pour m'aider à :
- Définir les endpoints nécessaires
- Penser à la structure de données
- Identifier les cas d'usage
```

**2. Écrire le Plan**
```
Maintenant, utilise writing-plans pour créer un plan d'implémentation détaillé
pour cette API utilisateurs.
```

**3. TDD pour chaque endpoint**
```
Utilise test-driven-development pour implémenter le endpoint POST /users.
Commence par les tests.
```

**4. Vérification finale**
```
Utilise verification-before-completion pour vérifier que :
- Tous les tests passent
- La documentation est à jour
- Le code est propre
```

## Scénario 2 : Débugger un Bug Complexe

### Situation
Ton app plante de manière aléatoire en production, mais jamais en dev.

### Utilisation du Skill

```
J'ai un bug en production :
- L'app plante aléatoirement
- Ça n'arrive jamais en dev
- Les logs montrent [ton erreur]

Utilise systematic-debugging pour m'aider à :
1. Identifier les hypothèses
2. Concevoir des expériences pour tester chaque hypothèse
3. Isoler la cause racine
```

## Scénario 3 : Travailler sur Plusieurs Features

### Situation
Tu dois travailler sur 2 features en parallèle : un système de login ET un système de notifications.

### Stratégie

**1. Git Worktrees**
```
Utilise using-git-worktrees pour m'aider à setup deux espaces de travail :
- feature/login
- feature/notifications
```

**2. Développement Parallèle**
```
Utilise dispatching-parallel-agents pour :
- Agent 1 : Développer le système de login
- Agent 2 : Développer le système de notifications
```

## Scénario 4 : Code Review Pro

### Situation
Tu as fini une grosse feature et tu veux une review de qualité.

### Process

**1. Préparer la Review**
```
Utilise requesting-code-review pour préparer ma PR :
- Résumer les changements
- Créer une checklist de test
- Identifier les points sensibles
```

**2. Recevoir et Traiter les Feedbacks**
```
J'ai reçu ces commentaires sur ma PR : [liste les commentaires]

Utilise receiving-code-review pour m'aider à :
- Prioriser les changements
- Implémenter les suggestions
- Répondre aux reviewers
```

## Scénario 5 : Créer un Nouveau Projet de A à Z

### Situation
Tu commences un projet complètement nouveau : une app de gestion de budget.

### Workflow Complet

**1. Brainstorming Initial**
```
Je veux créer une app de gestion de budget perso.
Utilise brainstorming pour explorer :
- Les fonctionnalités principales
- L'architecture technique
- Les technologies à utiliser
```

**2. Plan Détaillé**
```
Utilise writing-plans pour créer un plan en sprints :
- Sprint 1 : Setup & Auth
- Sprint 2 : Tracking des dépenses
- Sprint 3 : Statistiques et reporting
```

**3. Développement avec Sous-Agents**
```
Utilise subagent-driven-development pour organiser le travail :
- Agent Architecture : Définir la structure
- Agent Backend : Implémenter l'API
- Agent Frontend : Créer l'UI
- Agent Tests : Écrire les tests
```

**4. TDD pour chaque composant**
```
Pour chaque feature, utilise test-driven-development
```

**5. Vérifications continues**
```
À chaque fin de sprint, utilise verification-before-completion
```

## Scénario 6 : Refactoring d'un Vieux Code

### Situation
Tu hérites d'un code legacy sans tests, plein de bugs.

### Approche

**1. Comprendre le Code**
```
Utilise systematic-debugging pour :
- Tracer le flux d'exécution
- Identifier les points critiques
- Documenter le comportement actuel
```

**2. Ajouter des Tests**
```
Utilise test-driven-development en mode "characterization tests" :
- Écrire des tests qui capturent le comportement actuel
- Même si ce comportement est bugué
```

**3. Refactoring Progressif**
```
Utilise executing-plans pour :
- Refactorer par petits pas
- Vérifier les tests à chaque étape
- Améliorer progressivement
```

## Tips Pro

### Combiner les Skills

Les skills sont puissants quand on les combine :

```
1. brainstorming → Vision globale
2. writing-plans → Structure détaillée
3. test-driven-development → Implémentation solide
4. systematic-debugging → Résolution de problèmes
5. verification-before-completion → Qualité finale
```

### Adapter à Ton Style

N'hésite pas à adapter :
```
Au lieu de : "Utilise test-driven-development"
Dis : "Inspire-toi de test-driven-development mais adapte pour React Native"
```

### Créer Tes Propres Skills

```
Utilise writing-skills pour créer ton propre skill basé sur
ton workflow personnel ou les spécificités de ton équipe.
```

## Questions Fréquentes

**Q : Dois-je utiliser tous les skills en même temps ?**
Non ! Commence par 2-3 skills pertinents pour ta tâche actuelle.

**Q : Un skill peut remplacer un autre ?**
Certains se complètent, d'autres sont alternatifs. Expérimente !

**Q : Comment savoir quel skill utiliser ?**
Demande à Claude : "Quel skill serait le plus adapté pour [ta tâche] ?"

## Next Steps

Maintenant que tu as vu des exemples :
1. Choisis un scénario proche de ton besoin
2. Adapte les commandes à ton contexte
3. Expérimente et itère
4. Partage tes propres patterns !

Happy coding! 🚀
