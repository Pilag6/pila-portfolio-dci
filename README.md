# Portfolio Website Design and Development

***NOTE***: 

This project is only for educational purposes and will only be shared within the DCI Crusaders group environment.

## Screenshots



<img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/c8d86480-a655-4b1a-88ec-269e7a626e81" alt="" width="100%">

<div style="display: flex; justify-content: space-between;">
  
  <img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/bea358dc-56fe-4a40-89cf-716702181ce3" alt="" width="30%">

  <img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/dbf16f47-0dab-4ca7-9da0-422a82b13940" alt="" width="64%">

</div>

---

<a href="https://pila-portfolio-dci.netlify.app/"><strong>➥ Live Demo</strong></a>

## Overview

This README provides an overview of the design and development process of my portfolio website, which follows a mix between the **New Brutalism** and **Memphis** design trend. It highlights the design choices, inspirations, challenges faced during development, and some extra details.

### Inspiration

For a while, I had been intrigued by the **New Brutalism** design trend and decided to take on the challenge of creating a website in this style. After studying various designs within this trend, I opted to follow the **New Brutalism** style but with a ***slightly muted color palette***. The vibrant colors initially associated with the trend were too intense for my taste.

## Design | Phase I

I began the design process in **Figma**, drawing inspiration from the community and utilizing resources available there. For the ***Spotify-style cards***, which presented a significant development challenge, I found a design that inspired me (or, let's say, "borrowed" from) within the **Figma community**. I downloaded the drawings in **SVG format** and sourced icons from **FontAwesome**


### Design Choices

Here are the key design choices:

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

- **Typography**: I carefully selected fonts to align with the New Brutalism aesthetic, with ***"Familjen Grotesk"*** as the main font and ***"Bebas Neue"*** as the secondary font.

With the design, fonts, colors and assets in place, I was ready to proceed to the coding phase.

## Development | Phase II

The development phase was both challenging and educational. I encountered various challenges and learned new techniques along the way:

- **Positioning**: I delved into the extensive use of `position: absolute`, aiming to constrain elements within their parent containers to achieve precise layouts. This approach taught me the importance of not allowing parent elements to become overly broad.

- **Hover Effects**: I discovered how to apply hover effects to different elements when hovering over a specific element. You can observe this in action in the top navigation bar, where hovering over ***"About"*** causes an arrow to move above the word. Similarly, in the ***"My Curriculum"*** and ***"My Projects"*** buttons, the arrows in the middle change direction on hover. I tackled this last challenge by strategically assigning orders to the three elements and utilizing the `~` selector. The last element in my HTML is the ***Arrow***, but applying ordering in CSS we can see it in the middle of the buttons. So I could Selects with `~` the element that is preceded by an `a` element (my buttons).

- **Spotify-Style Cards**: Creating the ***Spotify-style cards*** proved to be the most substantial challenge. While designing, I underestimated the complexity of implementing them. Thanks to the flexibility of `display: flex`, I managed to develop a design that closely resembled the original in **Figma**. However, this required nesting numerous `div` elements and dealing with complex class naming (`class="the-div-of-the-div-of-the-div"`). Point extra for **Tailwind CSS** in this aspect ;).

- **Flex-Wrap**: I achieved responsive design without the need for additional **media queries**, thanks to `flex-wrap: wrap`.

### Big Achievements

For sure, creating the **Spotify-style cards** was a particularly fulfilling accomplishment. It required meticulous design and coding, but the end result closely resembled the original. 

#### Extra Details

- **Open Graph Cards**: I added Open Graph cards for improved social sharing.

- **Cursor Styles**: I customized the cursor styles for various decorative elements on the website.

- **Scrollbar and Text Selection**: I adjusted the scrollbar and text selection styles to align with the overall design.

  ![image](https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/a835f190-ed7e-402f-9965-2b7a67d78402)


<img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/8fbc73c3-b7d4-454d-9b8d-3daf95c8992d" alt="" width="40%">

<img src="https://github.com/Pilag6/pila-portfolio-dci/assets/79191808/44357439-8bf9-4e11-b857-8e1adbc53a8a" alt="" width="40%">

## Conclusion

Building my portfolio website in the **New Brutalism** style was a rewarding challenge. While I aimed for code organization, it occasionally became overwhelming with nearly **700 lines of HTML** and over **1000 lines of CSS** (excluding the separate **Reset CSS** file). My future goal is to delve into **React** and component-based development, which I believe will streamline code maintenance and enhance my web development skills.

Thank you, `Marco`, `Carlo` and all my `Crusaders colleagues` for all your support!
