# MoodBite — Mood-Based Food Finder

**MoodBite** is a modern, interactive food discovery and local restaurant finder web application designed with a vibrant **Neon Tokyo** aesthetic. It helps users discover what to eat based on their current mood, regional cravings (with a dedicated Thai regional flavor tuner), and nearby local shops through an intuitive swipe-based interface. Just like in Tinder.

---

## 📁 Project Structure

The repository is organized into distinct UI screens and design system documentation generated via Stitch:

```text
stitch_mood_food_finder/
├── moodbite_discover_swipe_deck/
│   ├── code.html        # Main swipe deck interface for discovering dishes
│   └── screen.png       # Visual reference / UI preview
├── moodbite_cravings_local_shops/
│   ├── code.html        # Local shops, street food, and nearby cravings view
│   └── screen.png       # Visual reference / UI preview
├── moodbite_mood_regional_thai_tuner/
│   ├── code.html        # Interactive mood & Thai regional flavor tuner
│   └── screen.png       # Visual reference / UI preview
├── moodbite_crave_match_celebration_purple_neon/
│   ├── code.html        # "It's a Crave Match!" celebration overlay/screen
│   └── screen.png       # Visual reference / UI preview
└── neon_tokyo/
    └── DESIGN.md        # Design system tokens, color palette, and typography guidelines
```

---

## ✨ Key Features & Screens

1. **Discover Swipe Deck (`moodbite_discover_swipe_deck`)**
   - Tinder-style interactive card stack allowing users to swipe right on dishes they crave or left to pass.
   - Displays dish imagery, flavor profiles, and quick tags.

2. **Mood & Regional Thai Tuner (`moodbite_mood_regional_thai_tuner`)**
   - Customize food recommendations based on your current mood and regional Thai culinary preferences (e.g., Central, Northern, Isan, Southern).
   - Fine-tune spice levels, flavor notes, and comfort vs. adventurous vibes.

3. **Crave Match Celebration (`moodbite_crave_match_celebration_purple_neon`)**
   - High-energy purple neon celebration screen triggered when a user matches with their ideal dish, providing quick actions to locate or order it.

4. **Local Shops & Cravings (`moodbite_cravings_local_shops`)**
   - Connects matched cravings with nearby restaurants, local stalls, and hidden gems.

5. **Neon Tokyo Design System (`neon_tokyo/DESIGN.md`)**
   - Defines the dark-mode-first UI, glowing purple/magenta/cyan neon accents, glassmorphic cards, and modern typography.

---

## 🚀 Getting Started

Because each screen is built as a standalone static prototype, no complex build step is required to preview the UI:

1. **Clone or extract** the `stitch_mood_food_finder` archive.
2. **Open any `code.html` file** directly in your web browser (e.g., Chrome, Firefox, Safari, Edge).
3. *(Optional)* Use a local development server such as VS Code **Live Server** or Python's built-in HTTP server for smoother navigation:
   ```bash
   npx serve stitch_mood_food_finder
   ```

---

## 🎨 Design & Styling

- **Theme:** Neon Tokyo (Dark Mode with vibrant purple & electric neon highlights)
- **Reference Previews:** Each feature folder includes a `screen.png` file showing the intended layout and visual fidelity. Refer to `neon_tokyo/DESIGN.md` when extending components or unifying the screens into a single-page application (SPA).

All of this, uses Google AI studio and Google sticth. In the future if you have an Android, you can actually host you own app
