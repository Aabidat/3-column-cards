# 3-Column Card Component

A 3-column vehicle category card component built with HTML and CSS as part of building my CSS foundations at hackerboost.

## Overview

I built this project to practice CSS layout techniques, specifically flexbox, and to create a visually consistent component with proper spacing and styling. The page displays three vehicle categories side by side: Sedans, SUVs, and Luxury cars.

## Features

- Semantic HTML structure using `<section>` and `<article>` elements for each card
- Equal height, equal width cards built with flexbox using `flex: 1`
- Border-radius applied only to the outer corners of the card group, so the three cards read as one connected unit
- Circular icon backgrounds for each vehicle category
- Hover effects on the buttons, including a color swap and a soft box shadow
- A responsive layout that stacks the cards into a single column on smaller screens

## Bonus Challenges Completed

- Entrance animations on page load, with each card animating in from a different direction: the Sedan card slides in from the left, the SUV card falls in from the top, and the Luxury card slides in from the right
- Hover states on the buttons with a smooth transition, color swap matching each card's theme, and a subtle box shadow

## What I Learned

This project gave me a much deeper understanding of flexbox properties, particularly the difference between `flex`, `flex-wrap`, and `flex-direction`. I learned that `flex: 1` lets cards share available space equally so they end up the same width, that `flex-wrap` is what allows cards to drop onto a new line instead of getting squished on smaller screens, and that `flex-direction: column` is the key to switching from a side-by-side layout to a stacked layout on mobile.

## Built With

- HTML5
- CSS3
- Google Fonts — Plus Jakarta Sans

