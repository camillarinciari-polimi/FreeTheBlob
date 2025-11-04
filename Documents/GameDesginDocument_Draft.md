# Free the Blob!

Trapped in a lab, born to escape. Free the Blob home!

Blob is a strange alien mass accidentally brought to life by a reckless scientist. Now trapped inside their laboratory, it must escape through interdimensional portals to find its way home.

---

# Design Document - 3rd November

## Overview and vision statement

**Free the Blob!** is a 2D puzzle–platformer where the player does not directly control the protagonist. Instead, movement emerges from environmental manipulation and physics–based interactions.

Blob is a mysterious alien life-form accidentally summoned by a reckless scientist. Unable to move according to Earth’s physical laws, Blob cannot walk or jump, it reacts only to external forces.

The player uses a magnetic field, represented by the mouse cursor, to push and steer Blob while interacting with environmental elements including wind currents and lab objects.

Each level is a sealed laboratory chamber with one entry point and one interdimensional exit portal. As levels progress, new mechanics, hazards, and physics-altering substances are introduced. These substances temporarily modify Blob’s density and properties, allowing it to harden, stick, or dissolve objects, encouraging creative problem-solving. Levels are time-limited due to Blob’s inability to survive long in Earth’s atmosphere, and Blob has four hearts to attempt escape.

The game gradually evolves from simple navigation challenges to complex, hybrid puzzle-platforming scenarios that test timing, experimentation, and strategic thinking.

Free the Blob! aims to play platforming by shifting control from the character to the environment itself. Instead of moving the protagonist directly, players guide Blob by shaping forces, physics, and reactions around it, turning limitation into meaningful interaction and creativity.

The game seeks to deliver an experience that is playful and surprising, where curiosity and experimentation lead the way. As challenges evolve, players learn to read the environment, combine mechanics, and strategize timing to help Blob escape the lab and return home.

Importantly, Free the Blob! aims to be designed with accessibility in mind. Since the game requires no traditional keyboard input and relies solely on mouse interaction, it can be enjoyed by players who experience joint or motor limitations and may struggle with complex control schemes. By reducing physical strain and simplifying control, the game aims to provide a welcoming and inclusive experience without compromising depth or challenge.

Ultimately, Free the Blob! transforms physics, playful problem-solving, and accessibility-driven design into a new kind of platforming adventure, one that celebrates ingenuity, empathy, and the joy of guiding a tiny alien lifeform toward freedom.

---

## Gameplay

Blob does not move by itself. The player creates motion by pushing it with a magnetic cursor and modifying the environment.

**Core gameplay loop:**
`Observe environment → Push Blob using magnetic cursor → Interact with objects → Reach portal before time runs out.`

### Environmental Interaction
* Wind currents
* Moving platforms
* Breakable objects
* Climbing walls

### Transformation system:

Blob can temporarily change physical properties (10 seconds):
* **Sticky Blob:** clings to surfaces
* **Hard Blob:** heavy, breaks objects
* **Acid Blob:** dissolves obstacles
* **Fire Blob:** burns obstacles

### Time and lives
Each level has a timer due to oxygen exposure. Failure removes one heart (Blob has four).

### Difficulty progression
* **Level 1–3:** Movement basics
* **Mid-game:** multi-mechanic puzzles, timing
* **Late game:** precision + fast decision-making

### Player feedback
* Color shift when pushing Blob
* Blob squish/elasticity animations
* Subtle sound when force activates
* Heart UI changes

### Failure & Recovery
* Timer runs out → lose heart, restart level
* Blob dissolves/gets trapped → restart
* Quick reset button for accessibility?

---

The first three levels will be designed to explain to the players the alien physics of the Blob.

**Level 1** will be simpler as ever, dedicated to only making him move from left to right.

**Level 2** will explain how Blob can gain the powers, and how much they can last.

**Level 3** will introduce the environmental difficulties that make the game a puzzle.

Starting from Level 4, the game transitions into a true puzzle-platform experience, gradually increasing in complexity and strategic depth.

The difficulty is driven by:
* Environmental interaction
* Blob’s transformation states
* Route planning and timing

As players advance, they will face more complex layouts and multi-step puzzles that require increasingly precise control and strategic thinking to reach the portal and escape the laboratory chamber.

---

## Characters

There are no enemies in the story, only Blob. The mad scientist is seen only in the introductory sequence.

| Character | Lives | Attributes |
|---|---|---|
| Blob | 4 hearts | Sticky Blob, Rock Blob, Acid Blob, Fire Blob |

---

## Story

On the player’s first session, selecting Start launches an introductory sequence presented as a virtual comic. This sequence briefly narrates the origin story:

* In a mad scientist lab…
* A mad scientist concludes his experiment!
* But nothing happens.
* Later, Blob is hanging out with friends.
* And now, is teleported to this strange place!!! Help Blob escape!

On subsequent sessions, selecting Start resumes gameplay from the most recently saved level.

Levels unlock sequentially; each stage becomes available only after completing the previous one.

At the last level, when completed, it launches another virtual comic sequence:
* Blob finally found the portal by recreating the experiment
* Blob says goodbye to the lab
* And returns to hanging out with friends!

---

## World

The world is composed of a series of self-contained laboratory chambers. Each chamber functions as:
* a puzzle room with defined boundaries
* one spawn pod for Blob
* one interdimensional exit portal

Rooms follow a modular pattern system (reused tiles, equipment layouts, and environmental props).

**Tone:**
1. Playful sci-fi + chaotic experimentation
2. Warm comedic undertone
3. Slight captivity + urgency
4. Strange alien tech vs clumsy human equipment

---

## Media list

**Visual identity:**
Blob is acid-green with bubbling texture and playful expression hints.

Laboratory setting with modular props, test tubes, machines, and UI elements with gelatin-like visuals.

Timers and icons color-coded for clarity.

### Interactions
* Click to transform Blob
* Blob adapts shape to surfaces
* Magnetic force → subtle audio cue
* States visual cues:
  * Sticky: orange, elastic
  * Rock: brown, angular
  * Acid: fluorescent + vapor
  * Fire: red + energetic movement

---

## Flow

Main menu:
* Start
* Levels
* Settings

Intro shown only once, then skip to latest progress.

Last level unlocks the ending comic.

---

## Team

**Team leader:** Camilla Rinciari
**Member #1:** Jiazi Wang
**Member #2:** Han Xiao
**Member #3:** Kamila Mammadova
