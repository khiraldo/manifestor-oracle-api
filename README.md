# 🌙 Manifestor Oracle API

The **Manifestor Oracle API** is a digital collection of 79 oracle cards from the *Blessed Manifestation* website. This API allows users to pull random cards for spiritual guidance and inspiration directly from the website. Each card includes an image, name, description, and alt text for accessibility.

## Project Purpose
This project was created as part of my senior capstone to enhance user engagement on the [Blessed Manifestation](https://blessedmanifestation.com) website. By offering free oracle card pulls, the goal is to attract more visitors, increase session time, and support ad-based monetization through interactive content.

## Features
- Pulls random cards using JavaScript and the Fetch API.
- Hosted JSON file containing all card data.
- Accessible `alt` text for screen readers.
- Images and data hosted via GitHub.

## Technologies Used
- HTML / CSS / JavaScript  
- GitHub (for hosting data and images)  
- WordPress (for front-end integration)

## How It Works
1. The website uses JavaScript’s `fetch()` to request data from the hosted `cards.json` file.  
2. A random card is selected and displayed dynamically, showing the name, image, and description.  
3. Users can click again to pull a new card.

## Repository Structure
manifestor-oracle-api/
│
├── cards.json # All oracle card data
└── images/ # Folder with all card images


## Example API Endpoint
To view the JSON file directly, visit:  
[https://raw.githubusercontent.com/khiraldo/manifestor-oracle-api/main/cards.json](https://raw.githubusercontent.com/khiraldo/manifestor-oracle-api/main/cards.json)

## Future Enhancements
- Add animation or "shuffling" effects when drawing cards.
- Include reversed card meanings.
- Develop a mobile app version of the oracle.

---

Created with love and intention by **Katherine Hiraldo** ✨  
[blessedmanifestation.com](https://blessedmanifestation.com)

