# Natours-Project

## Description: 
- Natours is a travel website where you can book your next adventures.
- Natours provide a variety of adventures ranging from exploring the sea to climbing the icy mountains.
- You can book for an entire group and enjoy your stay in the lap of nature alongside your adventure.

- We have two options: 
```
> Small group : 6 - 12 people.
> Large group : 12+ people.
```
- We are waiting for your next adventure with us.

## Project Overwiew:
- Designing and Building a landing page for Natours website using HTML, SCSS, JavaScript and NodeJS.
- Made use of SassyCSS(SCSS) and strutured the layout using modern CSS grid and Flexbox. 
- **No CSS Framework**.
- Made use of BEM notation to name the classes.
- Used SCSS 7 in 1 architecture to style the different elemnets of the layout that helps to make them easily manageable and maintainable.
- Designed the layout using designing tools such as Figma.
- Deplyoed using Netlify.

### Designing the Website:
- The company focuses on providing the best adventure for a group. So, the overall personality of the website need to be more consumer focused and easy to navigate.
- Different elements for the website:

#### Selecting the different design elements and sketching a basic layout.

1. Design Inspiration: Source: [Land Book](https://land-book.com/) , [One Page Love](https://onepagelove.com/inspiration) and many more..

2. Typography: Selected 3 different fonts based on Sans-Serif typefaces.
> Source:[Google Fonts](https://fonts.google.com/)
- Rubik -> Family: sans-serif , Font-weight used : 400,500,600,700.
* Inter -> Family: sans-serif , Font-weight used : 400,500,600,700.
+ Noto Sans -> Family: sans-serif , Font-weight used : 400,500,600,700.

3. Colors: Source : [OpenColors](https://yeun.github.io/open-color/) , [Coolors](https://coolors.co/palettes/trending)
- Main color: `#e67e22`
* Greys : 

         - For long texts : #555555
         - For headings : #333333
         - #767676 :- Lightest grey on #ffffff
         - #808080
         - #6f6f6f
          
+ Tints and Shades: Source: [Tints and Shades generator](https://maketintsandshades.com/)
- Tints : `#fdf2e9` , `#fae5d3` , `#45260a`
* Shades: `#cf711f`
+ Accents: 

          - Paleo tag: `#ffd43b`
          - Vegan tag: `#94d82d`
          - Vegeterian tag: `#51cf66`

4. Images: Source: [Unsplash](https://unsplash.com/) , [Pexels](https://www.pexels.com/)

#### Defining the different sections of the webpage.

- Logo + Navigation
- Hero Section
- Featured In
- How it works
- Meals(and list of Diets)
- Pictures + Testimonials
- Pricing + Features
- Call-to-action
- Footer

#### Setting the development environment

- To make the website responsive from start I used relative units for lengths such as rem, percentage instead of px
* Set the font-size of the root element of the page to **62.5%** to make it easier for calculation(Default font size of browser is 16px so, 62.5% will convert it into 10px and thus 1 rem = 10px).
+ Font size and spacing system defined:
```
Font sizes (px)
10 / 12 / 14 / 16 / 18 / 20 / 24 / 30 / 36 / 44 / 52 / 62 / 74 / 86 / 98
Letter spacing(px)
2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

```
- Code Editor: VS Code