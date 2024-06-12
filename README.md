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


### Struggles and New Learnings

I had some struggles when I started working on the project and learnt a few things while I fixed them.
1. The first issue I had was displaying my footer on the mobile view. I had added 3 paragraphs in my footer and wanted to display in column for mobile and in row for desktop. I had enclosed 3 sections in div and had given flex display to `footer` with column direction. This made it impossible to give `space-evenly` to `justify-content` attribute to the ul element as giving `flex` display to footer made it confined to the text size. Two ways to fix this were, giving either `width` to the `ul` element or removing `flex` display from the footer as other elements will be block display and giving `flex` only to unordered list.

2. The second issue I faced was displaying images in the home screen for mobile screens. I aimed to create sliding images by using only HTML and CSS. This was a bit of a struggle as I was unable to fit my images in the mobile screen as I pictured in my wireframe. I struggled further with relative position for images as it broke my header and footer design. I saved the commit which I may come back to again. I decided to create a gif image of the gallery images and add them to the home screen.

3. Another struggle I faced was when I started the crafts section. I had a different wireframe but I was not able to fit the content in the mobile view, the same way I had created my wireframe. I modified the UI to fit the mobile view.

4. I also struggled with displaying the crafts section for the tablet and larger screens. The text associated with the craft appeared longer than the image. I am still figuring out on how to make a proper display for it. I believe I would either shorten the text, or make the display vertical rather than the horizontal change on larger screens.

5. I struggled with managing the width of the components on the website. The images would get distorted on 4k and higher resolution screens. I am still figuring out to fix it. Mentor suggested to give max-width to all the content in the main section. I am trying to see if I can give max-width to certain sections than the entire page.


### Credits

I got help from lot of online resources:

1. My font options were given by chatGPT on prompt " fonts for art websites" and fonts were taken from [Google Fonts](https://fonts.google.com/).
2. The creative quote was taken from [extraordinary chaos](https://extraordinarychaos.com/amazing-quotes-about-crafting.html).
3. The fade in Overlay in the material sections was taken from W3schools [Image Overlay Fade](https://www.w3schools.com/howto/howto_css_image_overlay.asp).
4. [Pexels](www.pexels.com), [Freepick](www.freepick.com), [iStock](www.istockphoto.com), and Google search for images
5. [Coolers](https://coolors.co/) for color theme.

### Deployment & Gitpod Development

#### Deployment

The website is deployed using Github Pages functionality provided by Github. The steps to follow are:

1. Create a Github account if you dont already have one
2. The repository for Creative Corner was created using a template provided by Code Institute. This can be found on the repository title [here](https://github.com/hennasingh/creative-corner).
3. Go to settings tab on the menu bar of the repository.
4. In the left section, under Code and automation, click on Pages.
5. Under the title "Build and deployment", select the source: Deploy from a branch.
6. Under the branch section below that, select /root folder and save.
7. Come back to Code section of the repository. Give a few minutes and refresh the page. You will find Deployments section generated the right side with a URL to the deployed site.

#### Gitpod Development

The project Creative Corner was developed using Gitpod that provides the functionality to work in VS code within the browser. The steps I followed setting up account and develop the project:

1. Create a Github repository using a template if you have one.
2. Install [Gitpod extension](https://chromewebstore.google.com/detail/gitpod/dodmmooeoklaejobgleioelladacbeki?hl=en&pli=1) in the browser you use.
3. Create a Gitpod account. With Code Institute, there was provision of enterprise gmail account provided by them. I used that email to sign-up for Gitpod account. You can use your personal email to sign-up. It provides limited hours to work on Gitpod. There are other ways to increase the hours.
4. Once in the Gitpod account, create a workspace, by pasting the link of the repository created in step 1. Other option is once you create repository in Github, the repository can be opened in Gitpod using the open button. Read more [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension)
5. Once, the workspace is created, you can run this command on terminal to preview your repo `python3 -m http.server`. 
6. You can continue to make changes in the workspace within Gitpod and commit your changes to Github and also see preview of your website.













