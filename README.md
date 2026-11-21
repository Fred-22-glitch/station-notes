<p align="center"><img src="docs/imagens/banner.png" alt="Station Notes: notes, canvas and mind maps for studying, on Windows and Android" width="100%"/></p>

<div align="center">

A note-taking app for studying: an infinite canvas for mind maps, sticky notes, arrows and freehand drawing, plus document-style text notes.
No account, no ads, no telemetry. Distributed by [OmniStation](https://omnistation.netlify.app).

[Download](https://github.com/Fred-22-glitch/station-notes/releases/latest) · [Website](https://omnistation.netlify.app/en/station-notes/) · [Changelog](CHANGELOG.md) · [Guide](docs/GUIDE.md) · [Privacy](docs/PRIVACY.md)

</div>

> Available in English, Spanish and Portuguese (⚙ → language).

## Windows

<p align="center"><img src="docs/imagens/windows.png" alt="Station Notes on Windows: mind map on the canvas" width="100%"/></p>
<p align="center"><img src="docs/imagens/windows-mais.png" alt="Text note in dark mode and the built-in guide on Windows" width="100%"/></p>

- **Installer:** `Station-Notes-Instalador-x.y.z.exe`. The installer isn't code-signed yet, so SmartScreen may warn you: *More info → Run anyway*.
- **Portable:** `Station-Notes-Portatil-x.y.z.zip`. Unzip and run `Station Notes.exe`.
- Windows 10 or 11, 64-bit. The study AI (Pro) runs on the PC with llama.cpp and uses the graphics card through Vulkan when it can.
- The installed version checks GitHub Releases for updates and installs them from inside the app (the installer is verified against the published SHA-256). The portable version opens the release page instead.

[**Download for Windows**](https://github.com/Fred-22-glitch/station-notes/releases/latest)

## Android

<p align="center"><img src="docs/imagens/android.png" alt="Station Notes on Android: canvas, text note, dark mode and menu" width="100%"/></p>

- **App:** `Station-Notes-x.y.z.apk`. Allow installing apps from unknown sources for your browser or file manager.
- Same features as the Windows version, adapted for touch: long-press the canvas to create a block, two fingers to pan and zoom, and the formatting bar sits above the keyboard.
- The study AI (Pro) needs 6 GB of RAM or more and runs on the device (on the GPU when the phone supports it).
- The app checks GitHub Releases for updates and installs them from inside the app.

[**Download for Android**](https://github.com/Fred-22-glitch/station-notes/releases/latest)

## Features

**Canvas**
- Sticky notes, rectangles, ellipses, frames (moving a frame moves what's inside it) and ready-made tables
- One gesture per action, the same with mouse and touch: click to select, drag to move, double-click to edit the text, double-click the background to create a sticky note
- Arrows with heads, colors, dashes, labels and draggable curves
- Freehand drawing with smooth strokes (thicker where the pen presses), highlighter, shapes and an eraser that only erases where it passes. Drawings live on their own layer and stay sharp at any zoom
- Palm rejection: a hand resting on the screen doesn't draw or move anything; two fingers together pan and zoom
- Everything snaps to the dot grid (hold Alt to move freely), alignment guides, minimap and search inside the canvas
- Presentation mode (one frame at a time, fullscreen)
- Undo/redo, duplicate, copy and paste between notes

**Text notes**
- Laid out as a document page (A4 width, margins); full width on phones
- 24 fonts, exact font size (8–96), line spacing, colors, highlighter, headings, lists, checklists, tables, images, quotes and code blocks
- Built-in spell checker on every platform (Hunspell, on-device): misspelled words get a red wavy underline. On desktop, right-click for suggestions; on Android the keyboard already corrects, so a long press just offers Ignore or Add to dictionary
- Dictation with the app's own panel (live text and a Stop button)
- Continuous scroll or book mode (side-turning pages)
- Links between notes (`[[` or Ctrl+K) and full-text search; renaming the note's top heading renames the note
- Selection menu (bold, italic, underline, strikethrough, color, highlight, link) and a `/` menu for blocks
- Note panel: heading outline, notes that link here and a study assistant that keeps AI summaries out of your text
- Ctrl+P to jump to any note, canvas or command
- Split view: a second note, canvas or PDF on the right; drag selected text onto a canvas to make a linked block
- PDF reader with selectable text: send an excerpt to a note (with the page number), a flashcard or the mistakes notebook
- Templates: lecture, summary, exam review, thesis chapter, exam study schedule, shopping list, to-do, checklist, meeting, journal, financial report, academic report and mind map

**Studying**
- Mistakes notebook: subject, topic, source, type of mistake, confidence, tags and date, plus questions with your answer, the right answer and an explanation. Search, filters and spaced review (1, 3, 7 and 14 days)
- Flashcards written by hand, from selected text or created by the study AI, with spaced repetition
- Mistakes notebook metrics (Pro): today's review goal, accuracy by subject and most common mistake types
- Quick quiz built from a note by the study AI, with wrong answers sent to the mistakes notebook
- Calendar: reminders, and dates and tasks written in your notes; tap a day to add a reminder or create a journal, meeting, class or to-do note for it
- Read aloud: the whole note or the selected text, using the device's voice, with the current word highlighted
- Word goals, tags, favorites and read mode (hides the toolbars)
- In-note search, back/forward between notes, multi-select to move or trash notes

**Data**
- Notes are stored as `.json` files in a folder you pick (the "vault"), with folders and subfolders you can drag notes into. "Open folder" opens it in your file manager
- LAN sync between up to 4 of your devices with a 6-digit pairing code: no server, no account, encrypted. Settings list every device in the group, and any of them can be removed
- Daily automatic backups, per-note version history with a side-by-side comparison, 30-day trash
- Export to PDF, Word, Markdown, HTML, PNG (canvas) and Obsidian `.canvas`
- Notebook-style PDF (lined paper) and a story-sized or square image of a note for sharing

## Themes

Each theme restyles the whole app (paper, shapes, fonts and details), not just the colors.

<table>
<tr>
<td align="center"><img src="docs/imagens/temas/caderno.png" width="270" alt="Notebook theme"/><br/><sub>Notebook</sub></td>
<td align="center"><img src="docs/imagens/temas/caderno-escuro.png" width="270" alt="Notebook theme, dark"/><br/><sub>Notebook (dark)</sub></td>
<td align="center"><img src="docs/imagens/temas/quadriculado.png" width="270" alt="Graph paper theme"/><br/><sub>Graph paper</sub></td>
</tr>
<tr>
<td align="center"><img src="docs/imagens/temas/cafe.png" width="270" alt="Coffee theme"/><br/><sub>Coffee</sub></td>
<td align="center"><img src="docs/imagens/temas/titanio.png" width="270" alt="Titanium and emerald theme"/><br/><sub>Titanium and emerald</sub></td>
<td align="center"><img src="docs/imagens/temas/herdado.png" width="270" alt="Heirloom notebook theme"/><br/><sub>Heirloom notebook</sub></td>
</tr>
<tr>
<td align="center"><img src="docs/imagens/temas/aquarela.png" width="270" alt="Watercolor theme"/><br/><sub>Watercolor</sub></td>
<td align="center"><img src="docs/imagens/temas/polaroid.png" width="270" alt="Polaroid theme"/><br/><sub>Polaroid</sub></td>
<td align="center"><img src="docs/imagens/temas/cyberpunk.png" width="270" alt="Soft cyberpunk theme"/><br/><sub>Soft cyberpunk (with a key)</sub></td>
</tr>
<tr>
<td align="center"><img src="docs/imagens/temas/sorvete.png" width="270" alt="Melted ice cream theme"/><br/><sub>Melted ice cream (with a key)</sub></td>
<td></td>
<td></td>
</tr>
</table>

**Linux:** builds are paused. The last one is [0.6.0](https://github.com/Fred-22-glitch/station-notes/releases/tag/v0.6.0) (`.deb` and `.AppImage`).

## Getting started

1. On first launch, pick a folder for your notes (you can skip this and do it later).
2. Right-click the canvas background (long-press on Android) and choose a block type.
3. Drag the dot on a note's edge to another note to connect them.

The full guide is in the app under **⚙ → How it works**, and in [docs/GUIDE.md](docs/GUIDE.md).

## Pricing

Station Notes is **free**, with no trial and no time limit: text editor, canvas, local vault, PDF reader, split view, standard export (Word, HTML, Markdown, PNG) and local network sync.

Station Notes Pro is a one-time personal key (no subscription) for your own devices. It adds the mistake notebook metrics and spaced review (1, 3, 7 and 14 days), the Soft cyberpunk and Melted ice cream themes, advanced export (notebook PDF papers, unbranded image, canvas for Obsidian) and the study AI that runs on the device, downloaded once from Hugging Face (Windows: Qwen3 4B via llama.cpp; Android with 6 GB of RAM or more: Gemma 4 E2B on the GPU via LiteRT-LM, or Qwen3 4B on the CPU): summary, main topics, quote wall, flashcards, quick quiz, study plan until an exam date and automatic mind map. Long notes can go through ChatGPT, Gemini or Claude with a ready-made prompt instead.

Buy it on the [website](https://omnistation.netlify.app/en/station-notes/). You get the activation key on screen and by email, and paste it under ⚙ → Station Notes Pro. It's checked offline; no account needed. Refunds within 7 days cancel the key, and the app goes back to the free plan without losing any notes.

## Support

If you'd like to support development beyond the key:

- **Ko-fi** (card or PayPal): https://ko-fi.com/glitch22f
- **Pix** (Brazil only): [payment link](https://nubank.com.br/cobrar/xx14o/6ade9685-dae0-492a-bbc8-c0c2d7317304), or in the app under ⚙ → Support Station Notes

## Privacy

No account, no ads, no analytics. Notes stay on your device and in the folder you choose. The app only goes online to check for updates (GitHub API), to download the study AI model if you ask for it (Hugging Face) and, with Pro active, to download the public list of refunded keys at most once a day; nothing about you or your notes is sent. Details in [docs/PRIVACY.md](docs/PRIVACY.md).

## Bugs and feature requests

Use [Issues](https://github.com/Fred-22-glitch/station-notes/issues/new/choose). Reports in English or Portuguese are fine.

## License

Station Notes is proprietary software: this repository contains releases and documentation, not source code. See [LICENSE](LICENSE).

Built with React, React Flow, TipTap, Tauri, Capacitor, Hunspell and Fontsource, among others. The full list of third-party licenses is in the app under ⚙ → Open source licenses.

<p><img src="docs/imagens/omnistation.svg" width="28" alt="" align="absmiddle"/>&nbsp; © 2026 <a href="https://omnistation.netlify.app">OmniStation</a></p>
