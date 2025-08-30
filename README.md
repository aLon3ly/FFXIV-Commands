# FFXIV-Commands

Chat commands for FFXIV RP.  
All commands are invoked as:

```
Caitlin <command> [args]
```

> Tip: On GitHub, press `t` to quick-search this page, or use the A–Z index below.

---

## Contents
- [Quick Reference](#quick-reference)
- [A–Z Index](#a–z-index)
- [Command Categories](#command-categories)
  - [Utility](#utility)
  - [Glamoursets](#glamoursets)
  - [Pose (Amborella)](#pose-amborella)
  - [Animations (Nightlife V3)](#animations-nightlife-v3)
  - [Non RP](#non-rp)
- [Conventions](#conventions)

---

## Quick Reference

| Command | Syntax | Short description |
|---|---|---|
| target | `target <t\|TargetName>` | Target your current or a named target |
| emote | `emote <name>` | Perform any emote |
| atease | `atease` | Perform `/atease` (usually `/embrace`) |
| strip | `strip [part]` | Apply glamour preset to remove gear (full if empty) |
| _color | `_color <variant>` | Dye current outfit |
| _disableAnimation | `_disableAnimation` | Disable emote animations |
| _noShoes | `_noShoes` | Same as `_strip shoes` |
| _nude | `_nude` | Same as `_strip` (full) |
| _reset | `_reset [mode]` | Reset mod states |

---

## A–Z Index

**A**: [atease](#atease)  
**C**: [_color](#color)  
**D**: [_disableAnimation](#disableanimation)  
**E**: [emote](#emote)  
**N**: [_noShoes](#noshoes), [_nude](#nude)  
**R**: [_reset](#reset)  
**S**: [strip](#strip), [_strip](#strip-1)  
**T**: [target](#target)

---

## Command Categories

### Utility

<details id="target">
<summary><code>target &lt;t|TargetName&gt;</code> — Target your current target or a named target</summary>

**Arguments:**
- `<t>` — Use the caller’s current target.
- `<TargetName>` — Explicit name.

**Examples**
```
Caitlin target <t>
Caitlin target Haurchefant
```
</details>

<details id="emote">
<summary><code>emote &lt;name&gt;</code> — Perform any emote</summary>

**Arguments:**
- `<name>` — Emote name.

**Example**
```
Caitlin emote hug
```
</details>

<details id="atease">
<summary><code>atease</code> — Perform <code>/atease</code> (usually the <code>/embrace</code> animation)</summary>

**Example**
```
Caitlin atease
```
</details>

<details id="strip">
<summary><code>strip [part]</code> — Apply glamour preset to remove gear (full strip if empty)</summary>

**Behavior:**  
- No argument → applies `_nude` to `<me>`.
- With a **part** (case-insensitive) → applies the matching preset(s) to `<me>`.

**Accepted parts & presets**
| Part (aliases) | Preset(s) applied |
|---|---|
| `feet`, `shoes` | `_noFeet` |
| `legs`, `pants` | `_noLegs` |
| `top`, `body` | `_noBody` |
| `hands`, `gloves` | `_noHands` |
| `head`, `gag` | `_noHead` |
| `earring`, `earrings` | `_noEarring` |
| `necklace` | `_noNecklace` |
| `ringR`, `ringRight` | `_noRingR` |
| `ringL`, `ringLeft` | `_noRingL` |
| `rings`, `ringB` | `_noRingL`, `_noRingR` |
| `bracelet`, `bracelets` | `_noBracelet` |

**Examples**
```
Caitlin strip
Caitlin strip shoes
Caitlin strip legs
Caitlin strip rings
```
</details>

---

### Glamoursets

Presets referenced by commands:

- `_bikini` / `_bikini1`
- `_bikini2`
- `_bunny`
- `_casual`
- `_casual2`
- `_catsuit1`
- `_catsuit2`
- `_catsuit3`
- `_comfy`
- `_comfy2`
- `_comfylatex`
- `_cursedsuit`
- `_sleep`
- `_slutsuit`
- `_whm`
- `_zipsuit1`
- `_zipsuit2`

---

#### Outfit Showcases

(Each outfit includes preview placeholders — replace with actual screenshots in `pics/screenshots/`.)

<details id="bikini">
<summary><code>_bikini</code> / <code>_bikini1</code></summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| (none) | Default bikini |

**Preview:**  
![Bikini Outfit](pics/screenshots/bikini.png)
</details>

<details id="bikini2">
<summary><code>_bikini2</code></summary>

**Preview:**  
![Bikini2 Outfit](pics/screenshots/bikini2.png)
</details>

<details id="bunny">
<summary><code>_bunny</code></summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| `latex` | Latex bunny suit |
| `leather` | Leather bunny suit |

**Preview:**  
![Bunny Outfit](pics/screenshots/bunny.png)
</details>

<details id="casual">
<summary><code>_casual</code></summary>

**Preview:**  
![Casual Outfit](pics/screenshots/casual.png)
</details>

<details id="casual2">
<summary><code>_casual2</code></summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| `normal` | Default casual |
| `lewd` | Lewd casual variant |

**Preview:**  
![Casual2 Outfit](pics/screenshots/casual2.png)
</details>

<details id="catsuit1">
<summary><code>_catsuit1</code></summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| `normal` / `covered` | Covered |
| `nipples` | Nipples exposed |
| `pussy` | Pussy exposed |
| `full` / `fully` / `all` / `exposed` | Fully exposed |

**Preview:**  
![Catsuit1](pics/screenshots/catsuit1.png)
</details>

<details id="catsuit2">
<summary><code>_catsuit2</code></summary>

**Variants:** (same as `_catsuit1`)  
**Preview:**  
![Catsuit2](pics/screenshots/catsuit2.png)
</details>

<details id="catsuit3">
<summary><code>_catsuit3</code></summary>

**Variants:** (same as `_catsuit1`)  
**Preview:**  
![Catsuit3](pics/screenshots/catsuit3.png)
</details>

<details id="comfy">
<summary><code>_comfy</code></summary>

**Preview:**  
![Comfy Outfit](pics/screenshots/comfy.png)
</details>

<details id="comfy2">
<summary><code>_comfy2</code></summary>

**Preview:**  
![Comfy2 Outfit](pics/screenshots/comfy2.png)
</details>

<details id="comfylatex">
<summary><code>_comfylatex</code></summary>

**Preview:**  
![Comfy Latex Outfit](pics/screenshots/comfylatex.png)
</details>

<details id="cursedsuit">
<summary><code>_cursedsuit</code> — ⚠️ Lewd/Restraint</summary>

**Preview:**  
![Cursed Suit](pics/screenshots/cursedsuit.png)
</details>

<details id="sleep">
<summary><code>_sleep</code></summary>

**Preview:**  
![Sleep Outfit](pics/screenshots/sleep.png)
</details>

<details id="slutsuit">
<summary><code>_slutsuit</code> — ⚠️ Lewd/Restraint</summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| `belt` | Belt restraint |
| `cuffs` | Cuffs restraint |

**Preview:**  
![Slut Suit](pics/screenshots/slutsuit.png)
</details>

<details id="whm">
<summary><code>_whm</code></summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| `normal` | Default WHM |
| `lewd` | Lewd variant |

**Preview:**  
![WHM Outfit](pics/screenshots/whm.png)
</details>

<details id="zipsuit1">
<summary><code>_zipsuit1</code> — ⚠️ Lewd/Restraint</summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| `black` / `normal` | Default black |
| `exposed` | Exposed |

**Preview:**  
![Zipsuit1](pics/screenshots/zipsuit1.png)
</details>

<details id="zipsuit2">
<summary><code>_zipsuit2</code> — ⚠️ Lewd/Restraint</summary>

**Variants:**  
| Subcommand | Notes |
|---|---|
| `transparent` / `normal` | Transparent |
| `exposed` | Exposed |

**Preview:**  
![Zipsuit2](pics/screenshots/zipsuit2.png)
</details>

---

### Non-Outfit Commands

<details id="color">
<summary><code>_color &lt;variant&gt;</code> — Dye current outfit</summary>

**Variants:**  
| Value | Effect |
|---|---|
| `none` / `reset` | Removes dye |
| `red` | Red dye |
| `black` | Black dye |
| `white` | White dye |

**Example**  
```
Cait _color red
```
</details>

<details id="disableanimation">
<summary><code>_disableAnimation</code> — Removes any animations bound to emotes</summary>

**Example**  
```
Cait _disableAnimation
```
</details>

<details id="noshoes">
<summary><code>_noShoes</code> — Alias for <code>_strip shoes</code></summary>
</details>

<details id="nude">
<summary><code>_nude</code> — Alias for <code>_strip</code> (full)</summary>
</details>

<details id="reset">
<summary><code>_reset [mode]</code> — Reset mod states</summary>

**Modes:**  
| Mode | Effect |
|---|---|
| (none) | Reset mod states |
| `full` | Complete reset |
| `strip` | Reset + `_strip` |

**Examples**
```
Cait _reset
Cait _reset full
Cait _reset strip
```
</details>

<details id="strip-1">
<summary><code>_strip [part]</code> — Remove gear parts</summary>

*(See [strip command](#strip) in Utility for full table of parts and usage.)*
</details>

---

### Pose (Amborella)

*(Commands will be listed here as we parse the scripts.)*

---

### Animations (Nightlife V3)

*(Commands will be listed here as we parse the scripts.)*

---

### Non RP

*(Nothing set up yet.)*

---
