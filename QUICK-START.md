# ⚡ Guide de Démarrage Rapide

## Installation en 2 minutes

```bash
# 1. Clone le repo
git clone https://github.com/[TON-USERNAME]/claude-skills-collection.git

# 2. Copie les skills dans ton Claude
cp -r claude-skills-collection/* ~/.claude/skills/

# 3. Redémarre Claude Code
```

C'est tout ! 🎉

## Premiers Pas

### 1️⃣ Ton Premier Skill : Brainstorming

Essaye ça dans Claude :

```
Je veux créer une app de todo list.
Utilise le skill brainstorming pour m'aider à structurer mes idées.
```

### 2️⃣ Apprendre le TDD

```
Montre-moi comment écrire un test pour une fonction qui valide un email.
Utilise test-driven-development.
```

### 3️⃣ Débugger Comme un Pro

```
J'ai ce bug : [décris ton bug]
Utilise systematic-debugging pour m'aider.
```

## Commandes Utiles

### Lister tes skills installés
```bash
ls ~/.claude/skills/
```

### Voir le contenu d'un skill
```bash
cat ~/.claude/skills/brainstorming/skill.md
```

### Mettre à jour les skills
```bash
cd claude-skills-collection
git pull
cp -r * ~/.claude/skills/
```

## Tips & Tricks

### ✅ DO
- Lis la doc d'un skill avant de l'utiliser
- Combine plusieurs skills pour des tâches complexes
- Adapte les skills à ton workflow

### ❌ DON'T
- N'utilise pas tous les skills en même temps au début
- Ne modifie pas les skills originaux (crée des copies)
- N'oublie pas de vérifier les résultats

## Workflow Recommandé

1. **Planification** → `brainstorming` + `writing-plans`
2. **Développement** → `test-driven-development`
3. **Debug** → `systematic-debugging`
4. **Review** → `requesting-code-review`
5. **Finalisation** → `verification-before-completion`

## Besoin d'Aide ?

Demande directement à Claude :
```
Peux-tu m'expliquer comment utiliser le skill [nom] ?
```

## Next Level

Une fois à l'aise :
- Explore `subagent-driven-development`
- Essaye `dispatching-parallel-agents`
- Crée tes propres skills avec `writing-skills`

Happy coding! 🚀
