---
name: growth-brain
description: Cerveau growth distillé du second brain de l'utilisateur (Meta ads, funnels, CRO, copywriting, research). Playbook opérationnel pour lancer/diagnostiquer/scaler des campagnes Meta et des tunnels e-com/info à haute conversion. Couvre l'algo Meta (retrieval→auction, Andromeda, creative=targeting, broad), la stratégie créa (net-new concepts vs variations, bigger swings, native statics, formats), le testing & scaling (budgets, KPIs de cut, 1 concept/ad set), le diagnostic par la data (CPC/CTR/CPM cibles, EPV, add-to-cart 10% / ATC→purchase 30%, "test your checkout"), les funnels (quiz, advertorial, paywall simplifié, subscription vs one-time), le copywriting (savage copy, OG sales letters, seeding, pré-handling objections) et la research avatar (produit 2026, AI 80% research, foundational docs). Use when the user asks about "meta ads", "facebook ads", "publicité facebook", "scaler mes ads", "pourquoi mes ads ne convertissent pas", "creative testing", "ad account structure", "CPM trop haut", "broad targeting", "quiz funnel", "advertorial", "paywall", "copywriting", "sales letter", "hook", "angle", "product research", "avatar", "CRO", "add to cart no sales", "breakeven ROAS", "quand couper une ad", or works on the GYPS campaign/funnel. Complète (ne remplace pas) le skill quiz-funnel-expert pour le détail quiz/paywall.
license: MIT
metadata:
  version: 1.1.0
  source: second brain iCloud (Jay/Learning) — 38 notes marketing/growth
---

# Growth Brain

Playbook growth **opérationnel**, distillé de ~90k mots de notes (créateurs e-com 7-9 figures : MarkBuildsBrands & agences growth) + croisé avec le contexte GYPS. Objectif : agir avec les bonnes règles/KPIs **par défaut**, pas re-lire des transcripts. Pour le détail brut → vault iCloud `Obsidian Vault/Jay/Learning/`. Pour le détail quiz/paywall → skill `quiz-funnel-expert`.

---

## Thèse centrale (à imprimer dans la mémoire de l'agent)

0. **Le marketing = CONTRAST.** Ne pas "faire mieux", mais **ne ressembler à personne** (faire l'opposé de tout ce que le marché consomme) pour casser le pattern — PUIS **disguise** (advertorial/quiz/native = vendre sans que ça ressemble à de la vente). Marché : **purple ocean** (marché prouvé + segment hyper-spécifique possédé à 100 %). Voir [07](references/07-strategy-mindset.md).
1. **La créa EST le ciblage.** Post-Andromeda, Meta lit la créa (hook, format, démographie montrée, copy, script, landing) pour décider à qui montrer l'ad. → Run **broad**, Advantage+, ~0 targeting manuel (au plus 1 exclusion acheteurs). Arrête de bidouiller les audiences.
2. **Média-buying ≠ trouver des winners.** Sous ~3-5k$/j, la structure d'ad account et le média-buying ne sont PAS le constraint. Le constraint = **trouver des créas gagnantes**. Pense en entrepreneur, pas en média-buyer.
3. **Facebook n'est pas une mystery box.** Un mauvais ROAS a une cause lisible dans la data (ad-side vs funnel-side). On diagnostique, on ne « change d'angle au feeling ».
4. **"When in doubt, zoom out."** À bas spend (<1k$/j) les résultats oscillent (sine wave) = normal. Décider sur 7 jours / max de data, jamais au jour le jour ni à l'émotion.
5. **Prends de plus gros swings.** Pas de micro-variations (vieux monsieur → jeune monsieur). Teste de la vraie variété / des net-new concepts. Extrais les **variables gagnantes** → nouveaux concepts.
6. **Ne crois pas Facebook.** Les suggestions « -11% cost per result » au niveau ad = piège à drainer le budget. EMQ/opportunity score = surcotés. CAPI = bien, mais data conversion à prendre avec des pincettes (attribution tierce).

---

## KPI quick-reference (cibles à citer par défaut)

**Ad-side** (par ordre d'importance : CPC > CTR > CPM) :
| Métrique | Cible US | Cible hors-US (FR/Big4) | Note |
|---|---|---|---|
| CPC lien | 1,50-2 $ | ~1 $ (ou moins) | le + important ; = coût du trafic |
| CTR | 4 %+ | 4 %+ (6-8 % si CPM haut) | relevance ; les 3 bougent ensemble |
| CPM | cap 80-100 $ | cap 50-70 $ | le moins important, très contextuel (health/CPG = haut) |
| Hook rate / hold rate / cost 3s view | — | — | soft metrics de l'eCTR |

**Funnel-side** :
| Étape | Cible | Diagnostic si raté |
|---|---|---|
| Link click → landing page view | drop < 20 % | > 20 % = problème vitesse de chargement |
| Add-to-cart (ou équivalent : lead/checkout) | **10 %** des landers (7-8 % si produit 80-100 $+) | bas = problème trafic/créa OU lander |
| **ATC → purchase** | **30 %** | bas = **TESTER LE CHECKOUT** (moyen de paiement, zip/adresse, checkout fonctionnel) |
| ATC → initiate checkout | ≥ 50-60 % | — |
| Initiate checkout → purchase | élevé | bas = friction paiement/prix |
| EPV (earnings per view) − CPC | > 0 | = profit par clic |
| AOV | > prix front | si AOV = prix front → **pas d'upsell = pas bon** |

**Cut rules** (couper agressif) : CPC élevé dès 15-20 $ de spend → cut (un CPC haut redescend rarement assez). Dépense jusqu'au breakeven CPA sans vente → cut. Connaître son **breakeven ROAS avec TOUS les frais** avant de juger.

**Budget testing** : sous 1k$/j → quasi tout le budget en testing (pas de winner à itérer). Min 10 $/ad par test. Établi (>10k$/j) → 20-30 % testing / reste scaling.

---

## Workflow par défaut

### Diagnostic "mes ads ne marchent pas"
1. **Ad-side ou funnel-side ?** Regarde CPC/CTR/CPM d'abord.
   - CPC/CTR hors cible → **problème créa** (la cause n°1 la plus fréquente). Solution : meilleures créas, plus de reps, plus gros swings.
   - CPC/CTR OK mais 0 vente → **problème funnel**. Descends : link→LPV (vitesse) ? ATC rate (10 %) ? **ATC→purchase (30 %)** ?
2. **ATC→purchase bas / 0 vente malgré des checkouts** → **teste le checkout toi-même** (paiement, méthodes, mobile/Apple Pay). Symptôme classique = "add to carts but no sales".
3. Toujours sur 7j+ de data, jamais au jour le jour.

### Trouver des winners
1. Teste **plus de créas** + **plus gros swings** (net-new concepts, pas micro-variations).
2. 1 ad set = 1 net-new concept ; les ads dedans = variations (hooks différents) → plus d'at-bats.
3. Extrais les variables gagnantes → nouveaux concepts. Broad targeting, créa = ciblage.

---

## ⚠️ Corrections & actions pour GYPS (croisement notes ↔ setup actuel)

*(État au 2026-07-01 — vérifier avant d'affirmer.)*
- **#1 — TESTER LE CHECKOUT.** 5 initiate_checkout → 0 vente = pile le symptôme "ATC but no sales" (note dédiée). Prod = `cs_live_` OK, mais **faire un vrai achat test de bout en bout** (Apple Pay/CB sur mobile, méthodes activées, pas de blocage). Priorité absolue avant de blâmer créa/funnel.
- **Ad-side = élite** (CPC 0,15 € vs cible ~1 $, CTR 5,5 %, CPM ~8 €) → les notes confirment : *le problème n'est PAS la créa, c'est le funnel*. Ne pas sur-investir en nouvelles créas tant que le checkout/lead→sale n'est pas réglé.
- **Vérifier l'upsell** (47 €/19 €) toujours branché avec front 67 € (sinon AOV = prix front = "pas bon").
- **Broad OK** : Advantage Audience OFF, âge 30-60, géo FR/BE/LU/QC/Romandie. Pourrait tester encore plus broad (Advantage+) — mineur.
- **Zoom out** : juger les 6 créas prunées + le quiz v2 sur 7j, pas sur les chiffres du jour.
- **Vérifier creative enhancements OFF** au niveau ads.

---

## Anti-patterns à refuser

1. Bidouiller les audiences/lookalikes/interests au lieu de bosser la créa (créa = ciblage).
2. Média-buyer sa sortie de constraint créa (< 3-5k$/j : structure ≠ le sujet).
3. Juger la perf au jour le jour / décisions émotionnelles (zoom out 7j).
4. Micro-variations timides au lieu de gros swings.
5. Croire les suggestions Facebook (-X % cost per result) + sur-truster EMQ/opportunity score.
6. Changer d'angle « au feeling » sans lire la data (ad-side vs funnel-side).
7. AOV = prix front (pas d'upsell/downsell) sur trafic froid → ROAS front < 1.

---

## Références détaillées

- **[01-meta-algo-scaling.md](references/01-meta-algo-scaling.md)** — Algo Meta (4 étapes, équation heavy-ranking, Andromeda, creative=targeting, broad), learning phase, CAPI/EMQ, creative diversity, testing & scaling (budgets, cut rules), structure ABO/CBO.
- **[06-diagnostic-kpis.md](references/06-diagnostic-kpis.md)** — Framework de diagnostic ad-side/funnel-side, tous les KPIs cibles, "add to carts but no sales → test checkout", breakeven, quand couper.
- **[02-creative-strategy.md](references/02-creative-strategy.md)** — winning sales message, formats × marché, native statics, post-Andromeda (medium-TAM), AI ads (workflow Higgsfield+Claude+NanoBanana/Kling), hooks, CPMs, broad.
- **[03-funnel-quiz-paywall.md](references/03-funnel-quiz-paywall.md)** — quiz (2 méthodes, voir aussi quiz-funnel-expert), advertorial (headline 90%, WIIFM, "sans", unique mechanism, twist the knife), paywall simplifié (Superwall +111%), subscription vs OTP.
- **[04-copywriting.md](references/04-copywriting.md)** — "arguments not words" (Agora/E5), méthode Halbert/copyworking, croyances nécessaires, unique mechanism.
- **[05-research-avatar.md](references/05-research-avatar.md)** — money's in the research, AI 80-90%, Foundational Docs SOP (research/avatar/offer/beliefs), produit gagnant (painful problem, AOV, marges 3× COGS), 4 variables (marché/produit/ads/funnel).
- **[07-strategy-mindset.md](references/07-strategy-mindset.md)** — le méta : contrast, disguise, purple ocean, mass desire, 5 universal truths, copy≠content, VOC, swipe philosophy, hook (PIG), économics 3 secteurs + LTV:CAC.

## Couverture & upgrade
**v1.1** : distille l'essentiel des 38 notes du vault (7 références, tous les thèmes). Notes intégrées incl. les grosses (`8 years of marketing advice`, `Neuroscience`, `Breaking Down OG Sales Letters`, `Comment avoir des Leads ULTRA Qualifiés`, `winning products are a lie`, `how to print money with AI`, etc.). Foldées **légèrement** (essence, pas verbatim) : `claude code CRO marketing` (rant identité/advertorial → effet parapluie), `how to master any skill` (reps/feedback loop = déjà dans les 5 universal truths).
**Source de vérité = vault iCloud** `Obsidian Vault/Jay/Learning/`. Pour upgrader : lire les nouvelles notes → distiller dans la ref thématique adéquate → bump la version. Ne jamais copier les transcripts bruts ici (le skill = distillation actionnable, pas une archive).
