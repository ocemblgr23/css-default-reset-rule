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


#### font and colors variable

```css
:root {

  --fs-300: clamp(0.94rem, calc(0.92rem + 0.08vw), 0.98rem);
  --fs-400: clamp(1.13rem, calc(1.06rem + 0.33vw), 1.31rem);
  --fs-500: clamp(1.35rem, calc(1.21rem + 0.69vw), 1.75rem);
  --fs-600: clamp(1.62rem, calc(1.37rem + 1.24vw), 2.33rem);
  --fs-700: clamp(1.94rem, calc(1.54rem + 2.03vw), 3.11rem);
  --fs-800: clamp(2.33rem, calc(1.7rem + 3.15vw), 4.14rem);
  --fs-900: clamp(2.8rem, calc(1.85rem + 4.74vw), 5.52rem);

  --clr-primary-300: hsl(219, 76%, 55%);
  --clr-primary-400: hsl(219, 76%, 40%);
  --clr-primary-500: hsl(219, 76%, 25%);
  --clr-secondary-300: hsl(269, 75%, 55%);
  --clr-secondary-400: hsl(269, 75%, 40%);
  --clr-secondary-500: hsl(269, 75%, 25%);
  --clr-accent-300: hsl(358, 72%, 65%);
  --clr-accent-400: hsl(358, 72%, 50%);
  --clr-accent-500: hsl(358, 72%, 35%);

  /* --clr-primary-400: 263 55% 52%;
  --clr-secondary-400: 217 19% 35%;
  --clr-secondary-500: 219 29% 14%;
  --clr-neutral-100: 0 0% 100%;
  --clr-neutral-200: 210 46% 95%;
  --clr-neutral-300: 0 0% 81%; */
}

.site-title {
  font-size: var(--fs-900);
  line-height: 1.05;
  text-transform: uppercase;
}

.section-title {
  font-size: var(--fs-800);
  line-height: 1.1;
}

```


#### html5 semantic tags style

`https://github.com/kevin-powell/reponsive-web-design-bootcamp/blob/master/Module%202-%20A%20simple%20life/normalize.css` <br>
`https://github.com/kevin-powell/css-demystified-course-material/tree/main/module-4/04-article-challenge-1` <br>


```css

article,
aside,
footer,
header,
nav,
section {
  display: block;
}

figcaption,
figure,
main {

  display: block;
}

audio,
video {
  display: inline-block;
}

```