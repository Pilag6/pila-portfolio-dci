# Portfolio Website Design and Development

## Screenshots



<img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/c8d86480-a655-4b1a-88ec-269e7a626e81" alt="" width="100%">
<div style="display: flex;">
  
<img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/bea358dc-56fe-4a40-89cf-716702181ce3" alt="" width="24%">

<img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/dbf16f47-0dab-4ca7-9da0-422a82b13940" alt="" width="74%">

</div>


## Overview

This README provides an overview of the design and development process of my portfolio website, which follows the New Brutalism design trend. It highlights the design choices, inspirations, challenges faced during development, and some extra details.

### Design Choices

For a long time, I wanted to create a website that adheres to the New Brutalism design trend. However, I decided to tweak the color palette to make it slightly less striking. Here are the key design choices:

- **Color Palette**: I chose a muted color scheme to deviate from pure colors. These are the primary colors used:

  ```css
  /* colors */
  --black: #333333;
  --white-body: #f5f5f5;

  --nb-yellow: hsl(65, 100%, 76%);
  --nb-orange: hsl(43, 100%, 80%);
  --nb-pink: hsl(328, 97%, 88%);
  --nb-lilac: hsl(260, 100%, 88%);
  --nb-blue: hsl(209, 82%, 83%);
  --nb-green: hsl(177, 61%, 73%);
  ```

- **Typography**: I used "Familjen Grotesk" as the main font and "Bebas Neue" as the secondary font.

### Design Phase

To start, I designed the website using Figma, drawing inspiration from various sources, including the Figma community. I utilized SVGs and icons from Favicon for specific elements.

### Development Phase

The development phase was both challenging and educational. I encountered various challenges and learned new techniques along the way:

- **Positioning**: I delved into the use of `position: absolute` to tightly control elements within their parent containers, ensuring a clean layout.

- **Hover Effects**: I implemented hover effects where an element's hover triggered an effect on another element, as seen in the navigation bar and buttons. This required creative use of CSS to order and select elements.

- **Spotify-Style Cards**: Designing and coding the Spotify-style cards was a significant challenge. I relied on the versatility of `display: flex` to achieve a design close to the original in Figma, using nested `divs` and creative class naming.

- **Flex-Wrap**: Leveraging `flex-wrap: wrap` eliminated the need for media queries, ensuring responsiveness.

### Achievements

Creating the Spotify-style cards was a particularly fulfilling accomplishment. It required meticulous design and coding, but the end result closely resembled the original. 

#### Extra Details

- **Open Graph Cards**: I added Open Graph cards for improved social sharing.

- **Cursor Styles**: I customized the cursor styles for various decorative elements on the website.

- **Scrollbar and Text Selection**: I adjusted the scrollbar and text selection styles to align with the overall design.

### Conclusion

Developing this portfolio website was a rewarding challenge. While code organization was sometimes a struggle, I gained invaluable experience. My future goal is to learn React and implement component-based development for easier code maintenance.

Thank you for visiting my portfolio website!
