# 📅 Weekly Meeting Availability Table

A responsive **Weekly Meeting Availability Table** built with **HTML and CSS** as part of the FreeCodeCamp curriculum.

The project displays the availability of people for meetings throughout the week using a color-coded table. Different colors represent different availability levels, while borders distinguish between different types of time rows.

## 📸 Project Overview

The table shows meeting availability for different days and times during the week.

Each availability level is represented by a different color, making it easy to identify when more or fewer people are available.

### ✨ Features

* 📅 Weekly meeting schedule
* ⏰ Time-based availability
* 🎨 Color-coded availability levels from `0` to `5+`
* 📊 Semantic HTML table structure
* ♿ Accessible `aria-label` attributes
* 🎨 CSS custom properties for colors and borders
* ➖ Solid and dashed borders for different rows
* 🌈 Gradient-based availability legend
* 📱 Responsive design

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* CSS Variables
* CSS Linear Gradients
* HTML Tables
* Accessibility Attributes
* Responsive Design

## 📂 Project Structure

```text
Availability-Table/
│
├── index.html
├── styles.css
└── README.md
```

## 🎨 Availability Levels

The table uses six availability levels:

| Class         | Meaning      |
| ------------- | ------------ |
| `available-0` | 0 available  |
| `available-1` | 1 available  |
| `available-2` | 2 available  |
| `available-3` | 3 available  |
| `available-4` | 4 available  |
| `available-5` | 5+ available |

Each level has its own CSS variable:

```css
:root {
  --color0: #f4cccc;
  --color1: #f6b26b;
  --color2: #ffe599;
  --color3: #b6d7a8;
  --color4: #76a5af;
  --color5: #6fa8dc;

  --solid-border: 2px solid;
  --dashed-border: 2px dashed;
}
```

## 🌈 Availability Legend

The project includes a legend that visually represents the availability range from `0` to `5+`.

```html
<div id="legend">
  <span>Availability</span>
  <div id="legend-gradient"></div>
</div>
```

The gradient uses hard color transitions between each availability level.

## ♿ Accessibility

The table uses semantic HTML elements such as:

* `<table>`
* `<caption>`
* `<th>`
* `<td>`

Table headers also use the appropriate `scope` attributes:

```html
<th scope="col">Monday</th>
```

Time headers use:

```html
<th class="time" scope="row">9:00 AM</th>
```

Availability cells include descriptive `aria-label` attributes:

```html
<td class="available-3" aria-label="3 available"></td>
```

This makes the availability information more accessible to users who rely on assistive technologies.

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/availability-table.git
```

2. Open the project folder.

3. Open `index.html` in your browser.

No additional dependencies are required.

## 🎓 Learning Objectives

This project helped me practice:

* Creating accessible HTML tables
* Using table headers and captions
* Working with `scope` attributes
* Using CSS custom properties
* Creating color-coded data
* Working with CSS gradients
* Creating hard transitions in gradients
* Styling elements based on parent classes
* Using `aria-label` for accessibility
* Building responsive layouts


This project was created for educational and learning purposes as part of the FreeCodeCamp curriculum.
