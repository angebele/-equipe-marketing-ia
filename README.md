# 🚀 Équipe Marketing IA — Plugin Cowork

**11 agents IA spécialisés** en stratégie, copywriting, tunnel de vente,
contenu, veille de marché, storytelling de marque, gestion des risques et
intelligence des tendances. Réutilisable sur tous les projets grâce à une
architecture en deux couches : le **moteur** (agents + skills, sans contexte
client) et le **contexte** (un fichier projet interchangeable).

> Auteur : Ange Belegue — Ambitieuse Assumée · Version 1.2.0

---

## L'équipe

| Agent | Rôle | Fichier |
|---|---|---|
| 👑 **Stratège CMO** | Chef d'orchestre : analyse, planifie, mandate les autres agents | `agents/01-cmo.md` |
| ✍️ **Copywriter** | Pages de vente, emails, scripts, hooks | `agents/02-copywriter.md` |
| 🔧 **Architecte Tunnel** | Structure et flow des tunnels de vente | `agents/03-tunnel.md` |
| 📱 **Content Strategist** | Stratégie de contenu organique Instagram | `agents/04-content.md` |
| 📈 **Data Analyst** | KPIs, dashboards, analyses, A/B tests | `agents/05-data.md` |
| 🎯 **Media Buyer** | Campagnes Meta Ads, du test au scale | `agents/06-media-buyer.md` |
| 🧠 **Neuromarketing** | Validation des déclencheurs psychologiques | `agents/07-neuromarketing.md` |
| 🔍 **Veilleur Stratégique** | Veille concurrence, tendances et opportunités de marché | `agents/08-veilleur.md` |
| 🎭 **Conteur de Marque** | Storytelling, voix de marque, archéologie de marque | `agents/09-storyteller.md` |
| 🛡️ **Risk Manager & Red Team** | Challenge et stress-test des décisions avant exécution | `agents/10-risk-manager.md` |
| 🔭 **Trend Hunter & Market Intelligence** | Ruptures plateformes, tech et IA au-delà du secteur | `agents/11-trend-hunter.md` |

L'agent par défaut est le **Stratège CMO** : adresse-lui ton brief, il
analyse la situation et mandate les bons agents dans le bon ordre.

> 💡 Le Veilleur Stratégique (🔍) et le Trend Hunter (🔭) se complètent : le
> premier surveille les concurrents directs du secteur, le second explore
> les ruptures hors-secteur (plateformes, tech, IA) qui n'ont pas encore
> atteint le secteur. Voir `agents/11-trend-hunter.md` pour le détail.

## Les 29 skills

| Skill | Utilisé par |
|---|---|
| `01-diagnostic-positionnement.md` | CMO, Neuromarketing |
| `02-structure-offre.md` | CMO, Copywriter |
| `03-page-de-vente.md` | Copywriter, Neuromarketing |
| `04-sequence-email.md` | Copywriter, Architecte Tunnel |
| `05-architecture-tunnel.md` | Architecte Tunnel, CMO |
| `06-calendrier-instagram.md` | Content Strategist |
| `07-hooks-et-accroches.md` | Copywriter, Content Strategist |
| `08-campagne-meta-ads.md` | Media Buyer, Copywriter |
| `09-dashboard-kpis.md` | Data Analyst |
| `10-audit-psychologique.md` | Neuromarketing, Copywriter |
| `11-audit-concurrentiel.md` | Veilleur Stratégique, CMO |
| `12-veille-tendances.md` | Veilleur Stratégique, Content Strategist, CMO |
| `13-carte-positionnement.md` | Veilleur Stratégique, CMO |
| `14-rapport-marche.md` | Veilleur Stratégique, CMO |
| `15-detection-opportunites.md` | Veilleur Stratégique, CMO, Content Strategist |
| `16-story-mining.md` | Conteur de Marque |
| `17-brand-voice-audit.md` | Conteur de Marque |
| `18-creative-copywriting.md` | Conteur de Marque |
| `19-content-engine.md` | Conteur de Marque |
| `20-brand-archaeology.md` | Conteur de Marque |
| `21-choc-initial.md` | Risk Manager & Red Team |
| `22-risk-assessment.md` | Risk Manager & Red Team |
| `23-pre-mortem.md` | Risk Manager & Red Team |
| `24-socratic-squeezing.md` | Risk Manager & Red Team |
| `25-pure-scouting.md` | Trend Hunter & Market Intelligence |
| `26-market-destructuring.md` | Trend Hunter & Market Intelligence |
| `27-ux-tech-insight.md` | Trend Hunter & Market Intelligence |
| `28-unfair-opportunity-finder.md` | Trend Hunter & Market Intelligence |
| `29-pure-ai-horizon.md` | Trend Hunter & Market Intelligence |

---

## Comment ça marche

### Règle fondamentale

**Aucun agent ne contient de contexte client hardcodé.** Chaque agent commence
par lire `context/projet-actif.md`, qui contient tout le contexte du projet
en cours (identité, positionnement, offre, cibles, stack, ton, objectifs).
Toutes ses réponses s'adaptent à ce contexte.

### Démarrer une session

1. Vérifie que `context/projet-actif.md` contient le bon projet
2. Adresse ton brief au Stratège CMO (agent par défaut)
3. Le CMO analyse, livre un plan et mandate les agents spécialisés
4. Chaque agent livre dans son format standardisé (voir son fichier)

Exemple de brief :

> "Je veux lancer mon tunnel de vente pour l'offre premium d'ici 30 jours.
> Par quoi on commence ?"

### Changer de projet

1. Duplique `context/TEMPLATE.md` sous un nouveau nom,
   ex : `context/mon-nouveau-client.md`
2. Remplis toutes les sections (plus c'est précis, meilleures sont les réponses)
3. Active-le en le copiant comme contexte actif :

```bash
cp context/mon-nouveau-client.md context/projet-actif.md
```

Tu peux aussi simplement indiquer en début de session quel fichier contexte
utiliser : *"Utilise context/mon-nouveau-client.md comme contexte projet."*

Pour revenir au projet Ambitieuse Assumée :

```bash
cp context/ambitieuse-assumee.md context/projet-actif.md
```

---

## Structure des fichiers

```
equipe-marketing-ia/
├── manifest.json                  → Déclaration du plugin
├── context/
│   ├── TEMPLATE.md                → Template vierge à dupliquer
│   ├── ambitieuse-assumee.md      → Contexte rempli pour Ange
│   └── projet-actif.md            → Contexte actuellement actif (lu par les agents)
├── agents/                        → Les 11 agents (rôles, skills, formats, instructions)
├── skills/                        → Les 29 frameworks méthodologiques
└── README.md                      → Ce fichier
```

## Bonnes pratiques

- **Un brief = un objectif.** Plus ta demande est précise, plus le livrable l'est.
- **Passe par le CMO** pour tout chantier multi-agents ; adresse-toi directement
  à un agent spécialisé pour une tâche ponctuelle (ex : "Copywriter, donne-moi
  5 hooks pour ce post").
- **Fais valider les pages de vente** par le Neuromarketing (skill 10) avant
  mise en ligne.
- **Mets à jour le contexte** quand le projet évolue (nouveaux chiffres,
  nouvelle offre, nouveaux objectifs) — les agents ne devinent pas.
