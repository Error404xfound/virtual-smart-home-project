# virtual-home-system-game-project
Year: 2025-Present
By: Sean Esguerra, y1 polytechnic student (First self-initiated project!)
Status: Work in progress

It was originally supposed to be a virtual home system application , but after some coding, it seemed like it could be a better fit for a horror game

Progess:
Day 1:
-Brainstormed core concept: psychological horror rooted in memory, emotion, and minimalism
-Designed initial mechanics: text-based grid exploration, monster interactions, item system
-Wrote pseudocode for player movement, input handling, and early game loop
-Identified 3 core monsters with unique behavioral patterns (Erratic, Stillness, Spectre)

Day 2:
-Built initial 4x4 grid system and player movement
-Implemented JSON-based map loader with random room/lore generation
-Coded basic player input with input validation (non-numeric, out-of-bounds, empty entries)
-Started implementing turn-based structure (Remembering, Security Check, Item Check)

Day 3:
-Added core monster AI:
  Erratic: random movement, stuns when exposed to light
  Stillness: non-diagonal, slow-paced, punishes inaction
  Spectre: emotional trigger, responds to player movement
-Implemented lore-based item interactions (with slow print for tension)
-Created check_for_item() with optional dialogue and consequences

Day 4:
-Added light and audio systems:
  Light: costs energy, stuns Erratic, void peering mechanic
  Audio: randomized environmental horror cues
-Implemented energy management using batteries
-Added multiple win/loss conditions tied to exploration, clarity, and emotional resolution
-Added inventory and inspection system using item_lore dictionary
-Created secret peer mechanic unlocked by lighting system
-Refactored monster movement into collision-safe loop to prevent overlap
-Made monsters able to occupy same room as player with dynamic checks

Day 5:



