# Design document - 3th of November

## Free the Blob!

Trapped in a lab, born to escape. Free the Blob home!

Blob is a strange alien mass accidentally brought to life by a reckless scientist. Now trapped inside their laboratory, it must escape through interdimensional portals to find its way home.

Unlike traditional 2D platformers, Blob cannot move itself, since it doesn’t obey Earth physics. The player, through the control of an external magnetic force that is the cursor, needs to modify the environmental factors of the level, spacing from wind currents to mad scientist’s boxes. The magnetic force is only pushing away the blob, and can be activated/disactivated through a click of a human mouse.

Blob is trapped in a big laboratory, so needs to escape different laboratory chambers. Each one is a contained space with one entrance, that is the Blob’s spawn point, and one alien exit, the portal that the Blob brothers are opening for him to escape. The levels will get more and more difficult: as you advance, new possibilities are opened for Blob. Early levels focus on simple navigation, while later levels combine multiple environmental elements, requiring strategic thinking and timing, making the game a 2D puzzle platformer.

While in the lab, the Blob might be exposed to different substances that can modify its density, from hardening, to sticking to the ground, or making him acid, but there’s blessing in disguise: the Blob might need to break and dissolve things or to stick to the floor to escape the level. Those modifications are not permanent, since Blob is an alien, and can last only in a predetermined time (more or less 10 seconds). Moreover, Blob can’t live in the human air for long, so all levels have a timer. If the Blob can’t reach the portal in that time, he will lose a heart. Luckily, as an alien, he has four hearts!

---

## Character

| Character | Lives | Powers |
|---|---|---|
| Blob | 4 hearts | Sticky, Rock, Acid, Fire |

---

## Design of the levels - see the PDF file for sketches

The first three levels will be designed to explain to the players the alien physics of the Blob.

**Level 1** will be simpler as ever, dedicated to only making him move from left to right.

**Level 2** will explain how Blob can gain the powers, and how much they can last.

**Level 3** will introduce the environmental difficulties that make the game a puzzle.

Starting from **Level 4**, the game transitions into a true puzzle-platform experience, gradually increasing in complexity and strategic depth. From this point onward, players are required to think more critically and plan each movement, as simple navigation is no longer enough.

The difficulty is driven by:
- Environmental interaction: obstacles, moving elements, and physics-based traps become more frequent and varied.
- Blob’s transformation states: players must understand when and how to use each temporary ability to progress, combining states in the correct order.
- Route planning and timing: levels begin to introduce sequences that must be executed in the right moment.

Each new stage adds an additional layer of challenge, so the gameplay has constant progression and keeps gameplay fresh. As players advance, they will face more complex layouts and multi-step puzzles that require increasingly precise control and strategic thinking to reach the portal and escape the laboratory chamber.

---

## Media list

### Visual identity

Blob is a bright acid-green color, staying true to the classic alien imagination. Small bubbles rise and pop across his surface, sometimes forming shapes that hint at playful facial expressions.

The visual style combines clean game assets with artistic background illustrations inspired by chaotic, experimental laboratories. Each level is constructed using modular elements such as lab shelves, test tubes, machinery, walls, and environmental obstacles.

All UI icons adopt a soft, gelatinous aesthetic consistent with Blob’s material properties. Their saturated tones ensure clear separation from the laboratory background, which is primarily composed of neutral grey industrial assets.

The main level timer uses a digital-style typeface in green, maintaining visual alignment with Blob’s core palette and emphasizing a technological, lab-controlled environment.

The secondary timers, those linked to Blob’s temporary transformations, each adopt a different color based on the specific ability, accompanied by a simple pictogram that communicates the effect at a glance.

### Interactions

Clicking triggers Blob’s transformation, activating an animation that temporarily alters his structure.

When navigating vertical surfaces or angled edges, Blob dynamically adapts his shape to match the environment's contours.

Activating the magnetic force produces a very subtle audio cue: a soft, white-noise-like sound that indicates the force is active.

Blob’s temporary states are communicated through visual changes in both shape and color:

- **Sticky**: turns orange, movement becomes slower and more elastic  
- **Rock**: becomes a compact brown block, more angular and heavier in appearance  
- **Acid**: remains green but becomes fluorescent with light vapor effects  
- **Fire**: turns red, with increased internal motion and energetic particle-like movement  

---

## Flow

The game features a main menu with standard navigation buttons:
- Start
- Levels
- Settings
- Audio on/off
- Credits?

On the player’s first session, selecting Start launches an introductory sequence presented as a virtual comic. This sequence briefly narrates the origin story:

- In a mad scientist lab…  
- A mad scientist concludes his experiment!  
- But nothing happens.  
- Later, Blob is hanging out with friends.  
- And now, is teleported to this strange place!!! Help Blob escape!

On subsequent sessions, selecting Start resumes gameplay from the most recently saved level.

Levels unlock sequentially; each stage becomes available only after completing the previous one. The Level Select menu displays progression and allows players to replay any previously completed level.

At the last level, when completed, it launches another virtual comic sequence:
- Blob finally found the portal by recreating the experiment;
- Blob says goodbye to the lab;
- And returns to hanging out with friends!
