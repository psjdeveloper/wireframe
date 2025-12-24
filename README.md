# wireframe

**WIP** — minimal CSS framework for building wireframes and layout prototypes.
An example `index.html` is provided.

The framework is intentionally lightweight and easy to extend.

---

## How to develop

- clone the repo
- run `npm install`
- run `gulp`
- read the source files
- add styles to the `lib/` directory (do not edit `css/` or `min/`)
- add corresponding HTML for styles introduced

---

## Effects (Optional)

Wireframe includes an optional effects module that provides
small, opt-in motion utilities for basic interaction feedback.

- Effects are utility-based (`fx-*`)
- They do not modify core components
- They respect `prefers-reduced-motion`

### Example

```html
<div class="fx-elevation-1 fx-lift">
  Example card
</div>

<button class="btn fx-fade-hover">
  Button
</button>
