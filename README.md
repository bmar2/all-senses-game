# all-senses-game
AME294-87373 Creating Games with AI

All-Senses Game — single-file HTML. It’s a ready-to-run interactive page that covers the five classic senses:

* Sight — pattern memory (color + shape tiles).

* Hearing — tone identification (generated with Web Audio; optional mic mini-game for loudness).

* Touch — vibration-pattern recognition (uses navigator.vibrate; mobile recommended).

* Smell & Taste — guided, self-reported prompts (browser cannot detect these; user follows safe prompts at their end).

Round flow, scoring, and simple UI/settings are included.

How to open and use it

* Open the canvas file in the editor (you can view, copy, or download the single-file HTML).

* Save the content to a file named all-senses-game.html and open it in a modern browser (mobile recommended for haptics).

* Microphone access is optional and local to your browser (used only for a simple loudness check). Vibration works on devices that support it.

Important notes & limitations

* Browsers cannot detect smell or taste. The game uses self-report prompts for those senses (safe items only — e.g., lemon, sugar, salt, coffee).

* Vibration requires a compatible device (mobile) and user consent.

* Microphone use requests permission; no audio data is sent anywhere — analysis is local only.

* For accessibility, I kept controls large, with high contrast and optional toggles for sound/vibration.
