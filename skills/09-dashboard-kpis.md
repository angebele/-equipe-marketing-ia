# Skill 09 — Dashboard KPIs

## Objectif

Construire un tableau de bord Notion (ou équivalent selon la stack du projet)
qui donne en 5 minutes une lecture claire de la performance et de la priorité
de la semaine.

## Utilisé par

- 📈 Data Analyst

## Framework — Dashboard en 4 tableaux

### Tableau 1 — TUNNEL
| Métrique | Objectif | Alerte |
|---|---|---|
| Taux d'opt-in | > 30% | < 20% |
| Conversion page de vente | > 2% | < 1% |
| Présence appel découverte | > 70% | < 50% |
| Closing appel | > 30% | < 15% |

### Tableau 2 — EMAIL
| Métrique | Objectif | Alerte |
|---|---|---|
| Taux d'ouverture | > 30% | < 20% |
| Taux de clic | > 3% | < 1,5% |
| Désinscription | < 0,5% | > 1% |

### Tableau 3 — CONTENU
| Métrique | Objectif | Alerte |
|---|---|---|
| Portée organique / post | Tendance croissante | Baisse 3 semaines |
| Taux d'engagement | > 3% | < 1,5% |
| Clics vers le tunnel | Suivi hebdo | 0 clic sur 7 jours |

### Tableau 4 — BUSINESS
| Métrique | Suivi |
|---|---|
| Coût par lead (CPL) | Hebdo (benchmark coaching : 5-15€) |
| Coût par client (CPA) | Mensuel |
| Revenu mensuel récurrent (MRR) | Mensuel, vs objectif 90 jours du contexte |

## Rituel hebdomadaire (5 minutes)

1. Ce qui fonctionne (1-2 métriques au-dessus de l'objectif)
2. Ce qui bloque (la métrique la plus en retard + hypothèse)
3. LA priorité de la semaine (une seule action corrective)

## Format de livrable

```
DASHBOARD — [Projet] — Semaine du [date]
---
[Les 4 tableaux avec valeurs réelles vs objectifs]
---
✅ CE QUI FONCTIONNE : [...]
⚠️ CE QUI BLOQUE : [...] — Hypothèse : [...]
🎯 PRIORITÉ DE LA SEMAINE : [Action actionnable sous 7 jours + responsable]
```

## Exemple court

> **⚠️ Ce qui bloque :** opt-in à 18% (objectif > 30%). Hypothèse : la
> promesse du lead magnet est trop générique pour la cible Experte établie.
> **🎯 Priorité :** mandater le Copywriter pour 2 variantes de titre de la
> page de capture, A/B test sur 7 jours.
