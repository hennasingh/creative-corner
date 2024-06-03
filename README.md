# Creative Corner - Find Your People

The objective of this project is to bring budding artists in the stillorgan, Dublin area under one place to show art or take workshops. The site is an MVP version built using HTML5 & CSS3 for the Milestone 1 project for Code Institute's Full Stack Development diploma.

Live Link: https://hennasingh.github.io/creative-corner/

## Contents


### User Experience - UX

#### Strategy

This project got inspired by the existing [Kilmacud Crokes clubs](https://kilmacudcrokes.com/) based in Stillorgan. The House as part of the club has activities that members can participate in. Unfortunately, there wasn't a place for them to look at timings of the class or see the activities in action or engage with members who are already attending and hence Creative Corner is born.

- User Stories
    - First time Visitor Goals
        - I should be able to understand the purpose of the website and to learn more about the business.
        - The content can be easily navigated without back and forth
        - I can look at testimonials from others, access social media links and check authenticity
    - Returning Visitor Goals
        - I want to know how to contact the business for more information to participate
        - I want to look at new activities and events happening and able to register for it.


#### Skeleton

The wireframes for mobile and desktop were created using Balsamiq

#### Desktop Design

<details>
<summary>Desktop Wireframe</summary>

![Wireframe for Desktop](./assets/images/Wireframe%20-%20Desktops.png)

</details>

#### Mobile Design

<details>
<summary>Mobile Wireframe</summary>

![Wireframe for Mobile Screens](./assets/images/Phone%20Pages-%20Wireframe.png)
</details>


### Bugs and New Learnings

I encountered a few bugs when I started the project and leanrt a few things while I fixed them.
1. The first issue I had was displaying my footer on the mobile view. I had added 3 paragraphs in my footer and wanted to display in column for mobile and in row for desktop. I had enclosed 3 sections in div and had given flex display to `footer` with column direction. This made it impossible to give `space-evenly` to `justify-content` attribute to the ul element as giving `flex` display to footer made it confined to the text size. Two ways to fix this were, giving either `width` to the `ul` element or removing `flex` display from the footer as other elements will be block display and giving `flex` only to unordered list.

2. The second issue I faced was displaying images in the home screen for mobile screens. I aimed to create sliding images by using only HTML and CSS. This was a bit of a struggle as I was unable to fit my images in the mobile screen as I pictured in my wireframe. 





