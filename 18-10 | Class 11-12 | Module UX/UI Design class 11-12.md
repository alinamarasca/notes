# Prep-work for design:

## User research &rarr;

## User flows:

lay out the user path into the app: what he does, what happens, what he needs
set up dependancies;

think about **successful** path and **unsuccessful** path

## Information architecture:

how you structure and organize information in a **logical** way; relationship between sections; what is where, what is inside what;
that's your &darr;

## Navigation

- don't hide it
- minimum level, simple(3-4 levels)
- group logically
- indicate where user is
- visual difference between levels (font styles, weights or background color)

## Wireframe

- page layout
- information hierarchy
- content sections
- actions and functions
- designa dn requirements
- NO DESIGN, only **content, flow, acions**

# Design principles:

## Grid

is the base of the page;

it will divide content in sections,
create composition on all pages which is easy to maintain and code;
easy to add new content;
easy to make adaptive;

- column: normally sets of 8, 6 or 4
- gutter: between columns
- margin: space **before** and **after** column

**just stick to the grid**

**stick element to columns not gutters**

## Gestalt:

set of principles on how human eye organise images, how our eye automatically sees things;
how we recognize patterns, simplify complex images and percieve objects

### Proximity

Elements that are close together appear grouped and related to each other; **respect the law of proximity**

### Similarity

Elements that are similar convey a sense of similar:

- function
- priority
- impact

**keep visual and fucntional consistency of the same elements across the project; guide users**

### Closure

Our perception fills the visual gap even when parts are missing (ex: loading, progress)

### Size and Scale

Bring hierarchy and prioritization for content informantion and actions to support user tasks and content scalability

**bigger- more important, use 3 section of importance**

# Visual and Typography hierarchy:

Guide user's attention to the most critical content on the page and/or element with different font type, font weight or font color;
**scale is important, tight to user's tastks, don't use more than 2-3 typeface's**

## Typography

Text formatting influences how user reads content:

- meaning
- hierarchy
- readability

**! language and special signs support, license**

### Typeface

**Font-family in CSS**

- Serif - easier to read in print
- Sans Serif - cleaner, esier to read on screen
- Monospace - fixed width of letters, best for code, easy to align and compare

**Font-weight in CSS**

- Light
- Medim
- Bold

**Font-style in CSS**

- Normal
- Italic
- Oblique (skew if no Italic)

  **Font-size in CSS**

  - size in px or ems or%;

**text-transform in CSS**

- Uppercase
- Lowercase
- Capitalize(first letter of every word becomes _Uppercase_)

**text-decoration in CSS**

- None (removes default decoration)
- Underline
- Overline

**text-align in CSS**

**the assender** - highest height of letters
**leading** - space between lines of text

- line-height: font size+leading

**text-align in CSS**

- Left/Right
- Center
- Justified

### Ideal line length (in English)

- paragrapgh, body text: 40-60 characters
- short lines 20-40 characters

# Color:

- gives the first impression
- creates hierarchy and clarity
- supports message

**Hue** technical name for color (red, green, blue, purple)<br>
**Saturation** amount of grey in teh color (dull/vivid)<br>
**Brightness** amount of black (dark/light)

## How do you choose colors?

**Color harmonies** - good combinations of colors.
**Analogus colors** - colors which are close to each other on color wheel

**Complementary colors** - colors completely opposite to each other in color wheel &rarr; hight contrast, bring accent

**Triadic color** - three colors on same distance from each other in color wheel

**applicable for all elements of the design**

### Contrast

distinguishes elements that behave differently, have different importance

### Color combination

### Accessibility

color should not be the only messenger - visually impared people may get lost

## In CSS

**RGB values**

- 0-255; RGB(255, 99, 71)
- RGBa (red, green, blue, opacity)

**HEX codes**

- #FFFFFF - white; #000000 - black;<br>
  FF(red)63(blue)47(green)

* not case sensitive
* if all letters/cifers are the same, can contract to first three:
  #ffffff &rarr; #fff

**Color names**

- just names: red, green, blue etc.
