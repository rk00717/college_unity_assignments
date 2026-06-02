# college_unity_assignments
**Unity 2D · December 2021**

Collection of Unity assignments from college game design coursework. Four assignments covering progressively more complex systems — movement, physics, UI, and asset integration.

---

## Assignment 1 — 2D Platformer

A side-scrolling 2D platformer with physics-based movement, collectibles, hazards, and a camera system that anticipates player direction.

**Features:**
- Double jump with configurable max jump limit
- Camera that offsets ahead of the player based on movement direction — flips side on direction change for better forward visibility
- Parallax background scrolling
- Collectibles with animation controllers (fruits)
- Health system — spikes deal damage, trampolines interact with physics
- Sprite flip on direction change via `localScale.x * -1`

**Scripts:** `PlayerMovement`, `CameraMovement`, `HealthManager`, `Collectible`, `Spike`, `Trampoline`, `ParallaxBG`

---

## Assignment 2 — Physics Jump

Basic jump mechanic exploration. Single script controlling jump force via Rigidbody2D impulse, single jump with ground collision reset, void trigger detection.

**Scripts:** `playerMovement`

---

## Assignment 3 — UI & Scene Management

UI-focused assignment using the HONETi mobile cartoon GUI asset pack. Implements scene switching via button-driven `Application.LoadLevel`. Includes achievement sprites, custom cursors, and a multi-scene structure.

**Scripts:** `switch_scenes` (imported — HONETi)

---

## Pixel Adventure 1

Asset integration and scene building exercise using the Pixel Adventure asset pack. Focused on scene composition and asset pipeline rather than custom scripting.

---

## Stack

Unity 2D · C# · Rigidbody2D · Animator · Physics2D
