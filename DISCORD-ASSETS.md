# Discord-sourced assets

Free-to-use assets from the **Creator Coaster** Discord guild (`public-assets` forum), collected
with `discofetch` and curated by hand. They are filed in the normal categories, not a folder of
their own — `images/` and `animations/` alongside everything else the API serves.

Every file was posted by its author with an explicit **no-credit-required** statement, and is
named `descriptive name__discord_author.ext` per the repo convention.

## Licensing

Each file stays under its original author's terms. The forum post said no attribution is
required, but that is the poster's claim about their own work — it does not extend to any
third-party IP that may appear in the file. Check before publishing.

## `images/`

### Weapons — 1920×1080 PNG renders
`weapon *__mahirglaciar12.png` — 9 custom Minecraft weapon renders (bows, axes, swords, shield,
crystal hammers). Post `1305559190168797264`.

### Thumbnails
- `thumbnail live announcement *__tobicraft_tamil.png`, `vertical stream screen purple armor
  avatar__tobicraft_tamil.png` — "Tobi is live" promo designs, 1920×1080 and 1920×2880.
  Post `1555390293094961182`.
- `thumbnail vs battle space nebula__mahirglaciar12.png` — character-vs-character thumbnail.
  Post `1325581796582228031` (*"you dont have to give credits to me… ENJOY"*).

That post's layered `.psd` sources were **left out**: the 74 MB one is the same design as the PNG,
and neither carried anything the PNG doesn't already show. The author had also uploaded a
Complementary Shaders config and shader pack — see the exclusion note below.

### Overlays
- `progress bar overlay static__remppuu.png` + two fill animations in `animations/`.
  Post `1322936600522526720`.
- `chart growth green area__remppuu.png` + its draw-on animation in `animations/`.
  Post `1324431264660586526`.

### Wordmarks
`minecraft wordmark stone lava *__iheartgamesyt.png` — fan-made Minecraft wordmarks.
Post `1324493533813411900`. These are unofficial fan logos; the Minecraft wordmark and logo are
Mojang/Microsoft IP — fine for personal use and thumbnails, but not for redistribution or
merchandise.

### Icons
`icon red monster shouting__mosh91124.jpg` — post `1365464938973233345`.

## `animations/`

- `jack in the box chest animation__deleted_user.mov`, `diamond armor display
  animation__deleted_user.mp4` — pixel-art chest pop-up and diamond armour display on chroma
  green. Post `1228016477416722626` (*"no credit required"*), from a since-deleted account.
- `netherite ingot animation__mosh91124.mov` — post `1365464938973233345` (*"no credits
  needed"*). Named for the post title, but the footage is a pixel-art **tank on a green field**.
- `progress bar fill animation__remppuu.mp4`, `progress bar timeline variant
  animation__remppuu.mp4` — 15 s each. Post `1322936600522526720`.
- `chart growth line draw animation__remppuu.mp4` — post `1324431264660586526`.

## Corrected attributions

Five files that were already in the repo under other names, several crediting the wrong person.
Author names verified against Discord; the old copies were removed in favour of these:

| Now | Was | Correction |
|---|---|---|
| `images/chart growth green area__remppuu.png` | `Images/image-40__jtsimms0265.png` | author is **remppuu**, not jtsimms0265 |
| `animations/chart growth line draw animation__remppuu.mp4` | `animations/stonks success green line.mp4` | author was not recorded at all |
| `animations/jack in the box chest animation__deleted_user.mov` | `animations/chest animation__nikogizz_.mov` | author is the **deleted OP**; nikogizz_ posted a different file in that thread |
| `animations/diamond armor display animation__deleted_user.mp4` | `animations/animation 2__nikogizz_.mp4` | same — nikogizz_ did not post this |
| `animations/netherite ingot animation__mosh91124.mov` | `animations/copy 9B5AF8CB-….mov` | author was right, filename was a CDN hash |

## Deliberately excluded

**Netflix footage.** Two files from post `1555390293094961182` are **not** included. The post was
labelled no-credit, but both are real Netflix film stills (visible NETFLIX watermark, live-action
cockpit footage). A poster's no-credit claim cannot license someone else's copyright, so shipping
these in a public repo would be a problem for whoever uses them:

- `3bCEoRC9.webp` — 498×280 Netflix cockpit still
- `k2IY3UDit7DAFYdyv.mp4` — 1.6 s clip of the same footage

**Complementary Shaders.** Post `1325581796582228031` also carried a `.zip` of OptiFine /
Complementary **Shaders** `.placebo` files plus a shader options file. That shader pack is
**third-party work by emilk**, ships no license file, and lists block IDs for ~130 other authors'
mods. Whoever posted it had no right to relicense it, so the zip is excluded. The options `.txt`
was dropped with it, being useless without the pack. Get both from the authors and follow their terms.

## Classifier caveat

`discofetch classify` filed two music posts as `no-attribution` when their own text asked for
credit (`"Please, credit the Deltacraft Channel"`, `"Credit me plz"`). Verify the OP text
yourself — the regex in `discofetch/attribution.py` misses a comma after "please" and only knows
a fixed list of nouns after "credit".

## Last updated

2026-10-05