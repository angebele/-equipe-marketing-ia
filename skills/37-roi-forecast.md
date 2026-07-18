---
name: roi-forecast
description: Projeter le revenue potentiel, break-even, ROI année 2 et cas pessimiste basés sur les données du marché trouvées.
---

# Skill 37 — ROI & Break-Even Forecast

## Objectif

Au-delà des coûts : **quel est le potentiel de revenue réel** basé sur les
données du marché qu'on a trouvées, quand ça devient rentable, et si
c'est vraiment worth le coup ?

## Utilisé par

- 🎲 Évaluateur d'Idées

## Framework — Les 3 scénarios

### 1. Cas optimiste
Tu nails tout : bonne exécution, timing parfait, conversion haute.
Revenue année 1 : X€

### 2. Cas réaliste
Exécution moyenne, quelques frictions, conversion normale.
Revenue année 1 : X€

### 3. Cas pessimiste
Pires cas raisonnables : moins de traction que prévu, conversion basse.
Revenue année 1 : X€

Pour chaque : break-even (mois X), ROI année 2, et "c'est worth ?"

## Méthode

1. Estimer la taille du marché accessible
2. Estimer ta part de marché réaliste (low/mid/high)
3. Calculer revenue par scénario
4. Déduire les coûts (dev, marketing, ops)
5. Déterminer break-even et ROI

## Format de livrable

```
ROI & BREAK-EVEN FORECAST — [Idée]
---
MARCHÉ ACCESSIBLE :
Taille totale : [X€ / X personnes]
Ta part réaliste : [X%]

CAS OPTIMISTE :
Revenue année 1 : X€
Clients acquis : Y
Break-even : Mois X
ROI année 2 : X%

CAS RÉALISTE :
Revenue année 1 : X€
Clients acquis : Y
Break-even : Mois X
ROI année 2 : X%

CAS PESSIMISTE :
Revenue année 1 : X€
Clients acquis : Y
Break-even : Mois X
ROI année 2 : X%
Seuil de "ça ne marche pas" : [Si moins de X clients]

VERDICT FINANCIER :
[L'idée est rentable même en cas pessimiste / Rentable seulement en cas optimiste / Never rentable]
```

## Exemple court

> **Marché accessible :** 500 expertes + 200 salariés en reconversion = 700
> prospects potentiels. **Cas réaliste :** 50 clients year 1 (7% conversion) à
> 2000€ = 100K€. Coûts dev/ops/marketing : 30K€. Profit année 1 : 70K€.
> Break-even : mois 4. ROI année 2 : +250%. **Cas pessimiste :** 20 clients =
> 40K€ revenue, profit : 10K€, break-even : mois 9. **Verdict :** rentable même
> dans les pires cas, go.
