# GridFlex Project

**Overview:** This project demonstrates the use of CSS Grid and Flexbox layouts. The focus is on understanding grid and flex systems, with an emphasis on controlling body width.

**Usage:**
- Explore grid and flex layout examples.
- Observe the utilization of body width for layout control.

**NOTE:**
- I used a fixed max-width for my body in order to fit the design well like the one in the image.

**Examples:**
```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 20px;
}

.flex-container {
  display: flex;
  align-items: center;
}

body {
  width: 80%;
  margin: 0 auto;
}
