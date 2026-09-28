 # SpendWise Dashboard Shell

## Project Description
SpendWise is a responsive personal finance dashboard that displays monthly budgets, expenses, savings, and financial categories using a modern dashboard layout.

## Features
- Sidebar navigation menu.
- Header with dashboard title and user profile.
- Summary cards showing total budget, total spending, and remaining balance.
- Six financial category cards: Food, Transport, Rent, Entertainment, Savings, and Utilities.
- CSS Grid for the overall page layout and category cards.
- Flexbox for arranging content inside the header, sidebar, and cards.
- Responsive single-column layout for screens below 768px.
- CSS custom properties for consistent colors and theming.
- Hover and keyboard focus animations on category cards.
- Dark theme using `prefers-color-scheme: dark`.

## Technologies Used
- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Custom Properties
- Media Queries

## Project Structure
```text
SpendWise/
├── index.html
├── style.css
└── README.md
```

## How to Run
1. Download or clone the project repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a web browser.
4. Alternatively, use the Live Server extension to preview the dashboard.

## Responsive Design
The dashboard uses a CSS media query at 767px to adapt the layout for smaller screens. The sidebar, summary cards, and category cards adjust to a single-column layout.

## Dark Theme
The dashboard supports dark mode using the `prefers-color-scheme: dark` media query, which overrides the CSS custom properties defined in `:root`.

## Author
Fredrick
