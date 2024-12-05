# RealmRender

**RealmRender** is an advanced 2D map generation tool designed for worldbuilders, writers, game developers, and anyone passionate about crafting immersive worlds. The program leverages real-world geographical and environmental principles to create realistic maps with features like plate tectonics, ocean currents, climate zones, biomes, and atmospheric circulation. Future updates will include AI assistance, time manipulation, and exportable world data.

---

## Features
### Current Goals:
- **Realistic Map Generation**:
  - Landmass creation using plate tectonics.
  - Atmospheric circulation, wind patterns, and ocean currents.
  - Climate zones and biome distribution based on environmental factors.
- **Interactive Interface**:
  - User-friendly browser-based interface for real-time interaction.
  - Tools for customization and fine-tuning generated maps.
  
### Future Features:
- **AI Assistance**:
  - Helps users input specific parameters and generates realistic details, including:
    - Fictional minerals, flora, and fauna placement.
    - Civilization placement and historical growth simulation.
- **Time Manipulation**:
  - Move forward and backward through time.
  - Simulate geological and societal evolution.
- **Export Options**:
  - Generate PDFs containing maps and detailed world data.
  - Export raw data in formats like JSON or CSV for further use.

---

## Technologies
### Current Tech Stack:
- **Backend**: Python (scientific modeling, AI integration, PDF generation)
- **Frontend**: JavaScript (React, D3.js, Three.js for rendering maps)
- **Database**: PostgreSQL with PostGIS for spatial and temporal data management
- **Performance Optimization**: WebAssembly (Rust/C++ for intensive computations)

---

## Installation
### Prerequisites:
- **Python**: Version 3.8 or higher.
- **Node.js**: Version 16 or higher.
- **PostgreSQL**: Version 13 or higher (optional for local database testing).

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/austinlgraham/realmrender.git
2. Navigate to the project directory:
   ```bash
   cd realmrender
3. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
4. Install JavaScript dependencies:
   ```bash
   npm install
5. Start the development server:
   - Backend:
   ```bash
   python app.py
   ```
   - Frontend:
   ```bash
   npm start
6. Open your browser and navigate to `http://localhoost:3000`

---

### Contributing
We welcome contributions from developers of all skill levels! Here's how you can help:
1. **Fork the Repository**: Click the "Fork" button at the top of this page.
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/austinlgraham/realmrender.git
3. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/your-feature-name
4. **Make Your Changes**.
5. **Test Your Changes**.
6. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
7. **Submit a Pull Request**: Open a pull request against the `main` branch of this repository.

---

## Project Roadmap
1. **Phase 1: Core Map Generation**
   - Plate tectonics simulation.
   - Atmospheric and ocean current modeling.
   - Initial biome generation.
2. **Phase 2: AI-Assisted Inputs**
   - User-guided customization with AI-generated suggestions.
3. **Phase 3: Time Manipulation**
   - Dynamic timeline for world evolution.
4. **Phase 4: Export Functionality**
   - Generate PDFs and raw data exports.
5. **Phase 5: Advanced AI Features**
   - Realistic placement of fictional resources and civilizations.

---

## Get in Touch
If you’re interested in contributing, discussing ideas, or have questions, feel free to:
- **Submit an Issue**: Use the [Issues](https://github.com/austinlgraham/realmrender/issues) tab to report bugs or request features.
- **Email the Maintainer**: `austin.graham86@gmail.com`
- **Join the Community**: [https://discord.gg/PR4fJn9zDh]

---

## License
This project is licensed under the [MIT License](LICENSE).
