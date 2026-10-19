# HavenMade — Recipe Studio

**CSC 4370 — Web Programming | Project 1**

**Student:** Haven Freeman

## Project Overview

HavenMade is a cozy, budget-friendly recipe website designed to make home cooking feel approachable, relaxing, and enjoyable. The website features original food photography, easy meal ideas, and a warm visual design inspired by a retro kitchen aesthetic.

**Tagline:** Good food. Small budgets. A little peace in every recipe.

## Target Audience

HavenMade is designed for students, beginner cooks, and anyone looking for affordable, comforting meals without complicated cooking techniques.

## Project Track

**Selected Track:** Recipe Studio

The website includes four HTML pages:

- `index.html` — Homepage introducing HavenMade and featured recipes.
- `recipes.html` — Recipe collection and interactive recommendation feature.
- `recipe-detail.html` — Individual recipe information and instructions.
- `about.html` — My Story page explaining the inspiration behind HavenMade.

## Technologies Used

- HTML5 for page structure and semantic content.
- CSS3 for styling, layout, animations, and responsiveness.
- CSS Grid and Flexbox for page layouts.
- CSS media queries for smaller screens.
- HTML radio buttons and CSS selectors for interactive recipe recommendations.

The website uses HTML and CSS without JavaScript or external AI APIs.

## Project Structure

```text
HavenMade/
├── index.html
├── recipes.html
├── recipe-detail.html
├── about.html
├── css/
│   └── style.css
├── images/
│   └── Original recipe photographs
└── README.md
```

## Design Decisions

The website uses cream, chocolate brown, soft pink, butter yellow, and sage green to create a welcoming kitchen-inspired atmosphere.

Rounded recipe cards, friendly typography, soft borders, and subtle CSS animations support the cozy aesthetic.

Shared navigation and reusable CSS classes help maintain a consistent appearance across all four pages.

## Bonus Feature: Recipe Recommendation Engine

HavenMade includes an interactive, CSS-only recipe recommendation interface on the Recipes page.

Visitors select one of four cooking moods:

- On a Budget
- Something Quick
- Comfort Food
- Something Sweet

The interface displays a matching recipe with a confidence label, an explanation, and a link to its instructions.

The feature uses HTML radio buttons and CSS selectors to simulate a recommendation engine. It does not use real artificial intelligence, JavaScript, or an external API.

### Bonus Feature Design Decisions

The recommendation feature is integrated directly into the Recipes page rather than placed on a separate page.

Pink selection states, rounded cards, and consistent typography help the feature match the rest of HavenMade.

## Responsive Design and Accessibility

The website includes responsive CSS layouts for desktop, tablet, and mobile screen sizes.

Accessibility considerations include descriptive image alternative text, semantic HTML elements, labeled controls, and keyboard navigation.

The website also includes CSS animations and reduced-motion styling.

## Testing and Debugging

The following checks were completed:

- Tested the website at mobile screen sizes.
- Tested keyboard navigation.
- Verified navigation between the four pages.
- Tested recipe links and the recommendation interface.
- Published the website to the university CODD server.
- Confirmed the published website displays its images and styling correctly.
- Asked another person to test the published website; they reported that everything worked.

### Bug Fix: Missing Recipe Images

During CODD deployment, four recipe photographs initially failed to display even though their files had uploaded successfully.

The problem was resolved by updating image file permissions and folder access permissions on the CODD server. After refreshing the website, all six recipe photographs displayed correctly.

## Running the Website

HavenMade is a static website and does not require additional software, dependencies, or installation.

To run it locally:

1. Download or clone the GitHub repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Use the navigation menu to explore the website.

## Project Links

**Published website:** https://codd.cs.gsu.edu/~hfreeman11/HavenMade/

**GitHub repository:** https://github.com/Hfreeman1/HavenMade

## Development Process

The project was organized using a Trello Kanban board to track completed tasks, work in progress, testing, and remaining deliverables.

Git and GitHub were used to maintain project files and record development changes.
