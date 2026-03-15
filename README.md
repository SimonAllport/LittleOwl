# Little Owl

A side-scrolling platformer for iOS built entirely with Metal and Swift. Help Little Owl rescue Princess Sasha from the clutches of the King Rat and his army.

## Story

Princess Sasha has been captured by the rats! Guide Little Owl through 15 hand-crafted levels across forests, mountains, frozen ponds, and deep warrens to reach the King Rat's throne room and bring her home.

## Gameplay

- **Run and jump** through platforming levels filled with enemies, gaps, and collectibles
- **Stomp enemies** by landing on their heads — mice, rat guards, and the King Rat himself
- **Collect acorns** scattered throughout each level for bonus points
- **Hit question blocks** from below to reveal power-ups

## Power-Ups

- **Grow Acorn** — Makes Little Owl bigger, allowing her to take an extra hit
- **Conker Helmet** — A timed helmet that destroys enemies on contact
- **Ball of String** (Level 5+) — Summons a tuxedo cat companion. Little Owl rides on the cat's back with increased speed, and the cat auto-attacks nearby enemies with pounces and swipes. Lasts until you take damage.

## Levels

15 levels across unique themed environments:

1. Meadow
2. Twilight Forest
3. Mushroom Grove
4. River Crossing
5. Autumn Woods
6. Moonlit Path
7. Craggy Cliffs
8. Mist Hollow
9. Burnt Forest
10. Frozen Pond
11. Deep Warren
12. Stormy Peak
13. Thorn Thicket
14. Rat Fortress
15. Throne Room (Boss Fight)

## Technical Details

- Built with **Metal** GPU rendering — no SpriteKit, no Unity, no third-party engines
- Procedurally generated 1024x1024 texture atlas using CoreGraphics
- Multi-pass post-processing pipeline: HDR scene rendering, bloom extract, Gaussian blur, final composite with dynamic lighting
- Instanced sprite rendering for performance
- Procedural level generation with seeded randomness for deterministic layouts

## Requirements

- iOS 16.0+
- iPhone (landscape orientation)

## Built With

- Swift
- Metal / MetalKit
- CoreGraphics
- AVFoundation (audio)
