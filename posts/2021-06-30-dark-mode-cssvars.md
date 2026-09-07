---
title: Light/Dark mode, the CSS-variable way
date: '2021-06-30'
category: note
basename: '2021-06-30-dark-mode-cssvars.gif'
width: 1440
height: 900
---

Choosing colors is hard. Respecting your visitors’ color preferences shouldn’t be.

For this short recipe, you will need a couple of ingredients: [CSS variables](https://www.w3.org/TR/css-variables-1/) and the media feature [`prefers-color-scheme`](https://www.w3.org/TR/mediaqueries-5/#prefers-color-scheme).

1. You can define your color variables and their values for light (default) and dark modes in your CSS file:

```css
:root {
  --text: #333333;
}

@media (prefers-color-scheme: dark) {
  :root {
    --text: #ffffff;
  }
}
```

2. Then you can use those variables in your CSS declarations:

```css
element {
  color: var(--text);
}
```

**And that’s it!** Your website will react to the user's color theme preference.

You can play with a simple but functional example in [this CodePen](https://codepen.io/mamuso/pen/jOmEjeQ); fidget with your OS appearance preferences to see colors change. This foundation also works like a charm in more complex scenarios:

- Check [Joshua Comeau's post](https://www.joshwcomeau.com/react/dark-mode/). He implements light/dark mode in Gatsby using CSS variables.
- Or [this example](https://github.com/mamuso/nextjs-simple-darkmode) using CSS variables with Next.js and styled-components.
