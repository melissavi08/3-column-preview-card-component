# Frontend Mentor - 3 column preview card component solution

This is a solution to the [3 column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3-column-preview-card-component-pH92eAR2-).

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

## Desktop Design

<img src="./images/desktop-design.jpg" alt="desktop-design" style="width:60%;"/>

## Links

- Live Site URL: [3 column preview card component](https://melissavi08.github.io/3-column-preview-card-component/index.html)

## Built with

<img alt='HTML5' src='https://img.shields.io/badge/HTML-100000?style=flat&logo=HTML5&logoColor=white&labelColor=F77421&color=F77421'/> <img alt='CSS3' src='https://img.shields.io/badge/CSS_Custom_Properties-100000?style=flat&logo=CSS3&logoColor=white&labelColor=00BFFF&color=00BFFF'/> <img alt='Flexbox' src='https://img.shields.io/badge/Flexbox-100000?style=flat&logo=&logoColor=white&Color=D063E4&color=D063E4'/> <img alt='CSS_Grid' src='https://img.shields.io/badge/CSS_Grid-100000?style=flat&logo=&logoColor=white&Color=D063E4&color=47DAB2'/> <img alt='Responsive_Desing' src='https://img.shields.io/badge/Responsive_Desing-100000?style=flat&logo=&logoColor=white&Color=FF69B4&color=FF69B4'/>

## What I learned

During this challenge, I sought to implement responsive design without media queries, and I accomplished this goal. I'm very proud of how I did it, and for that, I used the following resource 👉 [@frontend_trend - responsive flex wrap](https://www.instagram.com/p/CdYr6fqD_RC)

I have included the code I used below 👇

#### HTML code

```html
<main>
  <div class="card-container">...</div>
  <div class="card-container">...</div>
  <div class="card-container">...</div>
</main>
```

#### CSS code

```css
main {
  display: flex;
  flex-wrap: wrap;
  max-width: 900px;
  min-height: 500px;
  margin: 32px;
  border-radius: 10px;
  overflow: hidden;
}

.card-container {
  flex: 1 1 250px;
  display: grid;
  grid-template-rows: auto auto auto minmax(auto, 100%);
  padding: 40px;
}
```

## Useful resources

There are some awesome instagram channels that help me learn new things about coding and get inspired.

- [@frontend_trend](https://www.instagram.com/frontend_trend/).
- [@frontendchannels](https://www.instagram.com/frontendchannels/)

## Connect with me

<a href='https://twitter.com/melissa_vi2' target="_blank"><img alt='Twitter' src='https://img.shields.io/badge/melissa__vi2-100000?style=flat&logo=Twitter&logoColor=white&labelColor=00BFFF&color=FF69B4'/></a> <a href='https://www.linkedin.com/in/melissa-villegas' target="_blank"><img alt='LinkedIn' src='https://img.shields.io/badge/Melissa_Villegas-100000?style=flat&logo=LinkedIn&logoColor=white&labelColor=00BFFF&color=FF69B4'/></a>
