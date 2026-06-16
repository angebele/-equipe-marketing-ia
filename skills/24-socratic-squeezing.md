---
name: socratic-squeezing
description: Presser une décision marketing par questions successives jusqu'à faire émerger les hypothèses non vérifiées et les angles morts.
---

# Skill 24 — Socratic Squeezing

## Objectif

Faire remonter, par une série de questions resserrées, les hypothèses
implicites sur lesquelles repose une décision — sans jamais les énoncer
soi-même à la place de l'utilisateur.

## Utilisé par

- 🛡️ Risk Manager & Red Team

## Framework — La spirale de questions

### Niveau 1 — La décision affichée
"Qu'est-ce qui est décidé exactement ?"

### Niveau 2 — La preuve
"Sur quoi te bases-tu pour penser que ça va marcher ?"

### Niveau 3 — L'hypothèse cachée
"Si cette preuve était fausse, qu'est-ce qui s'effondrerait dans le
plan ?"

### Niveau 4 — Le test
"Comment pourrais-tu vérifier cette hypothèse avant de tout engager
là-dessus ?"

### Niveau 5 — La conséquence assumée
"Si tu avances sans vérifier, qu'est-ce que tu es prêt à perdre ?"

## Méthode

1. Démarrer par la décision telle qu'elle est formulée
2. Poser une question à la fois, jamais plusieurs en même temps
3. Ne jamais répondre à la place de l'utilisateur — chaque réponse
   alimente la question suivante
4. Arrêter quand l'hypothèse non vérifiée est clairement nommée par
   l'utilisateur lui-même

## Format de livrable

```
SOCRATIC SQUEEZING — [Décision analysée]
---
Q1 — Décision affichée : [Réponse obtenue]
Q2 — Preuve invoquée : [Réponse obtenue]
Q3 — Hypothèse cachée révélée : [Réponse obtenue]
Q4 — Test possible avant engagement : [Réponse obtenue]
Q5 — Conséquence assumée si non vérifié : [Réponse obtenue]
---
HYPOTHÈSE NON VÉRIFIÉE IDENTIFIÉE :
[Résumé en une phrase]
```

## Exemple court

> **Q2 — Preuve invoquée :** "Mes 3 dernières clientes ont adoré le
> format groupe." **Q3 — Hypothèse cachée révélée :** "Je suppose que la
> prochaine vague de clientes a le même profil que les 3 précédentes,
> alors que le contexte projet montre une cible plus diversifiée
> maintenant." → Hypothèse non vérifiée : la généralisation d'un petit
> échantillon à toute la nouvelle cible.
