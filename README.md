# ColorPalette

**ColorPalette** is a modern, responsive one-page webapp that lets you:

- Generate **complementary**, **triad** and **analog** color palettes  
- Instantly **copy** colors, **check WCAG contrast**, and **save** named palettes  
- **Import/Export** your palette collection in JSON  
- **Load**, **Edit** or **Delete** saved palettes in a clean table  

All in a single HTML/CSS/JS file—no backend, no build step, fully GPLv3-licensed.

---

## 📺 Live Demo

https://bocaletto-luca.github.io/ColorPalette/index.html

---

## 🚀 Features

- **Palette Generator**  
  • HTML5 color picker for base color  
  • Auto-generate complementary, triad and analog schemes  
  • Click a swatch to copy its HEX code  

- **Contrast Checker**  
  • Pick two colors and see their WCAG AA/AAA ratio  
  • “Pass/Fail” indicator for accessibility compliance  

- **Saved Palettes Table**  
  • Name and save your generated palettes  
  • View base, complementary, triad (two), analog (two) in one row  
  • Load, Rename or Delete any palette  

- **Import & Export**  
  • Export entire table as a JSON file  
  • Import a JSON file to restore or replace your saved palettes  

- **Responsive & SEO-Friendly**  
  • Mobile-first, CSS Grid layout  
  • Meta tags for author, description, keywords  
  • GPLv3 license footer and GitHub link  

---

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)

### Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/bocaletto-luca/ColorPalette.git
   ```
2. Or download & unzip the ZIP from GitHub.

3. Open `index.html` in your browser.

---

## 🎯 Usage

### 1. Generate a Palette

1. Choose a **Base Color** with the top picker.  
2. See three swatch groups: **Complementary**, **Triad**, **Analog**.  
3. Click any swatch to copy its HEX code to the clipboard.

### 2. Check Contrast

1. Select **Color 1** and **Color 2** in the Contrast Checker panel.  
2. View the **WCAG AA** (≥4.5:1) and **AAA** (≥7:1) pass/fail status.

### 3. Save a Palette

1. Click **Save Palette** below the swatches.  
2. Enter a **name** for your palette.  
3. It appears in the **Saved Palettes** table.

### 4. Manage Saved Palettes

- **Load**: reapply that palette as your new base  
- **Edit**: rename the palette  
- **Delete**: remove it from storage  

### 5. Import & Export Table

- **Export JSON**: download your saved palettes  
- **Import JSON**: upload a previously exported file to restore  

---

## 🧰 Technologies

- HTML5 & CSS3 (Grid, Custom Properties)  
- Vanilla JavaScript (ES6)  
- LocalStorage for persistence  
- No external dependencies  

---

## 🤝 Contributing

1. Fork this repository  
2. Create a branch (`git checkout -b feature/MyFeature`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to the branch (`git push origin feature/MyFeature`)  
5. Open a Pull Request  

---

## 📄 License

This project is licensed under the [GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html).

---

## 👤 Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
- Live Demo: https://bocaletto-luca.github.io/ColorPalette/index.html
