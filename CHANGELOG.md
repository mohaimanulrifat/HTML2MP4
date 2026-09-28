# What changed

## 1.1.0, 28 September 2026

Slide decks, PDF and PowerPoint.

- **Presentation mode.** A slide deck made with Claude Design is noticed by itself ("Slide deck detected: 18 slides") and filmed slide by slide, with each slide's animations and the Morph movements between slides. No Duration to set: each slide stays on screen long enough to read (or a fixed time you choose), and the total length is shown before you start. Several slides are filmed at once, so an 18-slide deck of two and a half minutes takes about two minutes.
- For decks made with other tools, choose Presentation mode and type the number of slides.
- **Export PDF**, for any HTML page. At its own size by default (one 16:9 page per slide for a deck), or on A4, A3, Letter or a custom size, scaled to fit. Text stays real text, links stay clickable, and the deck's own fonts go inside.
- **Export PowerPoint**, for slide decks. Every text is an editable text box and every shape a real shape, with the speaker notes and the deck's fonts inside. Shapes carry matching names, so PowerPoint's Morph transition animates them like the HTML.
- A "Make" row with Video, PDF and PowerPoint tick boxes: any mix, made in one run, in the queue too. Nothing is replaced without asking.
- The command-line tool has matching options: `--pdf`, `--pptx`, `--no-video`, `--mode`, `--slide-seconds` and more.
- Videos now carry full BT.709 colour labels, so every player shows the same colours.
- The "Save PNG" button under the preview has gone; the preview itself is unchanged.

## 1.0.0, 23 September 2026

The first public release.

- Turns animated HTML pages into MP4, or into transparent MOV for overlays.
- Every frame is drawn and photographed on a virtual clock, so a conversion gives the same result every time, on any PC.
- Animations that start part-way through the page, or that are created by a timer, run on their own clock rather than jumping to the end.
- The page's own sound is captured, including sounds built into the page, and a music track can be added with fade in and out.
- A queue converts a whole batch unattended, with progress and a time estimate.
- Preview any moment of the video as a still picture before converting.
- A tick box hides the playback bar and border that some design tools add around an exported page.
- Help menu: how to use, suggestions, problem reports, an update check that runs only when you click it, the logs and settings folders, third-party licences and the terms of use.
- A plain-language log, saved with each run.
- Everything needed is inside the app: open-source Chromium, ffmpeg and Python. Nothing to install.
