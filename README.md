# 🎮 UGS Files - Ultimate Game Stash 
 ![Version](https://img.shields.io/badge/UGS-v9.5.2-blue)
 ![Games](https://img.shields.io/badge/Games-3000%2B-brightgreen)
 ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
 ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
 ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
 ![Status](https://img.shields.io/badge/Status-Active-brightgreen)
 ![License](https://img.shields.io/badge/License-See%20Disclaimer-lightgrey)
 ![Themes](https://img.shields.io/badge/Themes-1000%2B-purple)
 ![Responsive](https://img.shields.io/badge/Responsive-Yes-blueviolet)
 ![Performance Mode](https://img.shields.io/badge/Performance%20Mode-Supported-orange)
 ![Music](https://img.shields.io/badge/Background%20Music-Supported-pink)

> A massive browser-based game launcher with thousands of games, customizable themes, UI sounds, performance controls, and a retro-inspired interface.
UGS Files (Ultimate Game Stash) is a browser game launcher designed to bring a huge collection of games together in one fast, customizable interface.

Built with HTML, CSS, and JavaScript, UGS focuses on simplicity, customization, and that classic game-menu feeling. 🕹️
<img width="3040" height="1413" alt="image" src="https://github.com/user-attachments/assets/cb8cf783-a33a-4969-a904-8758836e0225" />


---

## ✨ Features

### 🎮 Massive Game Library
- Thousands of games in one launcher
- Current library contains **3,000+ games**
- Fast game selection
- Built-in game searching
- Game IDs remain intact for reliable launching

### 🎨 Theme System
UGS includes a large collection of customizable themes.

Themes range from:
- 🕹️ Classic consoles
- 💿 Retro gaming
- 🌌 Space
- 🌲 Nature
- 💻 Operating systems
- 🌈 Color-based themes
- 👾 Arcade aesthetics
- 🧪 Experimental/glitch themes

Themes can be previewed before being saved.

Your selected theme is stored locally so it can persist between sessions.
<img width="2981" height="1361" alt="image" src="https://github.com/user-attachments/assets/1ba8e8b4-2a44-435d-9f52-d6eea772efc2" />


### 🔊 UI Sounds
UGS includes interface sound effects for a more game-like experience.

Sounds are integrated into the existing interface without interfering with game launching.

### 🎵 Background Music
UGS supports background music through:


music/background.mp3

The music system is designed to work independently from the UI sound effects.

⚡ Performance Mode

UGS includes a Performance Mode for lower-powered devices.

When enabled, expensive visual effects can be reduced or disabled, including:

Animations
Animated backgrounds
Blur effects
Glow effects
Transitions
Decorative animations

This can help reduce CPU/GPU usage on older hardware.

Performance Mode can be saved locally and restored automatically.

🔎 Game Search

Quickly find games without manually scrolling through the entire library.
<img width="3050" height="1410" alt="image" src="https://github.com/user-attachments/assets/b7261d0f-2b5e-4831-a28b-309fac25930e" />

🧠 Theme AI Lab

UGS also includes a custom Theme AI Lab for creating your own themes.

Describe the theme you want, generate it, preview it, and apply it directly to UGS.

Workflow:

Describe → Generate → Preview → Apply → Save

Custom themes can be created repeatedly, giving UGS effectively unlimited custom theme possibilities.

Generated themes can be saved and remain available after reloading UGS.

🧪 Theme Laboratory

Experiment with theme colors and create personalized UGS themes without modifying the original built-in themes.

🌀 Theme Roulette

Randomly discover themes from the massive UGS theme collection.

🧬 Theme Mutation

Create variations of existing themes while preserving their overall visual identity.

🗺️ Theme Universe

Explore themes through different visual styles and aesthetic groups.

🕰️ UGS Time Machine

Explore different visual eras and retro-inspired interface styles.

👾 Theme Boss Battles

Experimental visual themes designed to push the UGS interface into increasingly ridiculous territory.

🧿 Theme DNA

View the visual color palette and design characteristics of themes.

🌐 UGS OS Mode

A fake desktop-style UGS interface that runs entirely inside the browser.

📼 Retro Boot Sequence

Optional retro-inspired startup animation for UGS.
<img width="3035" height="1389" alt="image" src="https://github.com/user-attachments/assets/91e3cdce-7073-4dce-beee-6305185c04b2" />

🖱️ Custom Cursor

UGS includes a customizable SVG cursor.

Custom cursor colors
Live color preview
HEX/RGB color controls
Preview before applying
Apply/save functionality
Reset to the default/theme cursor color
Saved preferences

The cursor itself remains an SVG while its appearance can be customized.

📱 Responsive Interface

The launcher is designed to work across different screen sizes, including desktop and mobile-sized displays.
<img width="3058" height="1410" alt="image" src="https://github.com/user-attachments/assets/9cb7f975-f8d8-4f8d-a21e-01f930895f16" />


💾 Local Settings

UGS uses browser localStorage for settings such as:

Selected theme
Performance Mode
Music settings
Other interface preferences

No account is required for basic use.

🖥️ Tech Stack

UGS is intentionally lightweight.

HTML5
CSS3
JavaScript
Browser LocalStorage
External JavaScript resources for the game launcher

No large framework is required to run the main interface.

📁 Project Structure
UGS/
├── index.html
├── games.js
├── searchbut.js
└── music/
    └── background.mp3
index.html

The main UGS interface.

Contains the launcher UI, styling, theme system, settings, performance controls, music controls, and other interface functionality.

games.js

Contains the game's launcher data and game IDs.

searchbut.js

Provides search-related functionality for the game library.

music/background.mp3

Optional background music used by the UGS music system.

### UGS includes a customizable Quick Exit feature for instantly navigating away from the launcher.

Users can configure:

🔗 A custom destination URL
⌨️ A custom keyboard shortcut
💾 Persistent settings using localStorage

The URL and shortcut can both be changed directly from the UGS settings.

When the configured shortcut is pressed, UGS navigates the current browser tab to the saved destination.

This feature is fully customizable and designed to make switching between UGS and another user-selected website quick and convenient.
🎨 Customization

UGS was designed to be heavily customizable.

You can modify:

Colors
Fonts
Themes
UI effects
Sounds
Background music
Layout
Game library
Launcher behavior

The interface uses Pixelify Sans for its pixel-style appearance.

🚀 Running UGS

UGS is a client-side web project.

You can run it by opening:

index.html

in a modern web browser.

For the best experience, hosting it through a web server such as GitHub Pages is recommended.

🌐 Hosting

UGS can be hosted using services that support static websites.

For example:

GitHub Pages
Any standard web server
Local development servers

Because the project is primarily client-side, no traditional backend is required for the launcher itself.

⚙️ Performance

UGS is designed to run on a wide range of hardware.

For lower-powered systems:

Open the UGS settings.
Enable Performance Mode.
Reload the launcher if necessary.

This reduces the visual workload while keeping the main functionality intact.

🧩 External Resources

Some UGS functionality uses externally hosted JavaScript resources.

Current launcher resources include:

https://cdn.jsdelivr.net/gh/bubbls/ugs-singlefile@main/searchbut.js
https://cdn.jsdelivr.net/gh/bubbls/ugs-singlefile@main/games.js

These resources are used by the launcher and should remain unchanged unless the project is intentionally migrated.

🔐 Privacy

UGS does not require an account for normal use.

Local preferences are stored in the browser using localStorage.

UGS does not need a database or traditional backend for its core interface.

🛠️ Development Philosophy

UGS is built around a simple idea:

Make a giant game collection feel like an actual game console menu.

Instead of presenting thousands of games as a boring list, UGS focuses on:

Visual customization
Fast navigation
Retro-inspired design
Sounds and music
Performance controls
Simple game launching

The goal is to make opening the launcher feel like turning on a console. 🎮

📌 Project Status

UGS is actively being developed.

Current major systems include:

 Game library
 Game search
 Theme system
 Theme preview
 Theme persistence
 UI sounds
 Performance Mode
 Pixel-style interface
 Background music support
 Responsive interface
 Local settings

More improvements may be added over time.

⚠️ Disclaimer

UGS is a browser-based launcher/interface project.

Game files, external services, and third-party resources may be subject to their respective owners' licenses and terms.

UGS does not claim ownership of third-party games, trademarks, assets, or services.

Make sure you have the appropriate rights to use any game files or media you add to your own installation.

⭐ Credits

UGS builds upon existing open-source/web resources and external launcher components.

Special thanks to the developers and contributors whose work makes projects like this possible.

🎮 UGS

Thousands of games.
One launcher.
Your setup.

🕹️ Ultimate Game Stash
