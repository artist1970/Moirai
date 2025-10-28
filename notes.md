🌌 Moirai — Asset Compilation v1.0
Directory Map + Core Asset Inventory
🏛️ /assets/
🖼️ /assets/images/
1. Textures (Procedural Layers)

Used by drawCanvas.js to build depth and painterly quality.

/assets/images/textures/
│
├── watercolor-grain.png
├── canvas-fiber.png
├── light-haze.png
├── ink-bleed.png
├── dust-overlay.png
├── nebula-swirl.png
└── gold-thread.png

2. Palettes (Visual References)

Optional small swatch images for documentation & preview.

/assets/images/palettes/
│
├── sunset-serenity.png
├── forest-whisper.png
├── dreamy-pastels.png
├── bold-contrast.png
└── lunar-reflection.png

3. Symbols (Archetypal Icons)

Used by the poetic generator for symbolic anchoring.

/assets/images/symbols/
│
├── moon.png
├── flame.png
├── dove.png
├── labyrinth.png
├── crown.png
└── tree.png

4. Sample Art (for README & demos)
/assets/images/sample/
│
├── spark-preview-01.png
├── spark-preview-02.png
└── spark-preview-03.png

🔤 /assets/fonts/

Serve all fonts locally — no CDN dependencies.

/assets/fonts/
│
├── SovereignAcademy-Regular.ttf
├── CinzelDecorative-Regular.ttf
├── Poppins-SemiBold.ttf
└── Inter-Light.ttf

🔊 /assets/sounds/

Ambient tones and optional UI feedback.

/assets/sounds/
│
├── spark-chime.mp3          # plays when new art is generated
├── ambient-glow.mp3         # gentle background hum
├── click-soft.mp3           # button feedback
└── pulse-tone.mp3           # optional meditation sound

🎞️ /assets/videos/ (optional aesthetic layer)

Background visuals for immersive experience.

/assets/videos/
│
├── aurora-loop.mp4
├── ink-flow.mp4
└── lightwaves.mp4

📜 /data/

Structured knowledge files for Moirai’s symbolic, poetic, and chromatic logic.

/data/
│
├── palettes.json
├── wordbank.json
├── templates.json
└── archetypes.json


palettes.json
Holds all named color palettes with emotional metadata.

[
  {"name":"Sunset Serenity","colors":["#FF6E3A","#FF8A59","#FFD1A4","#FFE1C6","#2C1B17"],"emotion":"warm","tone":"peaceful"},
  {"name":"Forest Whisper","colors":["#2E4E1F","#6B8E23","#A9C985","#D4EAC7","#E5F3DB"],"emotion":"calm","tone":"natural"},
  {"name":"Dreamy Pastels","colors":["#FADADD","#FFD9E8","#C9E4FF","#E2FFE2","#FFF0B3"],"emotion":"gentle","tone":"whimsical"}
]


wordbank.json
Contains categorized symbolic vocabulary:

{
  "emotions":["hope","sorrow","wonder","grace","melancholy","joy"],
  "elements":["fire","water","air","earth","light","shadow"],
  "symbols":["moon","flame","dove","tree","labyrinth","crown"],
  "verbs":["whispers","rises","lingers","flows","glows","awakens"]
}


templates.json
Defines poetic composition structures:

[
  "{symbol} {verb} through the {element} of {emotion}.",
  "A {emotion} {element} cradles the {symbol}.",
  "Beneath the {symbol}, {emotion} {verb} in silence."
]


archetypes.json
Links archetypes to emotion and palette:

{
  "phoenix":{"emotion":"rebirth","palette":"Bold Contrast"},
  "labyrinth":{"emotion":"mystery","palette":"Lunar Reflection"},
  "tree":{"emotion":"growth","palette":"Forest Whisper"}
}

⚙️ /scripts/
/scripts/
│
├── moirai.js          # Core logic: input → symbolic processing → art rendering
├── poetica.js         # Poetic text and caption generation
├── palettes.js        # Palette management and randomizer
├── drawCanvas.js      # Procedural art renderer (canvas)
├── ui.js              # Interface event handling, accessibility toggles
├── adminPanel.js      # Passcode, local settings, and controls
└── export.js          # PDF/Codex export and local archival

🧩 /tools/
/tools/
│
├── localCache.js      # Handles saving preferences, palettes, wordbanks
├── archiveExport.js   # Creates Codex/ARSHIF export packages
├── soundController.js # Controls ambient audio & UI soundscape
└── accessibility.js   # Visual scaling, high contrast, and keyboard navigation

📘 /styles/
/styles/
│
├── main.css
├── theme-dark.css
├── theme-light.css
└── accessibility.css

🧭 Core Files
index.html          # Main entry (UI + generator)
README.md           # Documentation
LICENSE.md          # PLERA Sovereign License v1.0
.gitignore          # Sovereign-optimized ignore list

🪶 Sovereign Notes

No CDN or third-party scripts — all assets hosted locally or via GitHub Pages.

All JSON files are editable — creators can expand vocabularies and palettes.

Procedural textures are optional — Moirai functions without them if offline.

No telemetry — zero outbound network requests.
