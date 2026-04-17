# Insectiles: Apex Swarm Edition

A high-performance, zero-dependency "Survivor-like" roguelite game engine implemented in a single portable HTML file.

## Features
- **Procedural Audio:** Built-in multi-channel synthesizer for music and SFX using Web Audio API.
- **5 Playable Classes:** Mantis, Scarab, Black Widow, Wasp, and Moth—each with unique abilities and stats.
- **Deep Meta-progression:** Earn Amber to track progress and clear waves to unlock synergies.
- **Synergy System:** Combine specific upgrades to unlock powerful game-changing effects.
- **Zero Dependencies:** No external assets, images, or libraries. Everything is contained in one file.

## Technical Details
- **Engine:** Custom 2D Canvas engine with spatial partitioning and entity pooling.
- **Size:** ~85KB (Single HTML File).
- **Controls:** Supports Keyboard (WASD/Arrows + Space) and Mobile Touch (On-screen Joystick).

## Recent Session Summary (2024-04-17)
- **Audio Engine Patch:** Added dynamics compression and memory management (explicit oscillator disconnection).
- **Refactoring:** Completed a major "readability refactor" to expand cryptic v2.0 naming conventions into clear, maintainable identifiers.
- **State Audit:** Performed a global state survey to map dependencies for future modularization.
