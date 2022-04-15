# Button

```js script
import { html } from 'lit';
import '../src/button.tokens.css';
import '../src/button.css';
```

Button CSS-only component

## Usage

At this moment, our button component is just a combination of some CSS Custom Properties representing the Design Tokens behind the button.
The other CSS file implements those design tokens onto any element with `.btn` class.

```html
<link
  rel="stylesheet"
  href="@divriots/starter-style-dictionary/button/src/button.tokens.css"
/>
<link
  rel="stylesheet"
  href="@divriots/starter-style-dictionary/button/src/button.css"
/>
<button class="btn"></button>
```

### Primary

```js preview-story
export const base = () => html`<button class="btn">Click me!</button>`;
```

### Outline

```js preview-story
export const outline = () =>
  html`<button class="btn" outline>Click me!</button>`;
```

### Disabled

```js preview-story
export const disabled = () =>
  html`<button class="btn" disabled>Don't click me!</button>`;
```
