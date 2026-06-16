---
name: pre-mortem
description: Imaginer que le projet a déjà échoué pour remonter à la cause racine et la neutraliser avant qu'elle ne se produise.
---

# Skill 23 — Pre-Mortem Facilitator

## Objectif

Forcer l'équipe à envisager l'échec avant le lancement, pour identifier
les causes qu'un optimisme de façade laisserait passer.

## Utilisé par

- 🛡️ Risk Manager & Red Team

## Framework — Méthode en 4 étapes

### Étape 1 — Poser l'échec comme un fait
Formuler explicitement : "Ce projet a échoué. Six mois après le
lancement, [résultat décevant précis]."

### Étape 2 — Remonter les causes possibles
Lister librement toutes les raisons plausibles de cet échec, sans
censure ni recherche de solution à ce stade.

### Étape 3 — Identifier la cause racine la plus probable
Parmi toutes les causes listées, isoler celle qui, si elle se produisait,
expliquerait le mieux l'échec décrit.

### Étape 4 — Neutraliser avant le lancement
Pour la cause racine, définir une action concrète à mener avant le
lancement, pas après.

## Méthode

1. Définir un scénario d'échec précis et daté (pas "ça pourrait ne pas
   marcher" mais "dans 3 mois, 0 vente malgré 50 leads qualifiés")
2. Lister 5 à 10 causes possibles
3. Voter ou trancher sur la cause la plus probable
4. Définir l'action de neutralisation et son responsable

## Format de livrable

```
PRE-MORTEM — [Projet / lancement analysé]
SCÉNARIO D'ÉCHEC : [Description précise et datée]
---
CAUSES POSSIBLES IDENTIFIÉES :
[Liste brute]

CAUSE RACINE LA PLUS PROBABLE :
[...]

ACTION DE NEUTRALISATION (avant lancement) :
[Action] → Responsable : [Agent ou personne]
```

## Exemple court

> **Scénario d'échec :** "3 mois après le lancement de l'offre groupe,
> 2 inscriptions seulement malgré 200 vues de la page." **Cause racine
> probable :** la promesse de la page ne répond à aucune douleur
> exprimée par la cible — elle parle de méthode, pas de transformation
> vécue. **Action :** faire valider la page par le Neuromarketing avant
> mise en ligne, pas après les premiers résultats décevants.
