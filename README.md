# Word-Hunter-Ultimate
Word Hunter Ultimate is a premium, mobile-responsive word search puzzle game built entirely in a single HTML5 file. It leverages modern web technologies and the Gemini 2.5 Flash API to provide an endless, AI-powered gaming experience.
Core Gameplay Mechanics

Dynamic Grid Generation: A custom-built algorithm places words in various orientations (horizontal, vertical, diagonal) while ensuring no overlaps break the puzzle integrity.

Touch-First Interaction: Features a smooth, "drag-to-select" interface optimized for mobile touchscreens and desktop mouse inputs.

Smart Validation: The engine checks for words in both forward and reverse directions, allowing for advanced "Hard Mode" layouts.

2. Key Features

🎮 Game Setup & Customization

Difficulty Scaling: Three distinct grid sizes: Easy (8x8), Medium (12x12), and Hard (15x15).

Volume Control: Choose to search for 8, 12, or 15 words per session.

Curated Themes: Standard categories including Programming, Food, Countries, Animals, and Sports.

✨ AI Integration (Gemini 2.5 Flash)

Magic Theme Generator: Users can type any topic (e.g., "90s Sci-Fi" or "Rare Tropical Fruits"), and the AI generates a custom, relevant word list on the fly.

Ask AI Clues: If a user is stuck, the "Ask AI" feature generates a clever, crossword-style riddle for one of the remaining hidden words without revealing its location.

💰 Monetization & Retention

Rewarded Ad Simulation: A built-in system that simulates a video ad experience. When users run out of hints, they can "watch an ad" to refill their hint bank, demonstrating a production-ready game economy.

3. Technical Specifications

Language: HTML5, CSS3, Vanilla JavaScript (ES6+).

UI/UX Framework: Custom CSS using Tailwind-inspired design tokens (Flexbox/Grid layouts, glassmorphism, and fluid typography).

API Usage: Integrates with the Google Generative AI SDK via REST for real-time content generation.

Architecture: A single-page application (SPA) model using a state-machine to handle screen transitions (Home, Customize, Game) without page reloads.

4. Visual Identity

The application uses a "Premium Dark/Light" hybrid aesthetic:

Primary Palette: Indigo (#6366f1) and Violet (#8b5cf6) gradients.

Feedback Loops: Success states (Green), Warning states (Amber), and Magic AI states (Pink).

Responsive Design: Utilizes clamp() and aspect-ratio to ensure the game board remains perfectly square and legible on everything from small iPhones to large desktop monitors.
