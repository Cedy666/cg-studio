# MyWebsite — CG.STUDIO Site Identity

## Contexte

Site web officiel du studio **CG.STUDIO** de Cédric Godin — filmmaker indépendant, réalisateur-producteur, régisseur technique basé à Paris. Citoyen belge. Formé à l'Académie Royale de Musique et Théâtre de Mons.

**Domaine live** : http://cedricgodin.com
**Repo git** : actif (main branch)
**Dernière mise à jour structure** : 4 juin 2026

## Positionnement du site

Identité de **studio narratif indépendant** — ni portfolio, ni CV, ni site d'agence.

Référence esthétique : A24 / arthouse / engineering-doc hybrid. Minimalisme cinématographique avec esthétique "DOC.001 / DOC.PROFILE v2.1".

Tagline live : *"Independent studio developing original narrative worlds for television, animation and film. Miss One · Die With Peace."*

Crédibilité créative internationale, autorité calme, pas d'auto-promotion.

## Direction visuelle (verrouillée)

- **Background** : #080808 / #0B0B0B (noir mat cinématique)
- **Surface** : #0D0D0D
- **Accent** : #002FA7 (Yves Klein Blue)
- **Texte** : #EDECEA (white) / #A4A3A0 (muted) / #464646 (dim) / #1E1E1E (faint)
- **Typo principale** : Inter (poids 300-400)
- **Typo mono** : JetBrains Mono (labels, meta, classifications)
- **Grille subtile** : Klein blue 2% opacity, 72px
- **Espacement éditorial généreux, rythme lent**

## Structure du site (état actuel — Jun 4 2026)

### Pages live (HTML)

| Fichier | Rôle | Statut |
|---|---|---|
| `index.html` | Home — Hero + About + IP Slate + Selected Works + Contact | ✅ Production |
| `miss-one.html` | Page dédiée IP Miss One | ✅ Production |
| `die-with-peace.html` | Page dédiée IP Die with Peace | ✅ Production |
| `ip.html` | DOC.001 Narrative Development (page interne ?) | 🟡 À vérifier — peut-être à archiver si remplacée par les pages dédiées |
| `youtube-banner.html` | Generator banner YouTube 2560x1440 | ✅ Asset |
| `sitemap.xml` | SEO | ✅ Production |
| `favicon.ico` + `favicon.svg` | Branding | ✅ Production |
| `cedric.JPG` | Portrait About | ✅ Production |

### Structure index.html (live)

1. **Hero** — *"Creator — Producer & Director developing original IPs for television, animation and film"*
   - Compteurs : `IPs IN DEVELOPMENT — 02` / `BROADCAST CREDITS — 06+`
2. **About** — DOC.PROFILE v2.1 — biographie + crédentiels broadcast (Sky News, ARTE, TV5, Bloomberg, NBC Universal, EBU, Roland Garros, Eurovision)
3. **IP Slate** — PIPELINE / 2 ACTIVE
   - **Miss One** (Animation Series · Ages 6-12 · International · STAGE: DEVELOPMENT · e-dpo 000616668)
   - **Die With Peace** (TV Drama · 10 episodes · English · STAGE: DEVELOPMENT · v10)
4. **Selected Works** — PRODUCED / 2018-2024
   - **PTSD** (WRK.001) — Feature 71 min — Hexogen Pictures LLC USA — Best Film + Best Actor Chelsea Film Festival NY
   - **X Art** (WRK.002) — Doc 71 min — Best Editing Amsterdam + Best Documentary Grenoble
   - **Who Is Taki** (WRK.003) — Doc 20 min — Premiere First Amendment Gallery SF
5. **Contact** — OPEN TO COLLABORATIONS — cedricgodin@gmail.com + LinkedIn + YouTube

### IPs verrouillées au 12 juin 2026

**Miss One — Pilote 1 V3.1 LOCKED**
Score 9/10 conception. Cibles : BBC Children's, Apple TV+ Kids, Netflix Kids, France TV OKOO. Pitch MIPCOM octobre 2026.
Dossier de référence : `~/Desktop/PROJECTS/05_Miss_one_TV/01_PILOTAGE/Pilote1_Script_V3.1_FINAL_11juin2026.md`

**Die with Peace — WorkingDoc v10 + OnePager v5 prêts**
Score 9/10 conception. Cibles : Netflix → HBO → AMC/FX. Pitch sequence Brain Trust v2 défini. 3-phase deployment incluant The 36 Deaths anthology.
Dossier de référence : `~/Desktop/PROJECTS/04_Die with peace_TV/`

## Réseaux & extensions studio

- **LinkedIn** : https://www.linkedin.com/in/cedric-godin-23bb6933/
- **YouTube** : https://www.youtube.com/@CedricGodinStudio (channel setup, branding cohérent, à alimenter)

## Projets parallèles (HORS site, hors studio narratif)

- **Here We Boat (HWB)** — location bateaux à moteur Seine, levier YouTube. Auto-entrepreneur. Structure séparée.
- **FRITKOT** — concept friterie belge, en structuration. Structure séparée.

## Conventions de travail

- Réponses directes, concises, opérationnelles. Pas de formules de politesse.
- Toujours demander autorisation avant opération importante (modification HTML/CSS production).
- Livrables finaux sauvegardés dans ce dossier.
- Versioning git respecté — commits clairs pour chaque évolution.
- Mes 2 IPs (M1 + DwP) ont leurs propres dossiers projet et workflows distincts. Ce site est leur vitrine commune, pas leur lieu de développement narratif.

---

## 🎯 NEXT SESSION — Roadmap d'amélioration (review Cowork 12 juin 2026)

### Diagnostic actuel

**Forces** :
- Esthétique pro, identité studio cohérente, positionnement clair
- IP Slate avec 2 projets actifs = pipeline crédible
- Crédentiels broadcast + œuvres primées bien valorisés
- Bilingue EN/FR (à confirmer si le toggle EN/FR fonctionne sur toutes les pages)

**Manques identifiés à combler** :

1. **Visuels manquants sur IP Slate** (PRIORITÉ P0)
   - Miss One : intégrer key art (Hero Shot London v2 ou Miss_ONE_DEF2.jpeg disponible dans `~/Desktop/PROJECTS/05_Miss_one_TV/07_PRODUCTION/10_IA_Workbench/00_MASTERS_OFFICIELS/`)
   - Die with Peace : produire 1-2 key arts atmospheric (Maple Lake / Mike's herbal shop / Mike face shot) via MJ + Photoshop

2. **Sizzle reel studio 60-90 sec** (PRIORITÉ P1)
   - 10 sec crédentiels broadcast (logos défilants Sky News/ARTE/Eurovision...)
   - 30 sec extraits PTSD / X Art / Who Is Taki
   - 20 sec teaser M1 (key art animé) + DwP (mood board atmospheric)
   - 10 sec closer logo CG.STUDIO
   - À insérer en home page index.html + à uploader YouTube en pinned video

3. **Logo CG.STUDIO wordmark** (PRIORITÉ P1)
   - Brand mark visuel à créer
   - Cohérence cross-channels : header site / LinkedIn header / YouTube banner / fin de vidéos
   - Variantes : light (sur fond sombre) / dark (sur fond clair) / mono / favicon

4. **YouTube channel à alimenter** (PRIORITÉ P2)
   - Pinned video : sizzle reel studio
   - Playlist "Selected Works" : PTSD trailer + X Art trailer + Who Is Taki film
   - Playlist "IP in Development" : teasers M1 + DwP quand prêts
   - Cadence post-pitch MIPCOM à définir

5. **Page ip.html** — à vérifier (PRIORITÉ P2)
   - Statut actuel ? Page interne / archive / remplacée par les pages dédiées miss-one.html et die-with-peace.html ?
   - Si obsolète : archiver dans `99_ARCHIVE/` (à créer)

6. **LinkedIn strategy** (PRIORITÉ P2 — parallèle, plan media propre)
   - Calendrier 3 mois de posts personnels-stratégiques
   - Storytelling 40 ans de parcours + 2 IPs en dev
   - Cible : industry partners, diffuseurs, producers, talents

### Mission proposée prochaine session

[CEDY À CHOISIR — 1 priorité par session] :

**OPTION A** — Key arts IP Slate (P0)
Intégrer Miss One Hero Shot dans page miss-one.html + page index.html. Produire key art Die with Peace via brief MJ + Photoshop.

**OPTION B** — Sizzle reel script + storyboard (P1)
Script complet 60-90 sec, structure storyboard, identification des assets à monter (vidéo broadcast crédentiels + extraits œuvres + visuels IP). Brief pour montage.

**OPTION C** — Identité graphique CG.STUDIO (P1)
Brief de design : wordmark logo + déclinaisons (light/dark/mono/favicon) + guidelines couleur/typo applicables cross-channels.

**OPTION D** — Vérification page ip.html + sitemap (P2)
Status review, décision archive ou maintien, mise à jour sitemap.xml si suppression.

**OPTION E** — LinkedIn 3-month strategy (P2)
Calendrier éditorial + templates posts + cadence + métriques.

---

*Dernière mise à jour CLAUDE.md : 12 juin 2026 — review Cowork suite à analyse cross-projet (M1 + DwP) et diagnostic du site live cedricgodin.com.*
