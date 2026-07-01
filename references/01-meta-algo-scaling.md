# 01 — Algo Meta, testing & scaling

## Comment Meta sert une ad (4 étapes, ~200 ms, source : MarkBuildsBrands)
1. **Retrieval** — le plus data-intensive : des dizaines de millions d'ads → millions. Meta **analyse la CRÉA** (hook, format, démographie montrée à l'écran, copy, script, thumbnail, **et la landing page**) pour décider à qui l'ad est pertinente. ⇒ **"Your creative is your targeting."**
2. **Light ranking** — millions → milliers (peu à en dire).
3. **Heavy ranking** — milliers → centaines. C'est ici qu'intervient **l'équation de valeur** :
   `Total value = bid × estimated action rate (eCTR × eCVR) + valeur/UX consommateur`
   - eCTR = pas juste le CTR : culmination des **soft metrics** (CTR, CPC, CPM, hook rate, hold rate, cost/3s view) = à quel point la créa est pertinente.
   - eCVR = click→conversion = à quel point tu monétises le clic dans le funnel.
   - Dernière pièce = Meta protège l'UX (empêcher les advertisers agressifs de flinguer la plateforme).
4. **Auction** — les quelques advertisers restants ; bid le plus haut (dans le contexte de l'équation) gagne l'impression.

**Bidding** : lowest cost (auto-bid) marche jusqu'à 5-6 figures/jour. Cost cap / bid cap = pour résoudre un constraint précis, pas une religion. Choisis selon ton constraint business.

## Andromeda
Update du tri de retrieval, dû à l'afflux de créa IA. Conséquence : Meta se base **surtout sur la créa** pour cibler, plus sur les ad sets. Les audiences (interests/lookalikes) tiennent mal des gros budgets. ⇒ **Run broad**, Advantage+, au plus 1 exclusion (acheteurs). "Creative diversity is king."

## Learning phase (surcotée)
Les ads apprennent **toujours** ; pas de "sortie de learning = bon pour toujours". À bas spend (<1k$/j), les résultats oscillent (sine wave) = **normal**. "When in doubt, zoom out" → juger sur 7j / max de data, pas au jour le jour, pas à l'émotion.

## Signal / CAPI / EMQ
Envoyer de la bonne data server-side (CAPI) = bien pour l'optimisation long terme. MAIS : pas de corrélation directe prouvée EMQ↔profit (Mark a eu EMQ 9.8 + opportunity score 0 sur des comptes ultra-profitables). Prendre la data conversion Facebook **avec des pincettes** → attribution tierce (Triple Whale, etc. ou custom).

## Creative diversity : concepts vs variations
- **1 ad set = 1 net-new concept.** Les ads dedans = **variations** (hooks différents) du concept → plus d'"at-bats" au niveau concept.
- Les variations restent **très efficaces** (une variation peut être le winner alors que le concept "original" est loser). Ne pas les jeter.
- Une variation du TOP ad de l'account surperforme rarement le top ad (elle fait "decent"). Le gain vient de tester de **nouveaux concepts** + extraire les variables gagnantes → nouveaux concepts.

## Testing & scaling (budgets)
- **Not enough reps** = la raison n°1 : pas assez de créas testées (et pas assez de landers).
- Split budget : établi (>5-10k$/j) ≈ 15-30 % testing / reste scaling. **Sous 1k$/j → quasi 100 % testing** (tu n'as pas encore de winner à itérer). Ajuster le slider selon le spend.
- **Min 10 $/ad** par test.
- **Prends de plus gros swings** (surtout sous 1k$/j) : pas "vieux monsieur → jeune monsieur", mais de la vraie variété. Idem côté landing page : teste les extrêmes tant que tu n'es pas à un volume où un micro-changement CRO bouge les chiffres.

## Structure d'ad account (note dédiée)
- **ABO** (budget au niveau ad set) donne + de contrôle ; mais **< 3-5k$/j, CBO vs ABO ne change quasi rien**.
- 1 concept/ad set, budget ≈ CAC cible × nb d'ads (ou ~50 % pour petits comptes).
- **Ne PAS trouver des winners via le média-buying** — c'est de la créa. Le média-buying améliore la perf de ~10-50 % max.
- Ne pas laisser de "creative enhancements" / bullshit activés au niveau ad set.
- ⚠️ CPM qui s'effondre soudain (ex. -90 %) = **mauvais signe** (Meta baisse la qualité du trafic), pas une aubaine.
