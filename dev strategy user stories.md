# Backlog

## Must-Haves

1. As a **visitor** / **account owner** I want a website to be comfortable to use from smaller devices such as phone and tablet. **A**

- [ ] Given when open from smaller device then design modifies to the size of my screen.

> CSS media query for tablets and smartphones; wrap for flex objects

2. As a **visitor** I want to know the supported languages of the platform to decide if I want to use this website.

- [ ] Given the supported languages: Node.js, Python, C#, Ruby, PHP, Scala, Clojure

> HTML language section with list of supported languages(name+logo)

> CSS cards: rounded corners, shadows, flex, animation

3. As a **visitor** I want menu options so that I can navigate on website:

- [ ] Given when user opens the website hes sees the menu.

> HTML navbar: logo and menu list
> CSS menu: flex-end, logo -flex-start

4. As an **owner** of the website I want spam protection to protect data of my clients. **A**

- [ ] Given protection against spam demo requests.
  > HTML [honeypot form](https://zinoui.com/blog/protect-web-forms-from-spam#honey-pot)

> CSS hide honeypot 'display:none'

5. As an **owner** I want a logo so that my website can be easily identified.

- [ ] Given when the website is opened by a visitor in the browser, it should have a nice, attractive Loruki logo to recognize the website.
  > HTML Loruki in navbar
  > CSS @import font from google fonts with url

6. As a **content manager** I want information grouped in blocks and pages so it is easy to navigate.

- [ ] Given information is split in blocks and pages. (blocks can be small/colors)
  > HTML headers ierarchy and paragraphs, 3 pages:
  > home, features and docs
  > CSS grid, flex, display: blocks

7. As a **designer** I want to have infographics so the website is easy to use.

- [ ] Given minimalist design and clear infographics.
  > HTML infograpics with fitting images
  > CSS images on cards with info

8. As a **developer** I want to try demo version of the product to decide if I want to use it.

- [ ] Given request demo form on index page.
  > HTML request for name, company name and email, submit button
  > CSS card with request form on index page, top showcase section

## Should-Haves

9. As a **product owner** I want the name of website to be memorable.

- [ ] Given simple and original name to the website.
  > HTML import font, put website name in navbar seen on all pages

10. As a **potential client** I want success message on demo request form submission.

- [ ] Given succes message appears after the form is filled correctly and submitted.
  > HTML ???
  > CSS ???

11. As a **visitor** I want all menu items or navigation links to indicate they are selected for pressing.

- [ ] Given hoover effects.

  > CSS hoover effects: links - border-bottom: 2px #fff solid, buttons - transform: scale(0.98), language cards transform: translateY(-15px); list on Docs page - font-weight: bold;

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
- [ ] define colors
- [ ] define defaut
  - marging
  - padding
- [ ] body
  - fonts
  - color
  - line-height
- [ ] list-style-type
- [ ] links decoration
- [ ] headers

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

- [ ] navbar
- [ ] navbar ul
- [ ] navbar a
- [ ] navbar a:hover

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

- [ ] showcase
- [ ] showcase h1
- [ ] showcase p
- [ ] showcase .grid
- [ ] showcase-text
- [ ] showcase-form
- [ ] showcase-form. form-control
- [ ] showcase-form input

---

## Stats section

- [ ] class="stats"

  - [ ]div class="container"
    - h3 class="stats-heading text-center my-1"
  - [ ] div class="grid grid-3 text-center my-4"
    - [ ] div x3 (each own class for favicon, h3,p class="text-secondary")
      - [ ] Deployments i class="fas fa-server fa-3x"
      - [ ] Published i class="fas fa-upload fa-3x
      - [ ] Project i class="fas fa-project-diagram fa-3x

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
