# Project 1: Mama Put Kitchen

**Level:** Beginner  
**Focus:** Flexbox

A landing page for a food delivery kitchen in Port Harcourt. Almost every layout on this page can be built with Flexbox alone.

## What you will practise

- `display:flex`, `gap`, `justify-content`, `align-items`
- `margin-left:auto` to push the nav to the right
- `flex: 1 1 280px` + `flex-wrap` for cards that wrap on their own
- `flex-direction: column` inside cards, with `margin-top:auto` to pin the button to the bottom
- `flex-direction: row-reverse` for the About section
- `position: sticky` header
- `position: absolute` for the rotated sticker, review card, price and tag (parent needs `position: relative`)

## What's in this folder

| Path | What it is |
|---|---|
| `design/desktop.png` | Full-page desktop design at 1440px wide |
| `design/mobile.png` | Full-page mobile design at 390px wide |
| `assets/images/` | dish-dodo.jpg, dish-egusi.jpg, dish-suya.jpg, hero-jollof.jpg, kitchen-team.jpg |
| `assets/icons/` | clock.svg, leaf.svg, menu.svg, phone.svg, pin.svg, star.svg, truck.svg (SVG) |
| `assets/logo.svg` | Logo |
| `starter/index.html` | Finished HTML with all content. You shouldn't need to change it much. |
| `starter/style.css` | Colours, fonts and a reset. Write your layout here. |

## Your tasks

Work through these in order.

1. Build the sticky header: logo left, links and button right.
2. Build the two-column hero. The sticker sits over the top-right corner of the image; the review card hangs off the bottom-left edge.
3. Build the three menu cards. They must be equal height, with buttons lined up along the bottom.
4. Build the three steps in a row with a thick top border on each.
5. Build the About section with the image on the right (without changing the HTML order).
6. Build the footer. The copyright line must take the full width of its own row.
7. Make it responsive: below 760px everything stacks into one column, the nav links hide and the menu icon shows.

## Design specs

**Colours**

| Name | Hex | Used for |
|---|---|---|
| Green | `#0F4C3A` | Menu section background, logo |
| Yellow | `#F2B705` | Buttons on cards, step circles, footer headings |
| Red | `#C8331E` | Sticker, spicy tag, focus ring |
| Paper | `#FFFDF6` | Page background, cards |
| Ink | `#1C1C1C` | Text, dark buttons, footer |
| Muted | `#5B5B52` | Body copy |

**Font:** Bricolage Grotesque (400, 600, 800). Get it from https://fonts.google.com/specimen/Bricolage+Grotesque (already linked in the starter HTML).

**Measurements**

- Page side padding: `5vw`
- Hero headline: `clamp(2.75rem, 6vw, 5rem)`, weight 800
- Image corner radius: 32px (hero, about), 16px (inside cards)
- Card radius: 24px; card gap: 1.5rem
- Sticker: 120 × 120px circle, rotated 12°
- Review card shadow: `6px 6px 0` in ink colour (a hard shadow, no blur)
- Buttons: fully rounded (999px), 2px border

**Breakpoints:** check your page at 1440px, 1024px, 768px and 390px wide. Your page should never scroll sideways.

## Stretch goals

- Make the menu toggle open a dropdown nav on mobile.
- Add a hover state to the cards that lifts them 4px.
- Try building the steps with `counter-increment` instead of typed numbers.

## Tips

- Open the design image next to your browser and compare often.
- Use your browser's DevTools: the Grid and Flexbox overlays show you exactly what is happening.
- Pixel-perfect is not the goal. Matching the layout and the way it responds is.
