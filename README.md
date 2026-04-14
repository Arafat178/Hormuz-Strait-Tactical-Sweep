# Hormuz Strait: Tactical Sonar Sweep V3

A tactical mine-clearance simulation and strategy game set in the strategically vital **Strait of Hormuz**. This project merges geospatial visualization with classic logic-puzzle mechanics, developed with a focus on lightweight performance and mobile accessibility.

## Project Vision
The Strait of Hormuz is a critical maritime chokepoint. This project transforms its complex topography into a tactical "sonar sweep" simulation. It uses real satellite imagery analysis to generate a playable grid, challenging the user to secure the waterway from underwater threats.

##  Key Features
- **Topographical Radar Scan:** Uses an automated image-processing algorithm to detect water geometry from satellite maps and generate the game grid dynamically.
- **Sonar Sweep Ability:** A strategic tool that reveals safe sectors using a simulated sonar pulse.
- **Mobile Optimized:** Full support for touch gestures, including **Pinch-to-Zoom** and **Drag-to-Pan** for seamless navigation on smaller screens.
- **Tactical UI/UX:** A high-contrast, military-grade interface featuring real-time mine counters, mission timers, and mode toggles (Dig/Flag).
- **Synthetic Audio Engine:** Implements the **Web Audio API** to generate real-time oscillators for sonar pings, clicks, and tactical feedback without external audio files.

##  Technical Implementation
This project is built using pure "Vanilla" web technologies, adhering to a straightforward, procedural logic flow for better maintainability and performance:
- **Languages:** HTML5, CSS3, JavaScript.
- **No Frameworks:** Developed without external libraries or OOP overhead to ensure maximum execution speed.
- **Algorithms:** - **BFS (Breadth-First Search):** For recursive cell clearing.
  - **Custom Image Processing:** Canvas-based RGB analysis to distinguish land from water.
  - **Transformation Matrices:** CSS-based scaling and translation for smooth pan/zoom mechanics.

##  How to Play
1. **Initialize Radar:** Open `index.html` in any modern browser.
2. **Scan Sectors:** Use **DIG mode** to clear water cells. Avoid hidden mines.
3. **Deploy Markers:** Switch to **FLAG mode** or right-click to mark suspected mine locations.
4. **Utilize Sonar:** If stuck, use the limited Sonar charges to reveal safe paths.
5. **Mission Success:** Clear all safe water cells to secure the strait.

##  Project Structure
- `index.html`: The core application containing the engine, styles, and logic.
- `hormuj.jpg`: The satellite reference map used for grid generation.

##  Author
**Arafat Hossain (Rumun)**
*Mechanical Engineering Student, BUET*

---
*"Engineering the future, one line of code at a time."*
