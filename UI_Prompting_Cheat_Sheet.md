
# UI Prompting Cheat Sheet for Cursor (and Other AI Code Assistants)

Use this guide to describe small visual tweaks, layout changes, and design improvements—even if you’re not a frontend dev.

---

## 1. Spacing Between Elements

**Prompt Examples:**
1. Add horizontal space between these two buttons.
2. Increase vertical space between this form and the section above it.
3. Use Tailwind’s `gap` utility to add spacing between flex items.
4. Add `mt-6` to push this section down.
5. Add more breathing room between these sections.
6. Reduce the space between this heading and the next element—it feels too far apart.
7. Add consistent vertical spacing between all form fields.
8. Remove unnecessary margin to tighten layout.
9. Adjust padding so text isn’t cramped.
10. Use `space-y-4` for consistent vertical rhythm in stacked elements.

---

## 2. Alignment & Positioning

**Prompt Examples:**
1. Center this button horizontally.
2. Align the input field to the right of the label.
3. Distribute these elements evenly using flexbox.
4. Align all input fields to the left and labels above them.
5. Center this icon and text block vertically within its parent container.
6. Make sure all buttons in this section are the same width.
7. Align items to the top within this flex row.
8. Fix alignment so this content matches the grid layout.
9. Push this item to the far right of its container.
10. Justify content evenly with space between items.

---

## 3. Layout Adjustments

**Prompt Examples:**
1. Use a flex row layout on desktop and stack on mobile.
2. Use a grid with 2 columns on large screens, 1 column on small.
3. Wrap these cards in a container with padding and shadow.
4. Reorganize this section to better separate content blocks.
5. Create a two-column layout with text on the left and image on the right.
6. Add consistent spacing between sections of this page.
7. Use `max-w-screen-lg` to constrain layout width.
8. Stack these icons vertically on mobile.
9. Use `grid-cols-3` for even card distribution.
10. Apply a responsive layout that collapses to a single column on small screens.

---

## 4. Visual Hierarchy & Polish

**Prompt Examples:**
1. Make the section heading larger and bolder.
2. Use font size and spacing to separate label from input.
3. Add a visual border or background to distinguish this section.
4. Make this component feel more modern using Tailwind utilities.
5. This page feels cluttered—reorganize and simplify the layout.
6. Apply a subtle elevation (like shadow or border) to this card.
7. Improve the visual rhythm of this section using spacing and font size.
8. Emphasize the primary CTA button using bold colors.
9. Make supporting text smaller and muted for readability.
10. Use a divider line to separate major content areas.

---

## 5. When You’re Not Sure What’s Wrong

**Prompt Examples:**
1. The spacing here feels cramped—make it look more modern.
2. Polish this layout to feel more professional.
3. This section feels too flat—add separation and structure.
4. This form feels unbalanced—adjust layout and spacing.
5. These elements feel misaligned—can you fix that?
6. This header feels weak—give it more emphasis.
7. It looks cluttered—make it feel cleaner.
8. Make the UI feel like a modern SaaS app.
9. Use a common layout pattern to improve visual flow.
10. Improve visual clarity without changing content.

---

## 6. Mobile Responsiveness

**Prompt Examples:**
1. Make this layout responsive with stacked items on mobile.
2. Adjust padding and font sizes for smaller screens.
3. Add Tailwind responsive classes to stack this layout on mobile.
4. Make this image scale down on smaller screens while keeping text readable.
5. Ensure all padding and margins adapt at `sm`, `md`, and `lg` breakpoints.
6. Hide this sidebar on small screens.
7. Replace a horizontal layout with a vertical one on mobile.
8. Center this text block when on small screens.
9. Adjust spacing to reduce visual noise on small devices.
10. Create a mobile-first layout and scale up for larger screens.

---

## 7. Keeping Code Clean

**Prompt Examples:**
1. Simplify these Tailwind classes and remove anything redundant.
2. Organize these classes for better readability.
3. Remove any unused or redundant classes.
4. Refactor this block to use semantic HTML with Tailwind styling.
5. Clean up this layout so all elements are aligned and evenly spaced.
6. Split large utility class blocks into meaningful groups.
7. Sort utility classes using Headwind order.
8. Reduce nesting by flattening the structure.
9. Apply consistent spacing utilities throughout.
10. Replace repeated values with reusable Tailwind classes.

---

## Quick Reference: Design Term Translation

| **Design Term** | **Say This Instead** |
|------------------|----------------------|
| Padding | “Add space *inside* the box” |
| Margin | “Add space *outside* the box” |
| Gap | “Add space *between* items” |
| Centering | “Center this horizontally” |
| Hierarchy | “Make this more visually distinct” |
| Card | “Wrap in a container with padding and shadow” |

---

## Tools That Help with Visual Tweaks

- **Tailwind CSS IntelliSense** – tooltip help for spacing & layout classes
- **Headwind** – sorts Tailwind classes for clean code
- **Live Server / Browser Inspector** – inspect layout & test spacing
- **[play.tailwindcss.com](https://play.tailwindcss.com/)** – test layout & spacing in a visual playground
