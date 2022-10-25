# frontend-technical-pathway

## Foundational (Lvl 1-3)

1. Semantic HTML
2. CSS / CSS-in-JS / CSS Preprocessors / Bootstrap / Material UI / Tailwind / Storybook
3. Best Practices / PWAs / Service Workers
4. Accessibility 


---

## Semantic HTML

Semantics refers to the study of language _meaning_, 
in frontend development this meaning comes from the HTML tags we use to mark up a document. 

For example, if you saw a `<h1>` tag, you would know that whatever is found between that tag is a main heading. 
If you saw a `<footer>` tag, you would immediately assume that this exists at the bottom of a webpage.

Semantic HTML represents what your content means and how it should be interpreted by the end User.

So why is Semantic HTML so important? 

Computers don't have eyes 👀 - if you've built a webpage using random tags styled to convey meaning, this meaning gets lost. 

For example, if instead of using a `<h1>` tag to indicate a main heading, you instead style a `<p>` tag to be 32px, 
and then use CSS to make it bright red so that it stands out - for a User using a screenreader, this is just a `<p>` tag. It has no other importance.

Using Semantic HTML helps to make your website more accessible, but also benefits your site's SEO. 

### Useful resources

[Mozilla: Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

[W3schools: HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

[Medium: Semantic HTML & SEO](https://medium.com/geekculture/5-ways-to-write-semantic-html-and-improve-webpage-seo-and-accessibility-626329130d95)

[A11y Casts: "Why do semantics matter?" - YouTube](https://www.youtube.com/watch?v=g2tzEil5TL0&ab_channel=GoogleChromeDevelopers)

[Deque Systems: "Why Semantic HTML is important for accessibility" - YouTube](https://www.youtube.com/watch?v=1JRDOR73ahs&t=412s&ab_channel=DequeSystems)


---

## CSS

### CSS-in-JS

CSS-in-JS means writing your CSS directly in your component files.

The benefit to using this way of styling is largely related to scope, you no longer have to worry about naming conventions or overriding some obscure global style based on your variable name. Troubleshooting styling bugs is a lot easier - you know exactly where to look; also code maintainability - instead of keeping some legacy styles based on the fact that they've "always been there", if your component changes (or gets discarded), those styles go with them. 

CSS-in-JS is a topic that splits the field - try the libraries linked below and decide which side of the fence you sit on.

### CSS-in-JS Libraries

[styled-components](https://styled-components.com/)

[goober](https://goober.js.org/)

[emotion](https://emotion.sh/docs/introduction)

### Useful resources

[CSS-in-JS Playground](https://www.cssinjsplayground.com/)

[Github: CSS-in-TS analysis](https://github.com/andreipfeiffer/css-in-js/blob/main/README.md#overview)

[Sparkbox: A Lukewarm Approval of CSS-in-JS](https://sparkbox.com/foundry/css_in_js_overview_css_in_js_pros_and_cons)

[LevelUpTuts: "What is CSS in JS? What is Styled Components?" - YouTube](https://www.youtube.com/watch?v=EsSi4cER48E&ab_channel=LevelUpTuts)

[Coding Tech: "The Past, Present and Future of CSS-in-JS" - YouTube](https://www.youtube.com/watch?v=a31BUlx-EXc&ab_channel=CodingTech)

### CSS Preprocessors

### Bootstrap

### Material UI

### Tailwind

### Storybook

---

## Best Practices 

### PWAs

### Service Workers

---

## Accessibility 

