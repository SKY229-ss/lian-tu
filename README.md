# Lian Tu

A cheerful guitar girl for codex pets.

Directed and refined by [@SKY229-ss](https://github.com/SKY229-ss), with Codex assisting. This project presents the finished journey from a visual reference to an installable desktop companion.

<p align="center">
  <img src="media/jumping.gif" width="192" alt="Lian Tu waving gently with both feet planted">
  <img src="media/look-around.gif" width="192" alt="Lian Tu looking in sixteen directions">
</p>

<p align="center">A gentle greeting · Sixteen gaze directions</p>

**[Download the pet](downloads/lian-tu-v1.0.0.zip?raw=1)** · [Animation guide](docs/ACTIONS.md) · [Quality notes](docs/QUALITY.md)

## Design highlights

- Natural anime proportions, with a smaller head and longer body and legs.
- Expressive red and ivory feathered ears, red hair, golden eyes, and a brighter smile.
- A complete guitar, long gray tie, jacket, stockings, shoulder strap, and ribbons.
- Nine animation state slots and sixteen gaze directions.
- A gentle wave replaces the exaggerated jump, keeping both feet planted.

<details>
<summary>View the character design</summary>

![Lian Tu character design](media/character-design.png)

</details>

## Installation

Download and extract the package, then place its `lian-tu` folder in the Codex pets directory:

```text
~/.codex/pets/lian-tu/
├── pet.json
└── spritesheet.webp
```

If you use a custom `CODEX_HOME`, use `$CODEX_HOME/pets/lian-tu/` instead. You can also download this repository and run these commands from its root:

```sh
mkdir -p "${CODEX_HOME:-$HOME/.codex}/pets/lian-tu"
cp pet.json spritesheet.webp "${CODEX_HOME:-$HOME/.codex}/pets/lian-tu/"
```

Select **Lian Tu** in a Codex desktop app that supports custom pets.

## Animation previews

| Idle | Dragging right | Dragging left |
| :---: | :---: | :---: |
| ![Idle](media/idle.gif) | ![Running right](media/running-right.gif) | ![Running left](media/running-left.gif) |

| Awaiting a response | Working on a task | Reviewing results |
| :---: | :---: | :---: |
| ![Waiting](media/waiting.gif) | ![Playing guitar while standing](media/running.gif) | ![Inspecting the guitar](media/review.gif) |

[Explore all animations and their triggers →](docs/ACTIONS.md)

## Asset specifications

| Property | Value |
| --- | --- |
| Name / ID | Lian Tu / `lian-tu` |
| Sprite version | `spriteVersionNumber: 2` |
| Spritesheet | 1536 × 2288, transparent WebP |
| Grid | 8 columns × 11 rows |
| Cell size | 192 × 208 |
| Animation state slots | 9, including the jump-to-wave replacement |
| Gaze directions | 16, spaced at 22.5° intervals |

