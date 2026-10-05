# discord-assets

Free-to-use assets sourced from the **Creator Coaster** Discord guild (`public-assets` forum),
collected with `discofetch` and curated by hand.

Every file here was posted by its author with an explicit **no-credit-required** statement.
Naming follows the repo convention: `descriptive_name__discord_author.ext`.

## Licensing

Each file stays under its original author's terms. The forum post said no attribution is
required, but that is the poster's claim about their own work — it does not extend to any
third-party IP that may appear in the file. Check before publishing.

Source post IDs are listed below so any file can be traced or re-verified.

## What is here

### Weapons & items — 1920×1080 PNG renders
`weapon_*__mahirglaciar12.png` — 9 custom Minecraft weapon renders (bows, axes, swords,
shield, crystal hammers). Post `1305559190168797264`, tagged no-credit.

### YouTube thumbnails
- `thumbnail_live_announcement_*__tobicraft_tamil.png` + `vertical_stream_screen_*` —
  "Tobi is live" promo designs, 1920×1080 and 1920×2880. Post `1555390293094961182`.
- `thumbnail_vs_battle_space_nebula__mahirglaciar12.png` — character-vs-character thumbnail,
  1920×1080. Post `1325581796582228031` (*"you dont have to give credits to me… ENJOY"*).

The post's layered `.psd` sources were **left out**: the 74 MB one is the same design as the
PNG above, and neither carried anything the PNG doesn't already show. The author had also
uploaded a Complementary Shaders config and shader pack — see the exclusion note below.

### Overlays & motion graphics
- `overlay_progress_bar_*__remppuu.*` — static PNG + two 15 s fill animations. Post `1322936600522526720`.
- `chart_growth_green_area__remppuu.png` + `chart_growth_line_draw_animation__remppuu.mp4` —
  neon-green area chart and its draw-on animation. Post `1324431264660586526`.

### Wordmarks
- `wordmark_stone_lava_grey__iheartgamesyt.png`, `wordmark_stone_lava_black__iheartgamesyt.png` —
  fan-made Minecraft wordmarks. Post `1324493533813411900`.

These are unofficial fan logos. The Minecraft wordmark and logo are Mojang/Microsoft IP —
fine for personal use and thumbnails, but not for redistribution or merchandise.

### Animations
- `animation_jack_in_the_box_chest__deleted_user.mov`, `animation_diamond_armor_display__deleted_user.mp4` —
  pixel-art chest pop-up and diamond armour display on chroma green. Post `1228016477416722626`
  (*"no credit required"*), from a since-deleted account.
- `animation_netherite_ingot__mosh91124.mov` + `icon_red_monster_shouting__mosh91124.jpg` —
  Post `1365464938973233345` (*"no credits needed"*). The MOV is named for its post title, but
  the footage is a pixel-art **tank on a green field**; the still is a red monster app icon.

## Renamed duplicates

Five of these files were already in the repo under other names, in several cases crediting the
wrong person. Verified against Discord and removed in favour of the correctly-named versions here:

| This folder | Old repo path | Correction |
|---|---|---|
| `chart_growth_green_area__remppuu.png` | `Images/image-40__jtsimms0265.png` | author is **remppuu**, not jtsimms0265 |
| `chart_growth_line_draw_animation__remppuu.mp4` | `animations/stonks success green line.mp4` | author was not recorded at all |
| `animation_jack_in_the_box_chest__deleted_user.mov` | `animations/chest animation__nikogizz_.mov` | author is the **deleted OP**; nikogizz_ posted a different file in that thread |
| `animation_diamond_armor_display__deleted_user.mp4` | `animations/animation 2__nikogizz_.mp4` | same — nikogizz_ did not post this |
| `animation_netherite_ingot__mosh91124.mov` | `animations/copy 9B5AF8CB-….mov` | author was right, filename was a CDN hash |

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

`discofetch classify` filed two music posts as `no-attribution` when their own text asked
for credit (`"Please, credit the Deltacraft Channel"`, `"Credit me plz"`). Verify the OP text
yourself — the regex in `discofetch/attribution.py` misses a comma after "please" and only
knows a fixed list of nouns after "credit".

## Last updated

2026-10-05