# ChemiMate: AI-Powered Educational Animation App

**ChemiMate** is an AI-powered application that converts textbook content (text + diagrams) into animated educational videos. Designed for subjects like chemistry, the app helps students visualize chemical reactions and concepts by transforming textbook pages into engaging animations with voice narration.

---

> ## Features

* Upload a textbook page image
* OCR and diagram recognition
* NLP-powered understanding of chemical reactions
* Scene generation and animation scripting
* Voice narration using Text-to-Speech (TTS)
* Video generation for visual learning

---

> ## System Architecture

```
User Input (Image of textbook page)
        │
        ▼
OCR Engine -> Extracted Text + Diagrams
        │
        ▼
NLP Processor -> Reactions, Concepts, Steps
        │
        ▼
Scene Generator -> Structured animation script
        │
        ▼
Animation Engine (Manim/Blender)
        │
        ▼
TTS Narration + FFMPEG video generation
        │
        ▼
Output: Animated Educational Video
```

> ## Datasets and Resources

* [PubChem](https://pubchem.ncbi.nlm.nih.gov/)
* [CHEMDNER Corpus](https://biocreative.bioinformatics.udel.edu/tasks/biocreative-iv/chemdner/)
* [USPTO Chemical Reactions](https://github.com/nlp-ml/chemical-reaction-datasets)

---

> ## Contributing

If you're interested in contributing, open an issue or fork the repo! We welcome suggestions on improving OCR accuracy, NLP enhancements, or adding more animation templates.

---

> ## License

MIT License. Use it, build on it, and make education more visual!
