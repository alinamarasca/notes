## Adaptive design (milestone)

**CSS**

- media query for tablets (issue)
- media query for smartphones (issue)
- flex: wrap (issue)
- change animation direction for smaller devices (issue)
  (end of stylesheet)

## Supported languages (milestone)

**HTML**

- list of supported languages: Node.js, Python, C#, Ruby, PHP, Scala, Clojure in languages section on the index page (issue)

**CSS**

- card with supported language (logo + name of supported language) (issue)
- card styling: rounded corners, shadows (issue)
- cards hover animation (issue)

## Menu (milestone)

**HTML**

- navbar: Home, Features, Docs (all pages) (issue)

**CSS**

- style elements, hover (issue)
- place elements using flex (issue)

## Spam protection

**HTML**

- insert honeypot code [honeypot form](https://zinoui.com/blog/protect-web-forms-from-spam#honey-pot) (issue)

**CSS**

- hide honeypot 'display:none' (issue)

## Original logo

**HTML**

- Logo in navbar on every page (issue)

**CSS**
@import font from google fonts (issue)

## Organised information

**HTML**

- headers ierarchy on each page (issue)
- information placed on cards on features page (issue)
- sub-menu with information on docs page (issue)
  **CSS**
  grid, flex on all pages (issue)

## Infographics.

**HTML**

- infograpics with fitting images (issue)
- **CSS**
- images placed on cards with info on features page (issue)
- infographics placed near paragraphs (issue)

## Demo-request form

**HTML**

- request form with name, company and email lines, submit button (issue)
- **CSS**
- card styling for request form on index page, top of showcase section
  on Home page

## Memorable style

**CSS**

- original color palette (issue)
- original skewed rectangle as part of design(issue)
- animation on Home page (issue)

1.  As a **potential client** I want success message on demo request form submission.

- [ ] Given succes message appears after the form is filled correctly and submitted.
  > HTML ???
  > CSS ???

## Selected item indication

**CSS**

- hover effect on links - underline in Home page menu (issue)
- hover effect on cards - go up on Home page menu (issue)
- hover effect on sub-menu - bold, chosen - blue (issue)

---

## Could-Haves

12. As a **user** I want supported languages icons to be linked to their respective official websites.

- [ ] Given when user clicks on a language icon it redirects him to the respective official website.
- [ ] > HTML cards get links a href to websites

13. As a **visitor** I want social networks icons.

- [ ] Given social network icons so that they connect Loruki through social network. Mayuri
  > HTML favicons with attached links
  > CSS favicons in-line block footer

14. As a **visitor** I want a favicon to easily recognize the webpage in my browser. Mayuri

- [ ] Given a blue "L" favicon.
      HTML favicon in header

Loruki website
Cloud hosting for everyone

---

# Home page

### Head

**HTML**

- [ ] boilerplate, stylesheet link, title

**CSS**

- [ ] import font
- [ ] define color scheme
- [ ] define default
  - marging
  - padding
  - fonts
  - color
  - line-height
  - links decoration

---

### Body

## Navbar

**HTML**

- [ ] div class="navbar"
- [ ] div class="container-flex"
- [ ] h1 logo
- [ ] ul li menu: Home, Features, Docs
- [ ] menu: links to pages

  **CSS**

- [ ] list display
- [ ] navbar grid
- [ ] hover state

## Showcase section

**HTML**

- [ ] section class="showcase"
  - [ ] div class="container grid"
    - [ ] div class "showcase-text":
  * h1 title
  * paragrpah
  * 'Read more' button + link
- [ ] div class= "showcase-form card"
  - [ ] commented out honeypot
  <!--  <form name="contact" netlify-honeypot="bot-field" method="POST" data-netlify="true">
         <input type="hidden" name="form-name" value="contact">
         <p class="hidden">
         <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
         </p> -->
  - [ ] div class="form-control" x 3
    - [ ] input type
    - [ ] placeholder text
    - [ ] required
  - [ ] submit btn class="btn btn-primary"

**CSS**

- [ ] text stling
- [ ] grid
- [ ] form, form-control, input

---

## Stats section

**HTML**

- [ ] class="stats"
  - [ ]div class="container"
    - h3 class="stats-heading text-center my-1"
  - [ ] div class="grid grid-3 text-center my-4" - [ ] div x3 (each own class for favicon, h3,p class="text-secondary") - [ ] Deployments i class="fas fa-server fa-3x" - [ ] Published i class="fas fa-upload fa-3x - [ ] Project i class="fas fa-project-diagram fa-3x
        **CSS**
- [ ] grid

---

## CLI section

- [ ] class="cli"
  - [ ]div class="container grid">
    - [ ] cli.png
    - [ ] class="card" h3 'easy to use' & 'Deploy in seconds'

---

## Cloud section

- [ ] class="cloud bg-primary my-2 py-2

  - [ ]div class="container grid"
    - [ ]div class="text-center"
      - h2 class="lg" Extreme Cloud Hosting
      - p class="lead my-1" Cloud hosting like you've never seen. Fast, efficient and scalable
      - button 'Read more' class="btn btn-dark" linked to features.html
  - [ ] cloud.png

  ## Languages

- [ ] class="languages"
- [ ] h2 class="md text-center my-2" ' Supported Languages'
- [ ] div class="container flex"

  - [ ] div class="card" x7
    - h4: Node.js, Python, C#, Ruby, PHP, Scala, Clojure
    - img

## Footer

- [ ]class="footer bg-dark py-5"
  - [ ]div class="container grid grid-3"
    - [ ]div
      - h1 Loruki
      - p Copyright &copy; 2020
  - [ ] nav ul li: Home, Features, Docs
  - [ ] div class="social"
    - i class="fab fa-github fa-2x" + link
    - i class="fab fa-facebook fa-2x" + link
    - i class="fab fa-instagram fa-2x" + link
    - i class="fab fa-twitter fa-2x">
