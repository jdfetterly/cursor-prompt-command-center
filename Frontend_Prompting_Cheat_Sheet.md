
# Frontend Prompting Cheat Sheet for Cursor (and Other AI Code Assistants)

Use this guide to communicate frontend design, interactivity, layout, and responsiveness goals clearly to an AI developer assistant.

---

## 1. Creating or Updating UI Components

**Prompt Examples:**
1. Create a responsive navbar with a logo on the left and menu items on the right.
2. Add a hero section with a large heading, subheading, and a call-to-action button.
3. Update this component to use Tailwind CSS instead of inline styles.
4. Convert this static HTML into a React component.
5. Add a reusable button component with props for size, color, and icon.
6. Build a footer with links grouped by category.
7. Create a user profile card with an image, name, and short bio.
8. Add a sidebar with collapsible navigation sections.
9. Update this layout to include a sticky header.
10. Build a “Features” section with icons, titles, and descriptions.

---

## 2. Styling with Tailwind CSS

**Prompt Examples:**
1. Style this form using Tailwind: include padding, border, and focus states.
2. Add hover effects and transition animations to these buttons.
3. Make this layout feel more modern with spacing, shadow, and rounded corners.
4. Use Tailwind utilities to create a responsive grid with 3 columns on desktop, 1 on mobile.
5. Apply consistent padding and margins to this component.
6. Add a background gradient and shadow to this header.
7. Use Tailwind’s `prose` class to style article text.
8. Add ring and focus styles for accessibility.
9. Create a badge with rounded corners and subtle background color.
10. Apply Tailwind dark mode variants for this section.

---

## 3. Responsiveness

**Prompt Examples:**
1. Make this section responsive with Tailwind—stack elements on small screens.
2. Ensure padding, margins, and font sizes scale at `sm`, `md`, and `lg` breakpoints.
3. Adjust this layout so it works on mobile, tablet, and desktop.
4. Hide this sidebar on small screens and replace it with a menu button.
5. Make images resize proportionally across screen sizes.
6. Reorder these elements on mobile to show the call-to-action first.
7. Enable horizontal scrolling for this table on mobile.
8. Use responsive spacing utilities to reduce margins on small screens.
9. Make this video embed responsive using aspect-ratio utilities.
10. Use breakpoints to adjust font sizes for readability.

---

## 4. Interactivity & State

**Prompt Examples:**
1. Add a toggle switch that controls dark mode for the app.
2. Create a modal that opens when a button is clicked and closes when clicking outside.
3. Make this dropdown interactive using React state.
4. Add form validation and show error messages inline.
5. Build a step-by-step wizard with progress tracking.
6. Toggle a sidebar when a hamburger icon is clicked.
7. Display a loading spinner while fetching data.
8. Enable a tooltip on hover over these icons.
9. Show a success toast after submitting a form.
10. Animate a list item being removed from a list.

---

## 5. Forms & Inputs

**Prompt Examples:**
1. Build a login form with email and password inputs, and a submit button.
2. Add client-side validation using React Hook Form.
3. Style inputs for better usability and spacing.
4. Add placeholder text and floating labels to form fields.
5. Include a checkbox for terms and conditions.
6. Create a select dropdown with grouped options.
7. Add a password visibility toggle.
8. Show real-time validation errors below each input.
9. Include accessibility labels and helper text.
10. Create a multi-step form with “Next” and “Back” buttons.

---

## 6. Lists, Tables & Cards

**Prompt Examples:**
1. Render a list of products as cards in a responsive grid.
2. Create a sortable table using Tailwind and React.
3. Add pagination to this list of results.
4. Make each card hoverable with elevation and scale effects.
5. Highlight rows on hover in a table.
6. Add an expandable/collapsible accordion list.
7. Use virtual scrolling for large lists.
8. Style table headers with background and font weight.
9. Add a card component with an image, title, and call-to-action.
10. Display badges or tags on list items conditionally.

---

## 7. Animation & Transitions

**Prompt Examples:**
1. Add a fade-in animation to this section on scroll.
2. Make this button pulse subtly when hovered.
3. Use Tailwind’s transition utilities to animate changes in color and scale.
4. Animate the dropdown menu opening and closing.
5. Slide in the sidebar from the left when opened.
6. Add staggered animations for a list of elements.
7. Animate form validation errors with a shake effect.
8. Use Framer Motion to reveal content on mount.
9. Add a loading skeleton with pulse animation.
10. Fade out the modal when dismissed.

---

## 8. Icons & Visual Elements

**Prompt Examples:**
1. Add an icon next to each menu item using Lucide icons.
2. Use SVGs for the social media links and color them appropriately.
3. Add a background image to the hero section with a semi-transparent overlay.
4. Use Heroicons for the navigation icons.
5. Animate icons on hover.
6. Display an avatar placeholder when image is missing.
7. Add a decorative border or divider element.
8. Use icons to indicate status (e.g. success, warning, error).
9. Style a notification badge with a count.
10. Add a subtle pattern background using SVG.

---

## 9. Accessibility

**Prompt Examples:**
1. Ensure this form is accessible with proper `aria` labels.
2. Make this button keyboard-navigable.
3. Add focus outlines for all interactive elements.
4. Improve contrast between text and background.
5. Use semantic HTML tags where appropriate.
6. Ensure screen reader support for dynamic content.
7. Add alt text to all images.
8. Use role attributes for modals and alerts.
9. Make sure dropdowns and menus are accessible by keyboard.
10. Include label associations for all inputs.

---

## 10. Refactoring & Improvements

**Prompt Examples:**
1. Refactor this layout using grid instead of multiple nested divs.
2. Simplify this component and extract logic into smaller functions.
3. Convert this to use semantic HTML elements.
4. Remove any unused classes or props.
5. Clean up redundant Tailwind utility classes.
6. Extract repeating layout into a reusable component.
7. Move inline styles into className definitions.
8. Break this long component into smaller, named pieces.
9. Use descriptive names for props and variables.
10. Replace hard-coded values with reusable constants.

---

## Quick Tips

| Goal       | Useful Terms to Include                        |
|------------|------------------------------------------------|
| Layout     | flex, grid, stacked, centered, spacing         |
| Styling    | Tailwind, modern, responsive, minimal          |
| Interaction| toggle, modal, dropdown, hover, click          |
| Structure  | card, section, container, hero, form           |
| State      | props, hook, state, context, toggle, loading   |

---

## Tools That Help

- **Tailwind CSS IntelliSense** – autocomplete & docs in your editor
- **Lucide Icons** – clean, lightweight icon set
- **React Hook Form** – easy form handling in React
- **Framer Motion** – animations for React components
- **Heroicons / Phosphor Icons** – more icon choices

