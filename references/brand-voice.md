<!-- MARKETING-SKILL:CONFIGURED (last updated: 2026-11-06) -->
# Brand Voice & Marketing Preferences

> This file is the single source of truth every skill in this plugin reads
> before producing output. Edit it directly, or run
> `/marketing-skill:marketing-setup` for a guided conversational setup.
>
> The first line of this file is a machine-readable marker. Skills check it
> to decide whether onboarding is needed — leave it exactly as
> `<!-- MARKETING-SKILL:UNCONFIGURED -->` until you've actually set your
> preferences, then it will be updated automatically to
> `<!-- MARKETING-SKILL:CONFIGURED (last updated: YYYY-MM-DD) -->`.

## Priority Task
Publications Instagram et TikTok (pas de LinkedIn) qui amènent
des demandes de rendez-vous gratuits (bilan épargne), pour grossir l'actif
sous gestion.

## Content Types
Vidéos verticales courtes (Reels et TikTok) et carrousels (Instagram et
mode photo TikTok). Pas de LinkedIn.

## Project
- Nom : Sean, conseiller en épargne
- Ce que c'est : accompagnement en épargne et placements (CELI, REER,
  CELIAPP, REEE) pour particuliers et familles au Québec
- Pour : jeunes familles, travailleurs de 25 à 55 ans, futurs acheteurs
  d'une première maison, travailleurs autonomes
- Offre : bilan épargne gratuit de 20 minutes, sans engagement
- À éviter : promettre un rendement, comparer des produits nommés,
  nommer des concurrents, donner un conseil personnalisé dans un post

## Target Audience
Particuliers et familles au Québec qui veulent mettre de l'ordre dans
leur épargne mais n'ont pas de conseiller ou n'osent pas demander.

## Brand Voice & Tone
Français québécois simple, chaleureux, direct. Tutoiement. Pédagogique, jamais vendeur ni
alarmiste. Phrases courtes.

## Default Output Format
Accroche forte (1 ligne) + 3 à 5 lignes utiles + appel à l'action clair
vers un rendez-vous (commenter le mot-clé « BILAN »).

## Banned Words & Phrases
- « rendement garanti », « sans risque », « devenir riche »
- tout chiffre de rendement futur ou promesse de résultat
- « game-changer », « révolutionnaire »
- noms de concurrents

## Formatting Constraints
- Emoji : avec modération
- Style des titres : majuscule en début de phrase seulement
- Phrases courtes à moyennes
- Conformité : chaque publication doit être approuvée par la conformité
  de l'entreprise avant mise en ligne (règles AMF) ; information générale
  seulement, pas de conseil personnalisé.

## Do / Don't Examples
- Don't : « Placez avec moi et doublez votre argent ! »
- Do : « Un bilan de 20 minutes pour voir si votre épargne travaille vraiment pour vous. »

## Sonic Identity
Not yet configured. The sound of every video rendered for this project:
the same genre, tempo, key, and signature hook each time, so viewers start
to recognize it. `short-form-video` (or `/marketing-skill:marketing-setup`)
proposes two options with audio previews and saves your pick here; see
`references/sound-guide.md`. Once set, it looks like:

- Genre: tech
- Tempo: 112 BPM
- Key: C major
- Energy: 3 (of 5)
- Hook: 1 5 3 5 | 6 5 3 2
- Why: clean and optimistic, for technical buyers; no hype

## Visual Identity
Not yet configured. The look of every video rendered for this project:
its colors, a display font, and the logo and handle on the end card that
lands with the sonic logo, so every video looks like the same brand.
`short-form-video` (or `/marketing-skill:marketing-setup`) asks for it and
saves it here, and `scripts/video/brand.js` applies it to a page. Once
set, it looks like:

- Accent: #2f6fed
- Background: #0b1020
- Text: #f5f7ff
- Font: Space Grotesk
- Headline font: DM Serif Display (optional: the hook and text cards; add a weight, "Inter 800", for a family with several)
- Caution: #e0605a (optional: ~wrong~ words, struck through)
- Positive: #3fbf7f (optional: checkmarks and good outcomes)
- Logo: state/videos/assets/logo.png
- Handle: @yourbrand
- Character: state/videos/assets/mascot.glb (optional: the brand's own rigged 3D character, in place of the robot in 3D videos)

## Video Setup
Not yet configured. What a video can be made with: where videos get
posted (which decides 9:16 or 16:9), who presents them (you on camera,
your own 3D character, the plugin's robot, a realistic AI avatar, or no
presenter), a video whose style to follow, the paid tools you have, and
whose voice. `/marketing-skill:marketing-setup` or `short-form-video`
asks (see `references/video-setup.md`) and saves the answers here. Once
set, it looks like:

- Posted to: TikTok, Reels, Shorts (9:16); Reddit (16:9)
- Presenter: own character (see Character under Visual Identity)
- Style reference: /Users/me/Videos/launch-we-like.mp4
- Paid tools: HeyGen (avatars), Epidemic Sound (music)
- Voice: Kokoro af_heart
