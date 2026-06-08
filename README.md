# Analyseur HSE OCP Mining

Plateforme d'évaluation HSE des entreprises extérieures selon le Standard GEEX OCP S-HSE-27.

## Fonctionnement
- **Zéro token** · **Zéro backend** · **Zéro coût**
- PDF.js lit le contenu réel de chaque PDF
- JSZip extrait les archives ZIP (sous-archives imbriquées incluses)
- Moteur GEEX par document : scoring cumulatif sur 3 niveaux
- Export rapport Excel (.xls)

## Déploiement GitHub Pages

```bash
# 1. Créer le dépôt
git init
git add .
git commit -m "Initial deploy"
git remote add origin https://github.com/VOTRE_USERNAME/hse-analyzer.git
git push -u origin main

# 2. Activer GitHub Pages
# Settings → Pages → Source: main branch → / (root) → Save
```

## Structure
```
index.html   ← plateforme complète (fichier unique)
README.md    ← ce fichier
```

## Critères évalués (16)
| Code | Critère | Thème |
|------|---------|-------|
| pol | Politique HSE | A. Politique & Pilotage |
| pil | Pilotage performance | A. Politique & Pilotage |
| org | Organigramme | B. Organisation & Moyens |
| fic | Fiches de fonction | B. Organisation & Moyens |
| obj | Objectifs HSE | C. Planification |
| ris | Analyse risques ADRPT | C. Planification |
| pro | Procédures & Standards | C. Planification |
| hyg | Hygiène & Déchets | C. Planification |
| for | Programme formation | D. Compétences |
| pos | Postes dangereux | D. Compétences |
| hab | Habilitations | D. Compétences |
| aud | Audits internes | E. Amélioration continue |
| sor | Visites SOR | E. Amélioration continue |
| acc | Enquêtes accidents | E. Amélioration continue |
| tf | Taux de Fréquence | F. Indicateurs |
| tg | Taux de Gravité | F. Indicateurs |
