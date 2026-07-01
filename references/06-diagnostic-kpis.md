# 06 — Diagnostic par la data & KPIs

## Principe (source : "stop running ads like an npc", "why your ads perform like sh*t")
Facebook n'est PAS une mystery box. Un output pourri (ROAS 0.4, CAC 199 $) a une **cause lisible**. Mets ta blouse de scientifique : décompose inputs → outputs, identifie si c'est **créa (ad-side)** ou **funnel-side**, puis descends jusqu'à la variable fautive. "Read what the data is telling you."

## Ad-side (par importance : CPC > CTR > CPM)
- **CPC** = coût du trafic. Le plus important. Cibles : US 1,50-2 $, hors-US/Big4 ~1 $.
- **CTR** ≥ 4 % (monte à 6-8 % si CPM haut — les 3 métriques bougent ensemble : CPM haut ⇒ il faut compenser par un CTR plus haut pour tenir le CPC cible).
- **CPM** : le moins important, ultra-contextuel (health/beauty/CPG/weight-loss/ED = naturellement haut). Cap US ~80-100 $, Big4 ~50-70 $.
- Soft metrics : hook rate, hold rate, cost/3s view, event match quality.
- Si CPC/CTR hors cible → **problème créa** (la cause la + fréquente, "your ads just aren't good enough"). Mais contexte : CPM 100 $ ⇒ 4 % CTR ne suffit pas.

## Funnel-side
- **Link click → landing page view** : drop **< 20 %**. Au-delà = **problème de vitesse de chargement**.
- **Add-to-cart rate** = **10 %** des landers (7-8 % si produit 80-100 $+). Exception : trafic low-cost (native statics) à CPC ultra-bas (0,20 $) → pas 10 %. Un ATC bas = souvent problème de **qualité de trafic** (visible dans l'ATC rate, pas dans l'ATC→purchase).
- **ATC → purchase** = **30 %**. Décomposable : ATC → initiate checkout ≥ 50-60 %, initiate checkout → purchase élevé (ex. 60 % × 50 % ≈ 30 % net).
- **EPV** (earnings/revenue per view) − **CPC** = profit par clic. EPV pas de cible fixe (dépend du CPC).
- **AOV** : si AOV = prix front (pas d'upsell) → **pas bon** (manque de contribution AOV). Upsell/downsell obligatoire sur trafic froid.

## "Add to carts but no sales" (note dédiée — TRÈS pertinent GYPS)
Beaucoup d'ATC + 0 vente (ex. 10+ ATC, 0 purchase) après un vrai spend (~500 $) → le problème est **entre l'ATC et le purchase**, pas la qualité de trafic (sinon ça se verrait dans l'ATC rate). Actions :
1. **TESTE TON CHECKOUT toi-même** — checkout fonctionnel ? processeur de paiement mal réglé ? (zip/adresse matching, full address vs zip only, méthodes de paiement, mobile/Apple Pay). "Some people legitimately don't even have functional checkouts."
2. Source-of-truth tracking/analytics fiable pour voir exactement où ça casse.
3. Sors de tes chaussures : pense comme le client, pas comme le vendeur.

## Quand couper une ad (source : "how to read the data", "npc")
- Connaître son **breakeven CPA/ROAS avec TOUS les frais** (paiement, shipping, handling, COGS).
- Règle : dépense jusqu'au breakeven CPA sans vente → **cut**.
- Cut plus tôt via **leading indicators** : CPC élevé dès 15-20 $ de spend → cut (un CPC haut redescend rarement assez). Cost per ATC / cost per initiate checkout hors ligne → cut.
- ⚠️ Ne pas couper trop tôt AVANT de connaître ses funnel economics (combien d'ATC→initiate→purchase en moyenne sur un dataset suffisant).
- Zoom out : décisions sur 7j+, jamais au jour le jour.

## Ordre de diagnostic (arbre)
ROAS mauvais → CPC/CTR OK ? 
- Non → créa (plus de reps, plus gros swings). 
- Oui → funnel : link→LPV (vitesse) → ATC 10 % (trafic/lander) → **ATC→purchase 30 % (checkout/prix)**. Descends jusqu'à la marche qui casse, corrige-la, remonte.
