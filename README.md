# Portfolio Web
## Rules to convert *Figma/PSD* <img alt='figma' src='./images/figma.png' width="20"> to *HTML* <img alt='html' src='./images/html.png' width="20">
1. Top to Bottom.
2. Outside to Inside: Container -> Row or Container-Fluid.
3. Left to Right: Row -> Columns.
---
## More information:
1. [Bootstrap 4 Grid](https://getbootstrap.com/docs/4.0/layout/grid/)
2. [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
3. [Flexbox MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
4. [Flexbox by InternetingIsHard](https://www.internetingishard.com/html-and-css/flexbox/)
5. [BEM](http://getbem.com/)
---
## General Layout:
```
head
    link css
    link font
    link bootstrap
    link fontawesome
body
    header 
        nav.top-nav
    
    main
        section.hero
        section.about
        section.skills
        section.experiences
        section.education
        section.interests
    footer
        section.app-footer
```
## Section - Top-nav
```
nav.top-nav
    div.container
        div.row
            div.col
                img.top-nav__logo

            div.col
                ul.top-nav__menu > li > a

            div.col
                ul.top-nav__socials > li*3 > a > i

            div.col
                div.top-nav__switch > i
```
## Section - Hero
```
section.hero
    div.container
        div.row
            div.col
                div.hero__content
                    h1.hero__title
                    p.hero__description
                    button

            div.col
                img.hero__thumbnail
```
## Section - About
```
section.about
    div.container
        div.row
            div.col
                div.title
                div.about__picture
                div.about__contact
            div.col
                div.about__description
                h2.about__summary
                p.
                button
```
## Section - Skills
```
section.skills
    div.container
        div.row
            h1.title   
            div.col > li*3 > i               
```
## Section - Experiences
```
section.experiences
    div.container
        div.row
            h1.title
            p.experiences__summary
        div.row
            div.col
                div.experiences__logo
            div.col
                h2.experiences__subtitle
                h3.experiences__subtitle
                p
```
## Section - Education
```
section.education
    div.container
        div.row
            div.col
                h1.title
                h2.education_sub
                p
```
## Section - Interests
```
section.interests
    div.container
        div.row
            div.col
                h1.title
                p
```
## Section - Footer
```
section.footer
    div.container
        div.row
            div.col
                div.footer__box
                    h2 (thanks)
                    div.footer__box__button > li*3 > a >i
        div.row
            p 
            h4
```