## css-default-reset-rule
A basic css professional cheatsheet for devloper.


#### common styles rule

```css
/* You can add global styles to this file, and also import other style files */
@import url('https://fonts.googleapis.com/css2?family=Poppins&family=Roboto&display=swap');

:root {
  --font-family: 'Poppins', sans-serif;
  --font-family: 'Roboto', sans-serif;
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

/* Set core body defaults */
body {
  min-height: 100vh;
  line-height: 1.5;
  font-family: var(--font-family);
  text-rendering: optimizeSpeed;
}

/* Remove default margin */
body,
h1,
h2,
h3,
h4,
p,
figure,
blockquote,
dl,
dd {
  margin: 0;
}

a {
  text-decoration: none;
}

ul {
  list-style: none;
}

/* Make images easier to work with */
img,
picture {
  max-width: 100%;
  display: block;
}

/* Uttility classes */
.container {
  width: min(80%, 100% - 2rem);
  margin-inline: auto;
}

```