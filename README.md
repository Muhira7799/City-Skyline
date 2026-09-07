# 🌆 City Skyline

A responsive **City Skyline** built with **HTML and CSS** as part of the FreeCodeCamp curriculum.

The project uses CSS gradients, flexbox, CSS variables, and media queries to create a stylized city skyline with background and foreground buildings.

## 📸 Project Overview

The page displays a colorful city skyline during the day and automatically changes to a darker nighttime-style appearance on smaller screens.

### ✨ Features

* 🌇 Responsive city skyline design
* 🏢 Background and foreground buildings
* 🎨 CSS custom properties (variables) for colors
* 🌈 Linear and radial gradients
* 🪟 CSS-generated windows
* 📱 Responsive design using media queries
* 💻 Built entirely with HTML and CSS
* 🎯 No JavaScript required

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* CSS Variables
* Flexbox
* Linear Gradients
* Radial Gradients
* Repeating Gradients
* Media Queries

## 📂 Project Structure

```text
City-Skyline/
│
├── index.html
├── styles.css
└── README.md
```

## 🎨 CSS Concepts

This project demonstrates several important CSS concepts:

### CSS Variables

Building and window colors are stored as reusable variables:

```css
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
}
```

### Gradients

Different gradient types are used to create the sky, buildings, and windows:

```css
background: radial-gradient(...);
```

and:

```css
background: repeating-linear-gradient(...);
```

### Responsive Design

A media query changes the skyline colors when the screen width is smaller than `1000px`:

```css
@media (max-width: 1000px) {
  ...
}
```

This creates a darker appearance for smaller screens.

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/city-skyline.git
```

2. Open the project folder.

3. Open `index.html` in your browser.

No additional dependencies or installations are required.

## 🎓 Learning Purpose

This project was created as a practice project while learning **HTML and CSS** through the **FreeCodeCamp Responsive Web Design curriculum**.

It helped me practice:

* Structuring webpages with HTML
* Creating layouts with Flexbox
* Using CSS variables
* Creating shapes with CSS borders
* Working with gradients
* Building responsive designs
* Using media queries



This project is created for educational and learning purposes.
