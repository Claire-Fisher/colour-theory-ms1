# Colour Theory

### This site is designed as an educational resource for Colour Theory on an introductory level.

Designed as a teaching tool, the site will introduce the user to the basics of colour theory and guide them towards additional learning. This project is intended for users from Secondary School education age and above. With younger users increasingly likely to seek information on mobile devices, my site must be fully responsive and will be developed using a mobile first approach.

## Contents

[Planning & Development](#Planning-and-Development)

[Features](#features)

[Future Features](#future-features)

[Testing](#testing)

[Deployment](#deployment)

[Languages](#languages)

[Software](#software)

[Credits](#credits)

[Content](#content)

# Planning and Development

### Target Audiences

- Users who are looking for information about the meaning of colours.
- Designers who want insight into why certain colours are chosen for specific jobs in design. e.g. Warning signs / Product packaging / Interior-design / Fashion.
- Users who want a clear and easy-to-use teaching tool for colour theory.
- Users who are curious about the science behind colour.
- Users who want to research the psychology of colour.
- Users who want to quickly find more resources for further information on colour theory.

### User Stories

- As a user, I want to discover colour theory.
- As a user, I want to find the most relevant information quickly and effortlessly.
- As a user, I want to access additional media content.
- As a user, I want to have a positive emotional experience.
- As a user, I want to use the site as a teaching tool across multiple devices.
- As a colourblind user, I want to learn more about colours I see differently from others.

### Site Objectives

- To deliver fast introductory information on colour theory to the user.
- To make the purpose of the site obvious to the user.
- To provide a positive user experience.
- To create an intuitive UI that provides good site flow.
- To build a family-friendly site that is appropriate for young users.
- To build a site that is responsive on a large variety of screen sizes and mobile devices.
- To create a fast, easy-to-navigate teaching tool for teachers to show their students.
- To guide the user onto additional resources for learning about colour theory.
- To deliver a site about colour that is accessible to colour-blind users.
- To create a site that is reasonably navigable by screen-readers.

### Approach

- The information will be provided to the user logically and informed by planning research.
- The site will be created following the principles of user experience design.
- The site will provide embedded content and link to direct them to additional learning.
- The content of the site will be inoffensive and accessible to all.
- The site will be easy to navigate, intuitive and consistent in design.

### Wireframes

- Procreate was used to document research, sketch out initial ideas, page layouts and wireframes.
- This planning and development work was uploaded to Figma. The design page on Figma is a useful tool to layout all my early project documents in one space, and share online with others for additional input. It allowed my mentor to quickly view and understand my project themes and objectives.
- Using Figma's wireframes capabilities, I was able to play with initial layouts and plan intuitive flow around my site. This has given me a good understanding of how an MVP might be presented to me by a frontend designer.
- I focused on a mobile first development ethos.
- Please click the link to view my developement work on Figma: [View here](https://www.figma.com/file/xRmFsJ81DMgX4vdtkmL1bA/Wireframe?type=design&node-id=33%3A362&mode=design&t=yJLFa2QCrx29gmW1-1)

  ![An image of my development work presented on Figma](/documents/figma-development-work.png)

### Color Scheme

- Building a site on Colour Theory demands a complicated colour palette of the featured spectrum of 9 colours: Red, Orange, Yellow, Green, Blue, Purple, Brown, Black, and White.
- Consequently, a neutral background palette of Black, White and 2 tones of grey were chosen to offset the vibrant featured colours.
- I have been mindful of colourblind users by ensuring minimum contrast values are achieved across my site for readability. I have also ensured each colour is named with text, to allow colourblind users to easily understand which colour the information they read is referring to. (e.g. Colours text on the home-page "splats" / h1's clearly stating which colour profile page the user is viewing.)

  ![An image of colour development work](/documents/colour-palette.jpg)

- The above image illustrates how I considered good readability contrast on both light and dark backgrounds for each colour I selected.
- I realised a lighter text colour was required, not just over Black, but also over Red, Purple, and Brown. I created colour groups in my CSS to automatically give the light colours a dark font, and the dark colours a light font.
- Later in my developement process, Chrome dev tools showed amber warnings for text contrast on Red and Purple. To fix this, I moved the Red colour into the dark-font group. For Purple, I switched purple: #9843b4 for a darker purple: #772f8f which met the minimum contrast threshold.

### Typography

- 'Raleway" from Google Fonts was selected throughout as a clear, easily-readable font choice.

# Features

### General

- The site is fully responsive and functional on all screen sizes down to 320px.
- The site considers different user's sensory perceptions and reduces screen glare by softening white backgrounds, with black text, to a light grey instead.
- The site uses semantic elements to assist screenreader users to navigate and access information.
- The site includes text on all colour occurances to indicate to colour blind users which colour the information is referring to.

### Logo

- "Impact" (ios font) was used for the word "Colour". A strong, heavy font to grab attention. It was also broad enough to still be legible with a gradient of colours running across it.
- "Baskerville" (ios font) was used for the word "Theory". A more formal sans-serif typography to balance the heaviness of the Impact font, and give indication to the user that the site is intended for informative purposes.
- The logo typography choices were rasterized into a png image, and therefore the fonts were not required to be loaded into the site code.
- Early stages of the logo featured a consistent black background. A design choice was made to remove the black background and generate a transparent png version instead. This allowed the colour change of the header across different pages to be visible under the logo, whilst maintaining site continuity.
- This change created readability issues due to changing contrast levels across different colours.
- The gradient of the logo was made from the same colours selected site colour palette. So a black stroke outline had to be added to the word colour.
- The white colour of "Theory" created poor contrast on the light backgrounds and disappeared entirely on the White page. The font colour of "Theory" was changed to a mid-grey and a dropshadow applied.

### Navigation Bar

- The navigation bar features on all pages and is fully responsive.
- The navigation maintains it's structure across all pages for site continuity and for an intuitive, positive user experience.
- The logo is a hyperlink that will return the user back to the Home page from anywhere on the site. This link is indicated to the user with a hover animation.
- All navigation elements have hover animations to indicate they are clickable, and an underline text decoration to indicate the user's current location.
- The navigation bar background colour changes across all colour profile pages to indicate to the user their current location within the site.
- Information can be accessed quickly and intuitively as the navigation is designed so that any page can be viewed from any location within the site and within two clicks. This creates a positive user experience.

### Hero Image

- Instead of a classic Hero image, a gallery of multicoloured images sit aligned in a bar below the navigation header. See more information on images in the section: [Possible Future Features](#Future-features)

### The Footer

- The footer includes copyright name and date.
- The footer bar features links to site creation tools, and Research content links.
- The footer has links to social media sites.
- All links in the footer open in a new browser window.
- All links feature either an underline or animation on hover to indicate to the user they are clickable.
- All links include aria-labels for screenreader users.

### Video Section

- All videos are embedded from Youtube. A reliable source but one that will hinder site load times.
- All videos have built in play/pause functions and volume controls. Videos can be viewed full screen.
- All videos have aria-labelledby elements for screenreader users.

# Future Features

### Gallery images:

- For an additional feature, it would add interest to have the gallery change on each colour page. The images would change to those predominantly showing the colour in focus. (e.g A gallery depicting mostly red images on the Red profile page etc.)

### Contact Page:

- Invitation to site users to offer additional colour information to the developer. Particularly further cultural insights.

### Contact for accessibility suggestions:

- A note from developers to users stating accessibility is important to me and I'm always looking to improve my site. Invite users to offer accessibility improvements, or report accessibility issues they may experience while using my site.

### Additional Colours:

- Expand on the number of colours explored. Pink, Teal, Grey, Cream etc...

### Science:

- Explore further about how we see colour. Inform about colours on the spectrum which are invisible to humans (Ultraviolet, infrared). Expand on different levels of colour blindness. Show examples of how the world looks to people who see colour differently. How do other species see colour? (E.g. Dogs struggle with green and red, but see yellow and blue clearly. Dog toys are commonly blue and yellow for this reason.)

### Animations:

- Include more animated, interactive features across the site to engage the user more and appeal better to younger users. A more positive user experience increases how long a user explores your site, increases return visits and recommendations to other users.

# Testing

- **Testing During Development**

  - During the development process, I was manually testing in the following ways:-

    1. Manually testing each element for appearance and responsiveness via a simulated live server using an extension in VSCode.
    2. Published the page via GitHub pages and shared with fellow developers and other users to get feedback.

  - I tested my site on different browsers to ensure cross-compatibility. I asked other users to test browsers I don't have access to (Safari - Testers credited in thanks section). Browsers used for testing include:

    - Chrome
    - Edge
    - Firefox
    - Safari

  - I used the Chrome developer tools to simulate different screen sizes/devices from 320 px up to 1700px in width.

  - I used a Chrome extension to check my site for spelling errors. [Webpage Spell-Check](https://chrome.google.com/webstore/detail/webpage-spell-check/mgdhaoimpabdhmacaclbbjddhngchjik/related)

### Validator Testing

**HTML** - [https://validator.w3.org/nu/](https://validator.w3.org/nu/)

- Issues found:

  -

### Performance Testing

- Performance was tested using Chrome Developer tools.
- **Desktop Performance**
  ![A screenshot showing the site's Desktop Lighthouse analysis.](/documents/colour-theory-desktop-lighthouse.png)

- **Mobile Performance**
  ![A screenshot showing the site's Mobile Lighthouse analysis.](/documents/colour-theory-mobile-lighthouse.png)
- Performance on Mobile could be improved with further image compression and resizing of image aspect ratios.

### Other Bug Fixes

**Header :-**

- Multiple issues Found:
  - The Header ended up being designed three times. Positional issues and unwanted responsive behaviours.
- Solution:
  - Used a premade header from Bootstrap and styled it to fit my site themes.

**Header continued :-**

- Issue:
  - After changing the position of my navigation elements to the right side of the screen: The burger menu was traped inside header container and dropping up instead of down.
- Solution:
  - Used a media query to position:unset which returned the navigation back to it's default bootstrap behaviours on smaller screens. Then used z-index:3 to ensure the dropdown menu stayed ontop of other content.

**Duplicate IDs :-**

- Issue Found:
  - [https://validator.w3.org/nu/](https://validator.w3.org/nu/) reported dozens of Duplicate ID Errors. This was because I had used ID's instead of Classes for colour styling throughout my site. Duplicate ID's create visibility issues for assistive technologies and therefore reduces the sites accessibility rating.
- Solution:
  - Changed all ID colour styling in stylesheet to classes. Changed all colour ID's throughout all HTML pages to classes.

**Testing feedback from Tom Harris :-**

- Issue Found:
  - Safari browser - footer clipping on left edge on small screen sizes.
- Solution:
  - Fix: Increased footer padding-left in media query (max-wdith:450px).

### Unfixed Bugs

- Some positioning issues and text-background showing on colour-splats on home-page on small screen sizes.

- Unwanted underline effect showing on header navigation icons. (Desktop screen sizes only).

# Deployment

- You can deploy this site on GitHub by following these steps :-
  1. From the project's [repository](https://github.com/Claire-Fisher/colour-theory-ms1), go to the green 'Code' button.
  2. On the local tab, select Download zip.
  3. Find the zipped folder in your local Downloads folder, right click and select 'Extract All..".
  4. In the extracted 'colour-theory-ms1' folder, find the index file. Right click index and select "Open with Google Chrome" (or your prefered browser).

# Languages

- The coding languages used to create this site were HTML and CSS.
- In conjunction with Bootstrap 4.5.3

# Software

- Visual Studio Code to create, load and push my code to Github.
- Git and Github as my version control system for the site.
- Figma to create design-boards, wireframes and prototypes.
- Procreate to create design pages and sketch-work, images and logo.
- tingpng.com [Visit site](https://tinypng.com/)

# Credits

- Google Fonts for 'Raleway" typography [View here](https://fonts.google.com/specimen/Raleway)

- Geeksforgeeks helped me with my flexbox grid layout. [View here](https://www.geeksforgeeks.org/how-to-set-space-between-the-flexbox/)

- w3schools: code to create an Image Gallery with a Horizontal Scroll. [View here](https://www.w3schools.com/howto/howto_css_image_gallery_scroll.asp)

- KenBroTeach Youtube tutorial for Bootstrap4 Grid system [View here](https://www.youtube.com/watch?v=Tldw2tFMTeY)

- KenBroTeach Youtube tutorial for Bootstrap4 Grid breakpoints [View here](https://www.youtube.com/watch?v=R1gHdv1koh4)

## **Content**

- Heller, E. (2009). Psychology of Colors
- Braun, Verlagshaus. Color in Motion
- Gage, J. (1993). Colour and Culture: Practice and Meaning from Antiquity to Abstraction. Thames & Hudson.
- St Clair, Kassia (2018). The Secret Lives of Colour. John Murray (Publishers)
- [London Image Institute](https://londonimageinstitute.com/how-to-empower-yourself-with-color-psychology/)
- [VeryWellMind](https://www.verywellmind.com/color-psychology-2795824#toc-history-of-color-psychology)
- [Science of People](https://www.scienceofpeople.com/color-psychology/)
- [Color Psychology.org](https://www.colorpsychology.org/)
- [Fifteen Design](https://www.fifteendesign.co.uk/blog/how-colour-influences-our-decision-colour-psychology-in-design/)
- [Springer Link](https://link.springer.com/article/10.3758/s13428-015-0598-8#:~:text=The%20color%20red%20was%20most%20associated%20with%20anger%2C%20green%20with,%E2%80%9D%20or%20%E2%80%9Cfeeling%20blue.%E2%80%9D)
- [Colour-affects](http://www.colour-affects.co.uk/psychological-properties-of-colours)
- [User Testing](https://www.usertesting.com/blog/color-ux-conversion-rates)
- [American Museum of Natural History](https://www.amnh.org/explore/ology/brain/seeing-color#:~:text=Light%20travels%20into%20the%20eye,Cone%20cells%20help%20detect%20colors.)
- [color-meanings.com](https://www.color-meanings.com/color-psychology-how-colors-affect-your-everyday-life/)
- [scmp](https://www.scmp.com/yp/learn/learning-resources/article/3069861/33-english-colour-idioms-make-your-writing-more)
- [azquotes.com](https://www.azquotes.com/quotes/topics/orange.html)
- [Smashing Magazine - Color Theory for Deisngers](https://www.smashingmagazine.com/2010/01/color-theory-for-designers-part-1-the-meaning-of-color/#:~:text=Orange%20is%20also%20strongly%20associated,less%20in%E2%80%93your%E2%80%93face.)
- [Sitepoint.com](https://www.sitepoint.com/color-in-design-orange/)
- [Adobe.com](https://www.adobe.com/creativecloud/design/hub/guides/meaning-of-green-in-design.html#:~:text=Associated%20with%20nature%20and%20positivity,as%20your%20design's%20primary%20color.)
- [trvst](https://www.trvst.world/mind-body/green-color-quotes/#:~:text=%22Green%20is%20the%20prime%20color,from%20which%20its%20loveliness%20arises.%22&text=%22Being%20green%20and%20clean%20is,an%20aspiration%20but%20an%20action.%22&text=%22When%20you're%20green%2C,re%20ripe%2C%20you%20rot.%22)
- [phrases.com](https://www.phrases.com/psearch/)

### YouTube videos

- Flow Studio: Color Theory for Noobs [Visit here](https://www.youtube.com/watch?v=AvgCkHrcj90)
- Blender Guru: Understanding Color [Visit here](https://www.youtube.com/watch?v=Qj1FK8n7WgY)
- GCFLearnFree: Beginning Graphic Design: Color [Visit here](https://www.youtube.com/watch?v=_2LLXnUdUIc)
- Satori Graphics: ADVANCED Colour Theory Makes Designs SUPERIOR! [Visit here](https://www.youtube.com/watch?v=XNkV6m4fosw)

### TedTalks

- ["I Listen To Color": Neil Harbisson](https://www.ted.com/talks/neil_harbisson_i_listen_to_color?language=en)
- ["What is color?": Colm Kelleher](https://www.ted.com/talks/colm_kelleher_what_is_color)
- ["How we see color": Colm Kelleher](https://www.ted.com/talks/colm_kelleher_how_we_see_color)
- ["What color is Tuesday? Exploring synesthesia": Richard Cytowic](https://www.ted.com/talks/richard_e_cytowic_what_color_is_tuesday_exploring_synesthesia)

## **Thanks**

- Richard Wells: my Code Institute Mentor.

- Dan Sanderson: for helping me with my VScode and Github set ups.

- Kera Cudmore: for her excellent guide to writing READMEs
  [View here](https://github.com/kera-cudmore/readme-examples#readme-examples)

- atapas: for his markdown-cheatsheet [View here](https://github.com/atapas/markdown-cheatsheet#horizontal-line)

- Ian Lunn: for his hover css library [View here](https://github.com/IanLunn/Hover)

- David Calikes: for his excellent README file which I've used as a template. [View here](https://github.com/davidcalikes/portfolio-project-one/blob/main/README.md?plain=1)

- Tom Harris: Site tester, my excellent research buddy and my biggest cheerleader.

- Shaun Russell: Site tester, my partner, my UI/UX personal mentor, and my provider while I study. Building my new development career change would have been infinitely harder without you. Thank you.
