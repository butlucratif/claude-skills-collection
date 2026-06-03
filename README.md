# 🚀 Claude Skills Collection

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/Skills-14-blue.svg)](#-skills-disponibles)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red.svg)](https://github.com/butlucratif/claude-skills-collection)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

Collection complète de skills pour Claude Code - parfaite pour les développeurs qui veulent optimiser leur workflow avec l'IA.

## 📑 Table des Matières

- [Qu'est-ce qu'un Skill ?](#-quest-ce-quun-skill-)
- [Skills Disponibles](#-skills-disponibles)
- [Installation](#️-installation)
- [Comment Utiliser](#-comment-utiliser)
- [Guide Démarrage Rapide](QUICK-START.md)
- [Exemples Concrets](EXAMPLES.md)
- [Contribuer](CONTRIBUTING.md)

## 📚 Qu'est-ce qu'un Skill ?

Un **skill** est comme un "super-pouvoir" que tu peux donner à Claude pour l'aider à mieux comprendre et exécuter des tâches spécifiques. C'est un guide structuré qui dit à Claude comment approcher certains types de problèmes.

## 🎯 Skills Disponibles

### 🧠 Développement & Architecture

- **brainstorming** - Techniques pour générer et organiser des idées avant de coder
- **writing-plans** - Créer des plans d'implémentation détaillés
- **executing-plans** - Exécuter les plans créés de manière méthodique
- **subagent-driven-development** - Utiliser des sous-agents pour diviser le travail

### ✅ Tests & Qualité

- **test-driven-development** - Approche TDD : écrire les tests avant le code
- **verification-before-completion** - Vérifier que tout fonctionne avant de dire "c'est fini"
- **systematic-debugging** - Méthode systématique pour débugger efficacement

### 🔄 Git & Code Review

- **using-git-worktrees** - Travailler sur plusieurs branches simultanément
- **finishing-a-development-branch** - Finaliser proprement une branche de développement
- **requesting-code-review** - Demander une review de code de manière professionnelle
- **receiving-code-review** - Réagir aux reviews et implémenter les suggestions

### 🤝 Collaboration

- **dispatching-parallel-agents** - Faire travailler plusieurs agents Claude en parallèle
- **using-superpowers** - Guide complet pour utiliser tous ces skills ensemble

### 📝 Documentation

- **writing-skills** - Créer tes propres skills personnalisés

## 🛠️ Installation

### Option 1 : Installation Manuelle

Copie le skill que tu veux dans ton dossier Claude :

```bash
# Créer le dossier skills si nécessaire
mkdir -p ~/.claude/skills

# Copier un skill spécifique
cp -r brainstorming ~/.claude/skills/

# Ou copier tous les skills
cp -r * ~/.claude/skills/
```

### Option 2 : Via Claude Code

Dans Claude Code, tu peux référencer ces skills directement dans tes prompts :

```
/skill brainstorming
```

## 💡 Comment Utiliser

### Exemple 1 : Créer une nouvelle feature avec TDD

```
Je veux créer une nouvelle fonctionnalité de login.
Utilise le skill test-driven-development pour m'aider.
```

### Exemple 2 : Débugger un problème complexe

```
J'ai un bug bizarre où mon API renvoie parfois des données nulles.
Utilise systematic-debugging pour m'aider à trouver la cause.
```

### Exemple 3 : Organiser un projet complexe

```
Je dois créer un système de paiement complet.
Utilise brainstorming puis writing-plans pour structurer ça.
```

## 🎓 Pour les Débutants

Si tu débutes avec Claude Code, commence par ces skills :

1. **using-superpowers** - Comprendre l'écosystème
2. **brainstorming** - Apprendre à structurer tes idées
3. **test-driven-development** - Adopter les bonnes pratiques dès le début
4. **verification-before-completion** - S'assurer que le code est vraiment fini

## 🚀 Skills Avancés

Une fois à l'aise, explore :

1. **subagent-driven-development** - Diviser pour mieux régner
2. **dispatching-parallel-agents** - Accélérer le développement
3. **using-git-worktrees** - Workflow git avancé
4. **writing-skills** - Créer tes propres skills

## 📖 Structure d'un Skill

Chaque skill contient généralement :

- `skill.md` - La documentation principale du skill
- `prompt.md` - Le prompt système qui guide Claude
- Éventuellement des exemples ou ressources additionnelles

## 🤝 Contribuer

Tu as créé un skill utile ? N'hésite pas à contribuer !

1. Fork ce repo
2. Ajoute ton skill dans un nouveau dossier
3. Documente-le clairement
4. Crée une Pull Request

## 📝 Licence

Ces skills sont open-source et libres d'utilisation.

## 🆘 Support

Si tu as des questions :
- Consulte la documentation de chaque skill
- Demande à Claude directement : "Explique-moi comment fonctionne le skill [nom]"

## 🎯 Prochaines Étapes

1. Clone ce repo
2. Explore les skills qui t'intéressent
3. Teste-les dans tes projets
4. Adapte-les à tes besoins
5. Partage tes propres skills !

---

**Made with ❤️ for developers who want to supercharge their workflow with AI**
