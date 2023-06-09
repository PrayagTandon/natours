# Natours-Project [Live-site](https://natours-prayag.netlify.app/)

## Description: 
- Natours is a travel website where you can book your next adventures.
- Natours provide a variety of adventures ranging from exploring the sea to climbing the icy mountains.
- You can book for an entire group and enjoy your stay in the lap of nature alongside your adventure.

- We provide two group options: 
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

1. Design Inspiration: Source: [Jonas Schmedtmann - CSS course Udemy](https://www.udemy.com/course/advanced-css-and-sass/) 

2. Typography: 
> Source:[Google Fonts](https://fonts.google.com/)
- Lato -> Family: sans-serif , Font-weight used : 100,300,400,700,900.

3. Colors: Source : [OpenColors](https://yeun.github.io/open-color/) , [Coolors](https://coolors.co/palettes/trending)

 Tints and Shades: Source: [Tints and Shades generator](https://maketintsandshades.com/)

- Primary color: `#55c57a`
- Primary color-light: `#7ed56f`
- Primary color-dark: `#28b485`

- Secondary color-light: `#ffb900`
- Secondary color-dark: `#ff7730`

- Tertiary color-light: `#2998ff`
- Tertiary color-dark: `#5643fa`


* Greys : 

         - Grey Dark : #333
         - Grey Light-1 : #777
         - Grey Light-2 : #999
         - Grey Lightest : #f7f7f7
         - Near white : #eee

4. Images: Source: [Unsplash](https://unsplash.com/) , [Pexels](https://www.pexels.com/)

#### Defining the different sections of the webpage.

- Navigation
- Hero Section + logo
- About
- Features
- Tours
- Testimonials
- Call-to-action
- Footer

#### Setting the development environment

- To make the website responsive from start I used relative units for lengths such as rem, percentage instead of px.

* Set the font-size of the root element of the page to **62.5%** to make it easier for calculation(Default font size of browser is 16px so, 62.5% will convert it into 10px and thus 1 rem = 10px).

+ Installed node and npm in the project.

- Added Sass to the project and used the 7 in 1 architecture.

* Created 5 folders named "abstracts, base, components, layout, pages" inside the sass folder and a main.scss file that contains all the different elements.

+ Code Editor: VS Code.

- Deployed using Netlify.


[def]: https://natours-prayag.netlify.app/