# Calculus II Exam Trainer

A self-contained web app for practicing Calculus II exam questions extracted from the PDF.

## Contents

```
calculus-trainer/
├── index.html          ← Main app (open this in a browser)
├── images/             ← 119 PDF page images (allpages-001.jpg ... allpages-119.jpg)
├── data/
│   └── questions_meta.json  ← 325 questions with correct answers
└── README.md
```

## How to Open

**Option 1 — Python (recommended):**
```bash
cd calculus-trainer
python3 -m http.server 8000
# Then open: http://localhost:8000
```

**Option 2 — Node.js:**
```bash
npx serve .
```

**Option 3 — VS Code:** Install "Live Server" extension → right-click `index.html` → "Open with Live Server"

> ⚠️ Do NOT open `index.html` directly by double-clicking — browsers block local file loading.
> You must use a local web server (any of the options above).

## Features

- **325 questions** across 8 topics
- Question images cropped directly from the PDF pages
- Click image to zoom full page
- Track correct / wrong / skipped answers
- Accuracy % and streak counter
- Shuffle mode per topic
- Keyboard shortcuts: ← → navigate, A/B/C/D answer, Space skip, Z zoom
- Jump to any question by number
- Filter by topic

## Topics (325 questions)

| Topic | Questions |
|-------|-----------|
| Complex Numbers | 39 |
| Multiple Integrals | 47 |
| Line Integrals | 40 |
| Surface Integrals | 38 |
| Vector Calculus | 41 |
| Series | 41 |
| Fourier Series | 35 |
| Differential Equations | 44 |
