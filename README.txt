# QuestFit: Realmwalker V3

An installable Progressive Web App (PWA) designed for Android phones including the Samsung Galaxy A32.

## Included
- 110+ curated challenges across Strength, Cardio, Mobility, Exploration, Wellness, Nourishment and Skill.
- Daily decks of 6, 8, 10 or 12 quests; randomized with category variety; daily rerolls; weekly campaign goals; challenge codex filters; custom quests.
- Safe, additive wellbeing/nourishment challenges. Fitness goals are adjustable and rewards are game mechanics, not medical advice.
- Character generator and sheet with race, class, alignment, six ability scores, combat values, saves, skills, notes and leveling.
- Training logs for reps, holds, walking, running, cycling and stretching.
- GPS walking tracker, distance-to-XP, map tile discovery, treasure caches and landmarks.
- Five fantasy merchant types with GPS-anchored virtual stalls, inventory and gold purchases.
- Boss contracts, optional timers, rewards and trophies.
- Separate inventory/equipment, spellbook, companion, stronghold, decor and trophy display.
- Local save, JSON export/import, offline service-worker caching.

## Install on Samsung Android
1. Host the contents of this folder on a secure HTTPS website (for example, a static hosting service).
2. Open that HTTPS address in Chrome on the phone.
3. Open Chrome menu (⋮) and choose **Install app** or **Add to Home screen**.
4. Launch QuestFit from the home screen. Allow location permission when you choose GPS tracking.

This ZIP is the PWA source package, not an APK. A secure HTTPS host is required for PWA installation and GPS. Once installed, most game features work offline; GPS depends on device/browser location services.

## Notes
- Save data stays in browser local storage on this device. Export backups regularly.
- Merchant locations are generated virtual game points near the first GPS location; they are not actual shops.
- GPS points are revealed when the phone moves enough to register a new location. GPS drift can affect distance and discovery.
- Character math is a lightweight D&D-inspired rules layer, not a complete implementation of D&D 3.5e.
