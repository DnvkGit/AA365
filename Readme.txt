అక్షరాల అమరిక  — Telugu Word Jumble Puzzle
------------------------------------------------
Version: 1.0 (Final Hobby Edition)
Developer: [Your Name or Initials]
Date: [YYYY-MM-DD]

Description:
A Telugu word puzzle game designed for language enrichment and fun.
Users form words from jumbled syllables and then assemble the caption.
Each day or user session loads a different puzzle from /data/sets/.

Features:
• Zoomable cartoon with pan
• Daily or user-progress-based puzzles
• LocalStorage-based progression
• Pre/Inter/Post comment captions
• Meaning display after solving
• Noto Sans Telugu font for correct rendering
• Confetti celebration popup
• Help overlay with restart option

Tested on:
• Desktop (Chrome/Edge)
• Android (Chrome Mobile)

Usage:
Open `index.html` in any modern browser or host via:
    python -m http.server 8080
and access http://localhost:8080

Credits:
• Concept, design, and testing — [Your Name]
• Built with help from ChatGPT (OpenAI)
• Telugu script rendering: Noto Sans Telugu

License:
For personal, non-commercial hobby use only.

aksharala_amarika/
│
├── index.html              ← main interface
├── script.js               ← game logic
├── style.css               ← visual design
│
├── /data/sets/             ← all d001.json … d365.json puzzles
│
├── /fonts/                 ← NotoSansTelugu-Regular.ttf (for compound aksharas)
│
├── /images/                ← optional icons, backgrounds, confetti etc.
│
├── README.txt              ← version info, usage, and notes
└── LICENSE.txt             ← (optional, hobby use notice)
