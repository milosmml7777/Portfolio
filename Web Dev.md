# Valroyal E-Commerce UI Design

![[images/web/Hero.png]]

Valroyal is a modern beauty e-commerce interface designed in Figma. The project focuses on a clean visual identity, a minimal color system, and a component-based layout optimized for product browsing and purchasing.

The interface emphasizes strong visual hierarchy, reusable UI components, and a consistent design language suitable for modern online storefronts.

---

# Design Process

Before designing the interface, a design system was defined to ensure visual consistency and scalability.

The following elements were planned before building the layout:

- Color palette and gradient combinations
- Spacing and layout grid
- Reusable UI components
- Product card structure
- Button styles and interaction states
- Typography hierarchy
![[Pasted image 20260319004853.png]]

This preparation helped maintain a consistent visual language across the entire interface.

Design system planning examples:

---

# Design Goals

The main goal of the project was to create a clean and visually appealing e-commerce interface that focuses on product discovery and conversion.

Key design goals included:

- Clear product hierarchy
- Minimal and consistent color palette
- Strong call-to-action elements
- Reusable UI components
- Product-focused layout

---

# Design System

## Color Palette

![[Pasted image 20260319004658.png]]

The interface uses **two primary colors**:

- Purple
- Lime Green

These colors are combined using gradients to create a recognizable brand identity while keeping the palette minimal.

Supporting colors include neutral backgrounds and soft shadows to keep the UI clean and readable.

---

# Interface Components

## Navigation Bar

The top navigation provides category browsing and product discovery.

Features include:

- Brand logo
- Category navigation
- Search bar
- Clean horizontal layout

---

## Hero Section

The hero section introduces the brand and encourages product browsing.

Elements include:

- Brand identity
- Marketing tagline
- Promotional message
- “Shop Now” call-to-action button
- Lifestyle image

---

## Product Cards

![[Pasted image 20260319003449.png]]

Reusable product card components display:

- Product image
- Category label
- Product name
- Price
- Add to cart button
![[Pasted image 20260319004756.png]]
Cards are designed for scalability and consistency across product sections.

---

## Product Sections

The homepage includes multiple product discovery sections:

- Most Popular
- New Products
- Discounted Products

Each section supports carousel browsing and promotes product visibility.

---

## Footer

The footer includes typical e-commerce functionality:

- Customer support links
- Company information
- Legal pages
- Social media links
- Newsletter subscription

![[Pasted image 20260319004819.png]]

---

# UX Considerations

The interface follows several key UX principles:

- Clear visual hierarchy
- Strong CTA contrast
- Consistent spacing and layout
- Product-focused browsing
- Familiar e-commerce interaction patterns

---
# Color System

The color palette was created using **Adobe Color** with a **complementary color scheme** to produce strong visual contrast while maintaining a cohesive brand identity.

Two primary colors were selected:

- Purple
- Lime Green

These complementary colors allow important interface elements such as buttons and highlights to stand out while keeping the overall design visually balanced.

Gradients combining the two primary colors are used throughout the interface to reinforce branding and create visual depth in key components such as call-to-action buttons.

Supporting colors include:

- Neutral background tones for readability
- Soft shadows for depth
- White product surfaces to keep the focus on products

![[Pasted image 20260319004915.png]]
---
# Tools Used

Design  
Figma

Color Tools  
Adobe Color

Concepts  
Component-based UI design  
Grid-based layout system  
Complementary color scheme

---

# What This Project Demonstrates

This project demonstrates:

- UI/UX design skills
- Design system planning
- Component-based interface design
- E-commerce layout architecture
- Consistent visual identity creation

---

# Fisherman Lane Runner - Browser Game

Fisherman Lane Runner is a browser-based arcade game built using HTML, CSS, and JavaScript with the Canvas API. The player controls a fisherman moving between lanes to collect rewards while avoiding obstacles. The project focuses on implementing core game programming concepts such as rendering systems, collision detection, particle effects, and asset management.

![[Pasted image 20260319010603.png]]

# Highlights

- Canvas-based rendering system
- Lane-based player movement mechanics
- Randomized object spawning with weighted probabilities
- Particle effects for visual feedback
- Floating score indicators
- Audio system with multiple sound effects
- Asset loading system for images and audio
- Game state management including win and lose conditions
![[fisherman.png]]
---

# Tech Stack

Frontend

- HTML
- CSS

Programming

- JavaScript

Rendering

- HTML5 Canvas API

Audio

- Web Audio / HTML Audio API
![[fishermanhit.png]]
---

# Core Systems

## Canvas Rendering System

All game visuals are rendered using the HTML5 Canvas API, including the player character, collectible objects, obstacles, and UI effects.

## Lane Movement System

The player moves between predefined lanes using keyboard input. This creates a simple but responsive movement system commonly used in arcade runner games.
![[deadfish.png]]
## Object Spawning System

Objects spawn randomly with weighted probabilities, creating varied gameplay where coins, gems, and obstacles appear at different rates.
![[heart.png]]
## Collision Detection

Collision detection is implemented using distance-based calculations between the player and falling objects.
![[coin.png]]
## Particle Effects

A simple particle system was implemented to create visual feedback when the player is hit or collects items.

## Floating Score Indicators

When collecting items, floating text appears showing the score gained, adding visual feedback and improving game feel.

## Audio System

Sound effects and background music are implemented using the browser Audio API, with support for overlapping sounds during gameplay events.
![[lose.png]]
## Asset Loading

Images and audio assets are loaded asynchronously before the game starts to ensure all resources are available when gameplay begins.

---

# Gameplay Mechanics

Players must:

- Move between lanes to collect coins and gems
- Avoid obstacles such as dead fish
- Maintain remaining lives while increasing score
- Reach a target score to win the game
![[win.png]]
---

# What This Project Demonstrates

This project demonstrates:

- Game development using the HTML5 Canvas API
- JavaScript-based game loops using `requestAnimationFrame`
- Collision detection systems
- Particle effect implementation
- Asset management and loading
- Interactive browser-based gameplay systems
![[diamond.png]]