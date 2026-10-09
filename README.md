# SpendWise Dashboard Shell

This project is a static dashboard shell built to match the SpendWise finance interface described in the assignment brief. It uses CSS Grid for the overall page layout and Flexbox for arranging the navigation, actions, and card content.

## What is included

- A left sidebar navigation panel
- A top header with a search box and primary action button
- Four summary statistic cards
- Six spending category cards with realistic static financial data
- Responsive behavior for smaller screen sizes
- Subtle hover and keyboard focus animations on interactive cards
- Dark mode support using a media query based on the system color scheme

## Files

### index.html
This file contains the dashboard structure. It defines the sidebar, header, summary cards, and category cards in a semantic layout.

### style.css
This file handles the visual design. It includes the theme variables, Grid/Flexbox layout rules, responsive breakpoints, and hover/focus micro-interactions.

### README.md
This file explains what the project is, what each file does, and how the dashboard is structured.

## Design approach

The page uses CSS custom properties on the root selector to define the application theme. Layout structure is implemented with CSS Grid on the main shell, while nested elements such as headers, nav items, and cards rely on Flexbox.

The dashboard is intentionally static, focusing on the visual shell requested for the capstone foundation rather than dynamic functionality.
