## Bonus Feature: Recipe Recommendation Engine

HavenMade includes an interactive, CSS-only recipe recommendation interface on the Recipes page.

Visitors select one of four cooking moods: On a Budget, Something Quick, Comfort Food, or Something Sweet. The interface displays a matching recipe with a confidence label, an explanation, and a link to its instructions.

This feature simulates a recommendation engine using HTML radio buttons and CSS selectors rather than real artificial intelligence or JavaScript.

### Design Decisions

I integrated the feature directly into the Recipes page so visitors can discover meals without leaving the main browsing experience. I used pink selection states, rounded cards, and the existing HavenMade visual style to keep the interface consistent.

### Testing and Accessibility

- Layout: Reviewed the recommendation section in the desktop browser.
- Interaction: Confirmed that selecting different cooking moods changes the recommended recipe.
- Accessibility: Used labeled radio buttons and visible keyboard focus styles. Keyboard navigation and reduced-motion behavior should also be tested.
- Responsive design: Added CSS breakpoints for tablet and mobile screen widths; narrow-screen behavior still needs verification.
