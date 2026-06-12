# Skill 08 — Campagne Meta Ads

## Objectif

Structurer une campagne Meta Ads (Facebook + Instagram) de la phase test au
scale, avec des décisions pilotées par les métriques.

## Utilisé par

- 🎯 Media Buyer
- ✍️ Copywriter

## Framework — Test → Optimisation → Scale

### Phase 1 — Test (300€/mois, 2-3 semaines)

Structure : **1 campagne → 3 adsets → 3 annonces par adset**

- **3 adsets** = 3 audiences distinctes (ex : intérêts cible 1, intérêts
  cible 2, lookalike ou audience large)
- **3 annonces par adset** = 3 angles d'accroche :
  1. Douleur ("Tu postes régulièrement mais personne n'achète")
  2. Désir ("Imagine 3 candidatures qualifiées par semaine")
  3. Curiosité ("Le détail qui sépare les comptes qui vendent des autres")
- Objectif de campagne : conversion (opt-in du tunnel), ou trafic si le
  pixel est froid

### Phase 2 — Optimisation (500-1000€/mois)

- Couper ce qui sous-performe : CTR < 0,8% après 1000 impressions,
  CPL > 20€ après 500€ dépensés
- Concentrer le budget sur les combinaisons gagnantes
- Lancer le retargeting : visiteurs page de vente, vues vidéo 50%+,
  engagement Instagram 30 jours

### Phase 3 — Scale (1000€+/mois)

- Scaler uniquement si : CTR > 2%, CPL < 8€, ROAS > 3x sur 7 jours consécutifs
- Augmentation progressive : +20-30% de budget tous les 3-4 jours
  (jamais doubler d'un coup)
- Dupliquer les adsets gagnants vers de nouvelles audiences lookalike

## Format de livrable

```
CAMPAGNE : [Nom]
OBJECTIF : [Conversion attendue]
CIBLE PRIORITAIRE : [Profil]
PHASE : [Test / Optimisation / Scale]
BUDGET : [Montant / mois]
---
ADSET 1 — [Audience] : [détail ciblage]
  Annonce A (douleur) : [Accroche + description visuel + CTA]
  Annonce B (désir) : [...]
  Annonce C (curiosité) : [...]
[Répéter pour les 3 adsets]
---
SEUILS DE DÉCISION : [Stop / Continue / Scale, avec les métriques]
PLAN DE RETARGETING : [Audiences + messages]
```

## Exemple court

> **Adset "Experte établie" — Annonce A (douleur) :**
> Accroche : "Ton business tourne, mais ton compte Instagram ne le montre
> pas." Visuel : portrait pro sobre, citation en surimpression. CTA :
> "Télécharge le diagnostic" → opt-in du tunnel. Seuil : stop si CPL > 20€
> après 500€ ; scale si ROAS > 3x sur 7 jours.
