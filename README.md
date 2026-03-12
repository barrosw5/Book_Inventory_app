# Book Inventory App

A clean and organized web interface designed to manage and display a personal collection of books.

## Description

This project showcases a structured approach to presenting tabular data using HTML5 and CSS3. The application functions as a visual inventory where books are categorized by title, author, and genre, while providing immediate visual feedback on their reading status and personal ratings.

The core focus of this repository is to demonstrate proficiency in:
- Semantic HTML table structure.
- Advanced CSS selectors, including attribute selectors (e.g., `tr[class="read"]`) and pseudo-classes (`:nth-child`).
- Dynamic UI feedback through color-coded status indicators (Read, To Read, In Progress).
- Custom visual components, such as a star-less rating system built entirely with CSS shapes and gradients.
- Layout management using linear gradients to improve readability and aesthetic appeal.

## Features

- Automated Status Highlighting: Different background gradients are applied to table rows based on the book's current status.
- Custom Rating System: A visual 3-point rating scale implemented using nested spans and CSS logic.
- Status Badges: Distinctive pill-shaped badges that help distinguish between different stages of reading.
- Responsive Table Logic: Designed to handle data display clearly across the horizontal axis.

## Technologies Used

- HTML5: Used for the semantic organization of the inventory list.
- CSS3: Used for the layout, custom component creation, and conditional styling based on classes and attributes.

## How to Use

1. Clone the repository to your local machine.
2. Open the `index.html` file in your browser.
3. Review the book list to see how different statuses (e.g., "In Progress" vs "Read") change the row's appearance.
4. Check the `styles.css` file to see how attribute selectors are used to apply specific styles without the need for excessive unique classes.

## Project Structure

- `index.html`: The main structure containing the book data and table elements.
- `styles.css`: The stylesheet containing all the visual logic, including gradients, status badges, and the custom rating system.
