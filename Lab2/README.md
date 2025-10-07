# 🎨 Portfolio Styling – Lab Assignment 2

This project continues from **Lab 1** by adding external CSS styling to the `index.html` file from the previous folder.  
All design and layout improvements are managed through an external stylesheet located in this **Lab2** folder.

---

## 🧱 Folder Structure
WEB_DEVELOPMENT/
├── Lab1/
│ ├── index.html
│ ├── README.md
│ └── images/
│ └── profile.jpg
│
└── Lab2/
├── style.css
└── README.md

---

## 🧠 Objective
Apply external CSS to the Lab 1 HTML page and style all elements for a clean, responsive, and professional portfolio layout.

---

## ✨ Features Implemented
- Linked **external CSS stylesheet** using relative path `../Lab2/style.css`
- Implemented **Google Font (Poppins)**
- Applied **color theme** (Navy Blue, Light Blue, White)
- Added **sticky navigation bar** with hover effects
- Used **CSS box model** for spacing and alignment
- Styled **table** with alternating row colors and borders
- Customized **buttons** with border-radius and hover effects
- Added **Back to Top button** with fixed positioning
- Used **<hr>** separators for section clarity
- Maintained consistent font, spacing, and colors

---

## 🧰 Tools Used
- **HTML5** (from Lab 1)
- **CSS3**
- **Google Fonts (Poppins)**
- **Visual Studio Code**

---

## 🚀 How to Run
1. Open `WEB_DEVELOPMENT/Lab1/index.html` in a browser.  
2. Ensure your `style.css` is in `WEB_DEVELOPMENT/Lab2/`.  
3. Verify that the page loads with proper colors, fonts, and hover effects.  
4. Try scrolling and clicking the **Back to Top** button.

---

## 🧾 Notes
- Do **not** include inline or internal styles in HTML — all styles must come from `Lab2/style.css`.
- The CSS link in `index.html` should be:
  ```html
  <link rel="stylesheet" href="../Lab2/style.css">