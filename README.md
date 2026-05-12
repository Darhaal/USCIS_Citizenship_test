# USCIS Civics Test Prep – 2025/2026 Practice App

A modern, interactive web application for practicing the USCIS civics portion of the U.S. naturalization test.

This project is a single-file web app built with HTML, Tailwind CSS, and vanilla JavaScript. It includes quiz practice, flashcards, typo-tolerant answer checking, local progress tracking, and location-based civics answers.

## Repository Description

Interactive single-file web app for practicing the USCIS 2025 civics test with quiz mode, flashcards, typo-tolerant answers, and local progress tracking.

## Live Demo

https://uscis-citizenship-test.vercel.app

## Project Overview

This project helps users study for the civics section of the U.S. naturalization test.

The app is designed to make studying more interactive than reading a static PDF. Users can practice questions, review answers, use flashcards, and track their progress directly in the browser.

The project follows a single-file structure for easy deployment and sharing.

## Important Disclaimer

This project is not affiliated with USCIS, the U.S. Department of Homeland Security, or any U.S. government agency.

The app is an independent educational practice tool.

Users should always verify official questions, answers, and current office holders using official USCIS and government sources.

## Features

### Official Civics Question Practice

The app is based on the USCIS 2025 civics test structure with 128 possible civics questions.

Users can study questions by topic or practice the full question bank.

### Location-Based Answers

Some civics questions depend on the user’s state or congressional district.

The app supports location-specific answers for:

- Governor
- U.S. Senators
- U.S. Representative
- State Capital

Users can select their state and optionally enter ZIP code information.

### Quiz Mode

Quiz Mode allows users to type answers and receive instant feedback.

The answer checker supports:

- minor typo tolerance
- common abbreviations
- synonym matching
- alternate acceptable answer forms

This makes the practice experience closer to real studying instead of strict exact-string matching.

### Flashcard Mode

Flashcard Mode allows users to review questions in a classic study-card format.

Users can reveal the answer and mark whether they got it or need to review later.

### Topic Selection

Questions are grouped by civics topic.

Main topic groups include:

- Principles of American Government
- System of Government
- Rights and Responsibilities
- Colonial Period and Independence
- 1800s History
- Recent American History
- Geography, Symbols, and Holidays

### 65/20 Rule Support

The app includes visual indicators for questions commonly associated with the 65/20 special consideration study set.

This helps older long-term permanent residents focus on the required subset when applicable.

### Local Progress Tracking

The app stores progress and settings using browser Local Storage.

No user account is required.

Progress stays on the user’s device and is not sent to a server.

### Responsive Design

The interface is designed to work on:

- desktop
- tablet
- mobile browser

The UI uses Tailwind CSS, glassmorphism-style cards, smooth animations, and a clean study-focused layout.

## Files in This Repository

All files are stored in the root of the repository.

Main files:

- README.md
- index.html
- favicon.ico
- LICENSE
- NOTICE.md

The main application logic, styling, question database, and UI are contained in index.html.

## How to Use

Download or clone the repository.

Open index.html in any modern browser.

No build step is required.

No backend server is required.

The app can also be deployed directly to static hosting platforms such as Vercel, Netlify, or GitHub Pages.

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript
- Local Storage
- Lucide Icons
- Vercel static deployment

No React, Vue, Angular, or backend framework is required.

## Data and Content Notes

The civics questions are based on public USCIS study materials.

Some answers depend on current elected officials or the user’s location. These answers can change over time.

Users should verify current officials using official sources, especially for questions about:

- President
- Vice President
- Speaker of the House
- Chief Justice
- Governor
- U.S. Senators
- U.S. Representative

## Privacy

This app does not require login.

Progress and location settings are stored locally in the browser using Local Storage.

The app does not intentionally collect or transmit personal data.

If deployed through a third-party hosting provider, that provider may collect standard access logs according to its own policies.

## Limitations

This app is a study tool, not an official USCIS product.

There are several limitations:

- Current official names may change over time.
- ZIP-to-representative lookup may need manual verification.
- Typo-tolerant answer checking is helpful but not identical to a real USCIS interview.
- The real civics test is oral, while this app uses typed answers and flashcards.
- Users should confirm official test rules and study materials on the USCIS website.

## Future Improvements

Possible future improvements:

- Add automatic official lookup for current representatives.
- Add multilingual study support.
- Add audio pronunciation mode.
- Add printable study summary.
- Add progress export/import.
- Add dedicated 65/20 study mode.
- Add offline PWA support.
- Add stronger accessibility testing.

## Version

Current repository version: 1.1.1

Question set: USCIS 2025 civics test practice format with 128 questions

## License

This project is licensed under the MIT License.

See the LICENSE file for details.

## Notice

This repository is an independent educational project.

It is not affiliated with USCIS or any U.S. government agency.

USCIS materials are public government study resources, but this app’s design, code, layout, and interactive functionality are original project work.
