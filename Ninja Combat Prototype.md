 **Ninja Combat Prototype**

A fast-paced 2D ninja combat prototype built in Unity focused on responsive controls, fluid combo combat, and performance-optimized gameplay systems. The project emphasizes precise combat feedback, enemy behavior variety, and custom visual effects while maintaining smooth performance through deliberate system architecture and optimization strategies.

[![Watch Gameplay](https://img.youtube.com/vi/qmVGOYmdafA/maxresdefault.jpg)](https://youtu.be/qmVGOYmdafA?t=5)
# Highlights

- Responsive combat system with high combo potential
- Custom hit resolution system for combat interactions
- Enemy AI with varied attack behaviors and patterns
- Custom VFX and shader-based visual effects
- Hybrid player architecture combining a state machine with lightweight custom systems
- Performance optimization through object pooling and distributed AI updates
- Fully custom art and animation created for the project

---

## Tech Stack

**Engine**: Unity Engine

**Programming**: C#

**Graphics**

- Shader Graph
- Unity Particle System
- Post Processing

**Input**: Unity Input System

**Level Design**: Unity Tilemap Editor with autotile setup

**Optimization**

- Object pooling
- Frame-distributed enemy updates
- Hybrid gameplay architecture

---

## Core Systems

### Combat System

Designed a responsive combat system with a minimal control scheme that allows fluid chaining of attacks and high combo potential. Combat interactions are processed through a custom hit resolution system that manages damage, reactions, and combat feedback.

### Player Architecture

Implemented a hybrid gameplay architecture combining a **player state machine with custom lightweight systems**, allowing for flexible combat logic while maintaining strong runtime performance.

### Enemy AI

Created multiple enemy archetypes with unique combat behaviors, including:

- Teleporting enemies requiring precise parry timing
- Ranged enemies throwing shurikens
- Elite enemies with advanced attack patterns and projectile behavior
- AI decision logic determining whether enemies engage directly or maintain distance

[![Watch Gameplay](Images/Ninja/ninjaVariant.png)](https://www.youtube.com/watch?v=8LME_ft6VYs&t=1s)
# Highlights
### Boss Encounters

Boss enemies feature unique movesets and combat patterns, providing more complex encounters compared to regular enemies.

[![Watch Gameplay](Images/Ninja/ninjaElite.png)](https://youtu.be/5mba21l6NqM?t=12)
### Performance Optimization

Several performance techniques were implemented to maintain smooth gameplay:

- Object pooling used for hit effects and visual effects
- Enemy update scheduling where only **one enemy updates per frame**, distributing CPU load while keeping reaction delays unnoticeable
- Optimized gameplay systems designed to reduce runtime overhead

---

## Visual Systems

- Custom VFX created for combat feedback including slash effects and hit effects
    
- Shader Graph effects including:
    
    - Eye glow
    - Sword glow
    - Slash trails
- Particle effects such as blood and environmental effects (fireflies)
- Dynamic lighting effects including lanterns and fireplaces with variable intensity and size
- Parallax background system creating visual depth



---

## Audio

- Designed and implemented original sound effects for combat and gameplay feedback
- Audio cues for attack swings, hits, and death states for both player and enemies
- Sound effects synchronized with animations and combat events

---

## Environment & Level Design

- Tilemap-based level construction using Unity’s Tilemap Editor
- Autotile setup for efficient level building
- Hand-crafted art and animation assets created specifically for the project

---

## Input & Controls

- Implemented using Unity’s modern **Input System**
- Input actions mapped to gameplay commands for flexible control configuration
- Playtested with external players to validate responsiveness and usability

---

## Showcase

- Playtested by multiple players for gameplay feedback and balancing
- Demonstrated during a **Unity SGA showcase**, where the project received positive feedback from Unity developers