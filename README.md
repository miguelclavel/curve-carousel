# Curve Carousel

Case studies that ride a curve, from [miguelclavel.com](https://miguelclavel.com/?utm_source=github&utm_medium=curve-carousel).

<img src="assets/still-light.png" width="720" alt="Case study cards on a curve, the focused one in front and the others tilting away">

**[Try it live](https://miguelclavel.github.io/curve-carousel/)** · one file, `index.html`, no libraries. Drag, swipe, scroll sideways or use the arrow keys.

My four case studies don't sit in a list. They ride a curve.

One's in front and readable. The rest lean away behind it.

A list of projects makes someone choose before they know anything. Four titles, pick one, hope it was the right one. I wanted them to move through the work instead, with one project fully in front of them at a time.

So the cards sit on the top of a huge circle, and the centre of that circle is below the bottom of your screen. You only ever see the crown of it. That's why the cards on either side tilt away instead of just getting smaller.

The whole thing runs off one number. How far each card is from the one in focus.

1. Distance sets the size. The focused card is full size, and each step away shrinks it, down to a floor so the far ones never vanish completely.

2. Distance sets the fade. Nothing fades until it's more than one and a half cards away, so the two nearest stay solid and the edges soften.

3. Distance sets the stacking, so the focused card is always on top and nothing crosses in front of it.

4. Only the front card takes clicks. The ones behind are decoration until they're the one in focus.

Curves are underrated. A straight carousel would've told you nothing about which one to read.

## Use it on your site

Put your cards in `CARDS` (title, line, image, link) and tune `RADIUS`, `MIN_SCALE` and `SOLID` at the top of the script. Only the front card takes clicks and keyboard focus; it jumps instead of gliding for people who prefer reduced motion.

## Or build your own from the prompt

```text
Arrange my project cards along the top of a large circle whose centre sits below the viewport, so cards to either side of the focused one tilt away as they ride the curve. Work out each card's distance from the focused index, and use that one distance to set its scale with a minimum floor, its opacity with no fade for the first card and a half, and its stack order so the focused card is always on top. Only the focused card should be clickable.
```

---

MIT licensed. Made by [Miguel Clavel](https://miguelclavel.com/?utm_source=github&utm_medium=curve-carousel) with Claude Code. Case study images belong to the companies named.
