# Lecture 8 deck — design direction

Reader: the lecturer and the master's group, projected 16:9 and opened on phones afterwards.
Hero idea: a prompt is a specification. Every prompt on every slide is split into the same five colour-coded parts, so the anatomy is learned by repetition.

## Palette
| token | dark | light | role |
|---|---|---|---|
| --bg | #101317 | #F7F6F2 | background |
| --fg | #ECEEF1 | #14171C | text |
| --accent | #E8653F | #C9472A | kickers, progress bar |
| --c-role | #4C8EEA | #2A62C9 | prompt part: role |
| --c-task | #E8653F | #C9472A | prompt part: task |
| --c-ctx | #2FA77F | #16805C | prompt part: context / data |
| --c-ex | #9B79E0 | #7448C4 | prompt part: examples |
| --c-fmt | #B88A12 | #9A7206 | prompt part: output format |
The five part colours pass the dataviz validator (lightness band, CVD and normal-vision separation, contrast) in both themes. Each segment also carries a text label, so colour is never the only cue.

## Type
- Onest 400–800 for headings and text (made for Cyrillic; Kazakh letters pass fonts-check). Replaces Unbounded/Literata from seminar 2.
- IBM Plex Mono for prompts, code and labels (JetBrains Mono lacks Kazakh letters).

## Format
Fixed 1280×720 stage scaled to the window; under 760 px wide it reflows into a reading column with notes inline. Motion: only the title prompt assembling; off under prefers-reduced-motion.
