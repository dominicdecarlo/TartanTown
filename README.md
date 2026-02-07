# 🐕 Scotty's Campus Tycoon

**A tiny campus management sim in under 13KB!**

## 🎮 Play

Build a thriving university campus for Scotty dogs! Manage dorms, labs, shops, and more to help your students graduate.

### Controls

- **Click** a tool, then **click/drag** on the grid to place buildings
- **👆 Select** tool lets you inspect buildings and Scotties
- **Click buildings** to view stats and upgrade them

### Buildings

| Building | Purpose |
|----------|---------|
| 🏛️ Hall | Town center - upgrade to unlock Library, Park, Bar |
| 🏠 Dorm | Houses Scotties, restores energy |
| 🔬 Lab | Study sessions - uses energy, progresses toward graduation |
| 🛒 Shop | Generates income, boosts happiness |
| 📚 Library | Alternative study location |
| 🌳 Park | Relaxation spot |
| 🍺 Bar | Income + happiness boost |

### Win Condition

Help Scotties complete **8 lab visits** + **8 shop visits** to graduate! 🎓

## 🔧 Technical Highlights

- **Single HTML file** - no dependencies, no build step
- **Procedural audio** - all sound effects generated via Web Audio API
- **Hybrid sprites** - Base64 for main tiles, Canvas2D procedural for unlockables
- **Pathfinding** - BFS algorithm for dog navigation
- **State machine AI** - Each Scotty has energy, happiness, and goals

## 📦 File Sizes

- Source: ~48KB
- Minified: ~29KB  
- **Zipped: 11.8KB** ✅

---

*Built for JS13K 2026* 🏆
