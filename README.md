# mint-auth

MINT login / register widget, built from the MINT Figma design with motion interactions.

**Live preview:** https://mint-auth.netlify.app/

## Interactions

- 3D tilt that follows the cursor with spring physics
- Dot-grid lens that bulges and warms to brand red under the cursor
- Logo pop and pixel confetti when the cursor enters the card
- Click feedback: squish-and-bounce, ripple, shockwave through the dot grid, soft UI sounds and haptics
- Email validation with a shake on error and a "Check your inbox ✓" success state
- Respects `prefers-reduced-motion`

## Stack

Plain HTML, CSS and vanilla JavaScript — no frameworks, no build step. Open `index.html` to run locally.
