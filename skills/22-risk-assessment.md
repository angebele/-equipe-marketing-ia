---
name: risk-assessment
description: Cartographier les risques d'un plan marketing par probabilité et gravité, pour prioriser ce qui doit être traité avant exécution.
---

# Skill 22 — Risk Assessment

## Objectif

Donner une vue d'ensemble structurée des risques d'un plan, d'une offre
ou d'une campagne, classés pour décider rapidement ce qui mérite d'être
traité avant le lancement.

## Utilisé par

- 🛡️ Risk Manager & Red Team

## Framework — Matrice probabilité × gravité

Pour chaque risque identifié, évaluer :
- **Probabilité** : Faible / Moyenne / Élevée
- **Gravité** : Mineure / Sérieuse / Critique

### Catégories de risques à explorer systématiquement
- Risque de message (la promesse est mal comprise ou ne convainc pas)
- Risque d'exécution (l'équipe ou les outils ne peuvent pas livrer ce qui
  est promis)
- Risque de marché (la cible n'est pas prête, ou la concurrence réagit)
- Risque de réputation (l'action peut nuire à l'image de la marque)
- Risque financier (le coût dépasse le retour attendu)

## Méthode

1. Lister tous les risques par catégorie
2. Positionner chacun sur la matrice probabilité × gravité
3. Ne retenir pour action immédiate que les risques Élevée/Critique ou
   Moyenne/Critique
4. Pour chaque risque retenu, proposer une mitigation concrète

## Format de livrable

```
RISK ASSESSMENT — [Plan / offre / campagne analysée]
---
🔴 PROBABILITÉ ÉLEVÉE × GRAVITÉ CRITIQUE :
[Risque] → Mitigation : [...]

🟠 PROBABILITÉ MOYENNE × GRAVITÉ CRITIQUE / SÉRIEUSE :
[Risque] → Mitigation : [...]

🟡 AUTRES RISQUES (surveillance) :
[Risque] → Signal à surveiller : [...]
```

## Exemple court

> **🔴 Probabilité élevée × gravité critique :** Le tunnel dépend d'un
> outil que personne dans l'équipe ne maîtrise encore en profondeur —
> risque de panne le jour du lancement. **Mitigation :** tester le tunnel
> complet 5 jours avant le lancement avec un faux paiement, pas la veille.
