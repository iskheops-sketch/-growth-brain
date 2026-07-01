# 02 — Stratégie créa (statics, formats, AI ads, hooks)

## Le vrai objectif : le WINNING SALES MESSAGE (pas "le winning ad")
Ce que tu cherches = **ton message de vente gagnant** (l'angle + le framing qui résonne). Une fois trouvé, il se **transmute** partout : image, native static, UGC, VSL, short-form, founder UGC, bottom-of-funnel. Les **image ads** sont le moyen le + rapide/cheap de le trouver (tester beaucoup d'angles/avatars). La **vidéo** vient scaler ensuite.

## Choisir le format : matche marché × produit
Connais la **forme de consommation préférée** de ton marché :
- **Older people (surtout femmes âgées) préfèrent LIRE** → statics + **advertorials** printent (c'est pour ça que l'advertorial cartonne sur ces marchés).
- **25-40 ans** → short-form video / UGC TikTok-style.
- Pas de bon/mauvais format dans l'absolu — il y a un bon format **pour ton marché**. Commence par ça, expérimente ensuite.
- 🎯 **GYPS** : ICP = enfants adultes 40-60, 55 % F → **statics + advertorial = le bon choix** (déjà en place). Vidéo (Higgsfield) en complément, pas en remplacement.

## Native statics
Amènent le prospect d'un niveau de conscience élevé → most aware, en construisant **intrigue/curiosité** ; le **funnel fait le heavy lifting**. Copy court, CTA = **"lire l'article"** (advertorial) → sales page/PDP, PAS "acheter". Best pour audiences solution-aware / problem-aware. Unaware = le + dur à scaler (éviter au début).

## Post-Andromeda : medium-TAM > un seul high-TAM
Avant : 1 ad ultra-high-TAM pouvait scaler $5M seule. Après Andromeda : Meta excelle à trouver des **micro-niches** → mieux vaut **10 ads medium-TAM** (plus spécifiques, toujours TOF, ~$500k chacune) qu'une seule high-TAM. Les ads lower-TAM (solution/product-aware) sont souvent **plus profitables** (moins scalables) → en avoir plus. = pourquoi "creative diversity is king".

## AI ads (workflow Mark, stack : Claude + Higgsfield)
**Image ads** (cheap/rapide, pour trouver le message) :
1. **Foundational docs** = recherche psycho/psychographique profonde (mots exacts du client, hot points émotionnels, stade de sophistication, niveau de conscience). "The money's in the research." (cf. SOP + ref 05).
2. **Swipe** (GetHooked, ads 4-5★ dans ta langue) OU **new concepts** (prompts d'idéation).
3. Claude (projet + foundational docs) analyse **pourquoi** l'ad marche + reverse-engineer chaque élément → génère un **text-to-image prompt**.
4. Higgsfield **NanoBanana Pro** + upload d'un **PNG produit sur fond blanc** → 4 variations. Feedback → Claude ajuste le prompt.
5. Texte mal orthographié sur l'image = **prompt pas assez détaillé** (les LLM n'extraient pas tout d'une image — ajoute les détails manquants). *(cf. notre fix accents GPT Image 2 : même logique — forcer les détails dans le prompt.)*

**Video ads** (plus scalables, CVR + haut car attention en isolation) — 5 étapes : swipe → **script** (Claude + foundational docs réécrit le transcript) → **storyboard** (1-2 phrases = 1 clip) → **prompts** (Claude → text-to-image NanoBanana Pro pour le start frame → image-to-video **Kling 3**) → **edit** (assemble + captions + cuts).
- **90 % du succès vidéo = le HOOK (3-5 premières s)** : copy (**70-80 %**) + clip scroll-stopper ("what the fuck did I just look at?") + audio (le moins important).
- Structure : hook (attention) → body (vend : mécanisme, différenciation) → hard CTA.

## CPMs — pourquoi hauts / comment baisser
1. **Ad account pas warm-up** (cause #1). Warm-up : campagnes **PPE + page-likes** à $10/j 2-3 j, PUIS conversion ads en rampe **$10→20→30→40→50** (jamais straight to $50).
2. **Ads/landers non-compliant / trop agressifs** = mauvaise UX → Meta punit (CPM haut). "Selling the click" (clickbait, before/after, sensationalisme, **"Are you struggling with X?"**) → même juste "**you / are you**" assume une identité → ↑ CPM. Fix : **vends le PRODUIT, pas le clic** (le pixel trouve mieux les buyers que les "curiosity clicks") ; nettoie/adoucis créas + landers.
3. **Tester si c'est le lander** : bridge page ultra-clean (image + texte + CTA) → si CPM baisse, le lander était le problème.
4. **Niche compétitive** (pain/beauty/skincare/hair = red markets) = CPM haut structurel, rien à faire sauf changer de niche.
5. Vidéos ont un CPM généralement > statics.
- 🎯 **GYPS** : CPM ~8 € = déjà très bas (marché francophone parent-safety peu concurrentiel, pas de red market) → non-sujet. Compte déjà warm-up (spend > 69 €). Nos angles sont fear-based mais le CPM bas prouve que Meta ne nous punit pas.

## Broad targeting
Au départ : **zéro interest, zéro lookalike → full broad** (créa = ciblage). Lookalikes performent rarement (sauf stack hyper-spécifique, rare). Broad = 1 variable en moins → beaucoup + facile à scaler. Split-test interests plus tard seulement.
