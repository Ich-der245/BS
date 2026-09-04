# Mini-Brawl 🥊💥

An action-packed 2D top-down shooter game inspired by Brawl Stars, featuring Shelly vs Shelly brawl gameplay built with HTML5 Canvas and JavaScript!

## 🎮 Features & Gameplay Highlights

- **Dual-Stick & Desktop Controls:**
  - **Left Joystick / WASD / Arrow Keys:** Movement
  - **Right Joystick / Mouse Click:** Aim & Shoot
  - **Auto-Aim:** Tap right joystick briefly or click near enemies
  - **Super Ability (Ulti):** Charged by dealing damage; trigger with the **SUPER** button or **E** key to fire a heavy wall-destroying shotgun blast.
  - **Pause / Restart / Sound:** Press **P** to pause, **R** to restart, **Enter** to resume, and use the topbar sound button to toggle audio.

- **Mechanics:**
  - **Sequential Ammo Reload:** Ammo reloads slot-by-slot (0.8s per bullet) so you can fire immediately when 1 bullet is ready.
  - **Item Drops:** Enemies drop **Power Cubes** (+Damage & Max HP) and **Health Packs** (+HP recovery) on defeat.
  - **Obstacles:** Indestructible by regular shots, but crushable by Super shotgun blasts!
  - **High Score Tracking:** Persistent high score saved to `localStorage`.

- **Web Audio API Synthesizer:**
  - Procedurally generated sound effects for shooting, super blasts, enemy hits, reload ticks, powerups, wave completions, and game over.

- **Visual Polish:**
  - Custom canvas particle engine for muzzle flashes, impact sparks, item pickup effects, floating damage text (`-16`, `+35 HP`), and screen shake!

- **PWA Support:**
  - Service Worker (`sw.js`) and Web App Manifest (`manifest.json`) for full offline capability and standalone installation.

## 🚀 How to Run

1. Open `index.html` in any modern web browser.
2. Click **Spielen** or press **Enter** to start!
