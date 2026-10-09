# Project 4: Garden City Fest

**Level:** Intermediate  
**Focus:** Positioning (relative, absolute, fixed, sticky) and z-index

A music festival page for a three-day event in Port Harcourt. Nearly every section layers things on top of other things.

## What you will practise

- An `absolute` header that sits over the hero
- Stacked layers with `position:absolute; inset:0` (image, dark gradient, text)
- A rotated circular stamp
- A `sticky` ticket bar that sticks once you scroll past the hero
- Day stickers and a diagonal corner ribbon (`rotate(45deg)` + `overflow:hidden` on the card)
- A timeline: vertical line from `::before`, dots from `li::before`, times pulled left with `position:absolute`
- Map hotspots placed with `top`/`left` percentages and centred with `translate(-50%, -50%)`
- A `fixed` toast notification
- `z-index` so the header, ticket bar and toast stack correctly

## What's in this folder

| Path | What it is |
|---|---|
| `design/desktop-full-page.png` | Whole page at 1440px (toast hidden) |
| `design/desktop-first-screen.png` | What you see on load, with the toast |
| `design/mobile-full-page.png` | Whole page at 390px |
| `design/mobile-first-screen.png` | First screen on mobile |
| `assets/images/` | artist-1.jpg, artist-2.jpg, artist-3.jpg, artist-4.jpg, hero-crowd.jpg, venue-map.jpg |
| `assets/icons/` | calendar.svg, clock.svg, menu.svg, pin.svg, star.svg, ticket.svg, x.svg (SVG) |
| `assets/logo.svg` | Logo |
| `starter/index.html` | Finished HTML with all content. You shouldn't need to change it much. |
| `starter/style.css` | Colours, fonts and a reset. Write your layout here. |

## Your tasks

Work through these in order.

1. Build the hero at 88vh. The header, gradient, title, date details and stamp are all absolutely positioned inside it.
2. Build the yellow ticket bar and make it stick to the top of the screen.
3. Build the line-up cards. Each has a day sticker in the top-left and a name panel along the bottom. Kalio's card has a diagonal Headliner ribbon.
4. Build the timeline. The current item has a glowing magenta dot.
5. Build the venue map with three numbered hotspots and a You are at the gate pill that hangs below the image.
6. Build the fixed toast (top-right on desktop, bottom on mobile).
7. Mobile (below 600px): move the title to the top of the hero, put the date details at the bottom, and move the timeline times above each item.

## Design specs

**Colours**

| Name | Hex | Used for |
|---|---|---|
| Navy | `#14213D` | Text, schedule background, buttons |
| Magenta | `#D6246E` | Stamp, live item, toast edge, map note |
| Sun | `#FFD23F` | Hero title, ticket bar, headliner ribbon, timeline dots |
| Teal | `#0E7C7B` | Artwork accent |
| Paper | `#FBF8F1` | Page background |
| Muted | `#56607A` | Secondary text |

**Font:** Anton (400) for display text, Work Sans (400, 500, 700) for body. Get it from https://fonts.google.com/specimen/Anton and https://fonts.google.com/specimen/Work+Sans (already linked in the starter HTML).

**Measurements**

- Page side padding: `5vw`
- Hero title: `clamp(4.5rem, 13vw, 11rem)`, line-height .85, uppercase
- Stamp: 150px circle, 4px dashed white border, rotated −10°
- Ticket bar: 3px navy bottom border
- Hotspots: 40px circles with 3px white border
- Toast: 6px magenta left border, 360px max width, 88px from the top

**Breakpoints:** check your page at 1440px, 1024px, 768px and 390px wide. Your page should never scroll sideways.

## Stretch goals

- Make the toast close button work.
- Show a small label when a hotspot is hovered or focused.
- Make the countdown tick with JavaScript.

## Tips

- Open the design image next to your browser and compare often.
- Use your browser's DevTools: the Grid and Flexbox overlays show you exactly what is happening.
- Pixel-perfect is not the goal. Matching the layout and the way it responds is.
