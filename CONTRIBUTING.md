# 🤝 Guide de Contribution

Merci de vouloir contribuer ! Ce repo est fait pour grandir avec la communauté.

## Comment Contribuer

### 1. Améliorer un Skill Existant

Si tu as trouvé un bug ou une amélioration :

```bash
# 1. Fork le repo
# 2. Crée une branche
git checkout -b improve/systematic-debugging

# 3. Fais tes modifications
# 4. Commit
git commit -m "docs: améliore les exemples de systematic-debugging"

# 5. Push et crée une PR
git push origin improve/systematic-debugging
```

### 2. Créer un Nouveau Skill

Tu as un workflow qui marche bien ? Partage-le !

#### Structure d'un Skill

```
mon-skill/
├── SKILL.md           # Documentation principale (obligatoire)
├── prompt.md          # Prompt système pour Claude (optionnel)
├── examples/          # Exemples d'utilisation (recommandé)
└── resources/         # Fichiers additionnels (optionnel)
```

#### Template de SKILL.md

```markdown
# Nom du Skill

## Description Courte
Une phrase qui décrit le skill.

## Quand l'Utiliser
- Situation 1
- Situation 2

## Comment l'Utiliser

### Commande de Base
\```
[Exemple de commande]
\```

### Exemple Complet
[Scénario détaillé]

## Tips & Tricks
[Conseils pratiques]

## Voir Aussi
- [Autres skills connexes]
```

#### Checklist avant de Soumettre

- [ ] La documentation est claire
- [ ] Au moins 2 exemples d'utilisation
- [ ] Testé avec Claude Code
- [ ] Pas de typos
- [ ] Respecte le style du repo

### 3. Corriger la Documentation

Typos, exemples manquants, clarifications... tout est bienvenu !

```bash
git checkout -b docs/fix-typo-readme
# Fais tes corrections
git commit -m "docs: corrige typo dans README"
git push origin docs/fix-typo-readme
```

## Standards de Code

### Commits

Utilise [Conventional Commits](https://www.conventionalcommits.org/) :

- `feat:` - Nouveau skill ou fonctionnalité
- `fix:` - Correction de bug
- `docs:` - Documentation seulement
- `refactor:` - Refactoring sans changement de fonctionnalité
- `test:` - Ajout de tests
- `chore:` - Maintenance

**Exemples :**
```
feat: add api-design skill
fix: correct example in TDD skill
docs: improve quick-start guide
```

### Documentation

- Utilise des exemples concrets
- Écris en français (ou ajoute une traduction EN)
- Reste simple et accessible aux débutants
- Ajoute des emojis pour la lisibilité 🎨

### Code

Si ton skill inclut du code :
- Commente bien
- Utilise des noms de variables clairs
- Teste avant de soumettre

## Process de Review

1. Tu soumets une PR
2. On regarde si :
   - Ça suit les standards
   - C'est utile pour la communauté
   - Ça marche avec Claude
3. On te donne du feedback si besoin
4. Une fois approuvé → Merge ! 🎉

## Idées de Contributions

### Skills à Créer

- **api-design** - Design d'APIs REST/GraphQL
- **database-design** - Modélisation de BDD
- **security-review** - Review orienté sécu
- **performance-optimization** - Optimisation perfs
- **docker-workflow** - Workflow Docker/K8s
- **ci-cd-setup** - Setup CI/CD
- **error-handling** - Gestion d'erreurs
- **state-management** - State management (React, Vue, etc.)

### Améliorations Générales

- [ ] Ajouter des vidéos de démo
- [ ] Créer des templates de projets
- [ ] Traduire en anglais
- [ ] Ajouter des tests automatisés
- [ ] Créer un site web de documentation

### Intégrations

- [ ] VS Code extension
- [ ] CLI pour installer les skills
- [ ] GitHub Action pour valider les skills
- [ ] Script d'installation automatique

## Questions ?

- Ouvre une [Issue](https://github.com/butlucratif/claude-skills-collection/issues)
- Demande sur les Discussions
- Contacte @butlucratif

## Code of Conduct

Sois cool, respectueux et constructif. On est là pour apprendre ensemble ! 🤝

## License

En contribuant, tu acceptes que tes contributions soient sous la même licence que le projet.

---

**Merci de faire grandir cette collection ! 🙏**
