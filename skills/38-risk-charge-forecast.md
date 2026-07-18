---
name: risk-charge-forecast
description: Cartographier les risques réels, les coûts, la charge de travail réelle, et identifier les points de rupture où l'idée peut échouer.
---

# Skill 38 — Risk & Charge Forecast

## Objectif

Sortir de "c'est ambitieux" vague et quantifier : **quels vrais risques
menacent l'idée**, combien ça va vraiment coûter, comment ta charge va
augmenter, et **où ça peut casser**.

## Utilisé par

- 🎲 Évaluateur d'Idées

## Framework — 3 cartographies

### 1. Risques par probabilité & gravité
Pour chaque risque réel, évaluer : prob (faible/moyenne/élevée) et
gravité (mineure/sérieuse/critique).

### 2. Coûts réels (pas estimé marketing)
Développement, infrastructure, acquisition, ops, salaires si embauche,
outils récurrents, assurance si applicable.

### 3. Charge de travail
Combien d'heures/mois pendant combien de temps. Qui travaille dessus ?
C'est un boulot full-time ou 20% du temps de quelqu'un ?

### 4. Points de rupture
Si X se produit (le pire cas pour chaque risque), l'idée meurt ou on
peut la sauver ?

## Méthode

1. Lister tous les risques probables (technique, marché, ops, personnel)
2. Scorer chaque risque
3. Évaluer les coûts réels, pas optimistes
4. Calculer la charge et identifier qui
5. Identifier les kill switches (points de non-retour)

## Format de livrable

```
RISK & CHARGE FORECAST — [Idée]
---
RISQUES CARTOGRAPHIÉS :
🔴 PROBABILITÉ ÉLEVÉE × GRAVITÉ CRITIQUE :
[Risque] → Mitigation : [Comment l'éviter]

🟠 PROBABILITÉ MOYENNE × GRAVITÉ SÉRIEUSE :
[Risque] → Mitigation : [Comment l'éviter]

🟡 AUTRES (surveillance) :
[Risque] → Signal d'alerte : [À surveiller]

COÛTS RÉELS :
Développement : X€
Infrastructure / Outils : X€/mois
Acquisition (phase 1) : X€
Personnel si embauche : X€/mois
Contingence (imprévu) : X€

TOTAL ANNÉE 1 : X€

CHARGE DE TRAVAIL :
Phase 1 (dev/setup) : X heures
Phase 2 (lancement) : X heures/mois
Phase 3 (scale) : X heures/mois
Responsables : [Qui fait quoi]

Impact sur la charge globale de l'équipe : [Léger / Moyen / Lourd]

POINTS DE RUPTURE (kill switches) :
Si [Événement critique] se produit → [L'idée meurt / On peut la sauver comment]
```

## Exemple court

> **Risque critique :** dépendance sur un seul partenaire de distribution
> (YouTube channel). Si partenaire arrête, distribution s'écroule. **Mitigation :**
> dès mois 2, avoir 2 canaux de distribution min. **Coûts :** dev 15K€ + ops
> 2K€/mois + ads phase 1 10K€ = 35K€ année 1. **Charge :** 1 personne à 40%
> pendant 3 mois (dev), puis 20% ops. **Impact :** moyen. **Kill switch :** si
> conversion <2%, on réévalue à mois 3, go/no-go decision.
