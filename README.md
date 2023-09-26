# Colour Theory

This site is designed as an introductory tool to colour theory.

Designed as a teaching tool, the site will introduce the user to the basics of colour theory and guide them towards additional learning.

## Contents

[Planning & Development](#Planning-and-Development)

[Features]

[Testing]

[Deployment]

[Languages]

[Software]

[Media]

[Credits](#credits)

## Planning and Development

- **Target Audiences**

  - Users who are looking for information about the meaning of colours.
  - Designers who want insight into why certain colours are chosen for specific jobs in design. e.g. Warning signs / Product packaging / Interior-design / Fashion.
  - Users who want a clear and easy-to-use teaching tool for colour theory.
  - Users who are curious about the science behind colour.
  - Users who want to research the psychology of colour.
  - Users who want to quickly find more resources for further information on colour theory.

- **User Stories**

  - As a user, I want to discover colour theory.
  - As a user, I want to find the most relevant information quickly and effortlessly.
  - As a user, I want to access additional media content.
  - As a user, I want to have a positive emotional experience.
  - As a user, I want to use the site as a teaching tool across multiple devices.
  - As a colourblind user, I want to learn more about colours I see differently to others.

- **Site Objectives**

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

- **Approach**

  - The information will be provided to the user logically and informed by planning research.
  - The site will be created following the principles of user experience design.
  - The site will provide embedded content and link to direct them to additional learning.
  - The content of the site will be inoffensive and accessible to all.
  - The site will be easy to navigate, intuitive and consistent in design.

- **Wireframes**

  - Procreate was used to document research, sketch out initial ideas, page layouts and wireframes.
  - This planning and development work was uploaded to Figma. The design page on Figma is a useful tool to layout all my early project documents in one space, and share online with others for additional input. It allowed my mentor to quickly view and understand my project themes and objectives.
  - Using Figma's wireframes capabilities, I was able to play with initial layouts and plan intuitive flow around my site. This has given me a good understanding of how an MVP might be presented to me by a frontend designer.
  - I focused on a mobile first development ethos.
  - Please click the link to view my developement work on Figma: [View here](https://www.figma.com/file/xRmFsJ81DMgX4vdtkmL1bA/Wireframe?type=design&node-id=33%3A362&mode=design&t=yJLFa2QCrx29gmW1-1)

- **Color Scheme**

  - Building a site on Colour Theory demands a complicated colour palette of the featured spectrum of 9 colours: Red, Orange, Yellow, Green, Blue, Purple, Brown, Black, and White.
  - Consequently, a neutral background palette of Black, White and 2 tones of grey were chosen to offset the vibrant featured colours.
  - I have been mindful of colourblind users by ensuring minimum contrast values are achieved across my site for readability. I have also ensured each colour is named with text, to allow colourblind users to easily understand which colour the information they read is referring to. (e.g. Colours text on the home-page "splats" / h1's clearly stating which colour profile page the user is viewing.)

    ![An image of colour development work](/assets/readme-images/colour-palette.jpg)

  - The above image illustrates how I considered good readability contrast on both light and dark backgrounds for each colour I selected.
  - I realised a lighter text colour was required, not just over Black, but also over Red, Purple, and Brown. I created colour groups in my CSS to automatically give the light colours a dark font, and the dark colours a light font.
  - Later in my developement process, Chrome dev tools showed amber warnings for text contrast on Red and Purple. To fix this, I moved the Red colour into the dark-font group. For Purple, I switched purple: #9843b4 for a darker purple: #772f8f which met the minimum contrast threshold.

- **Typography**

# Features

## Existing Features

- **Navigation Bar**

- **Sticky Navigation Menu**

- **Hero Image**

- **Upcoming Dates**

- **News Section**

- **Mailing List**

- **Fire Image**

- **The Footer**

- **Audio Section**

  - **Video Section**

- **The Gallery**

  - **Upper Biography Section**

  - **Lower Biography Section**

  - **Contact Section**

- **Possible Future Features**

  # Testing

- **Testing During Development**

  - I used a Chrome extension to check my site for spelling errors. [Webpage Spell-Check](https://chrome.google.com/webstore/detail/webpage-spell-check/mgdhaoimpabdhmacaclbbjddhngchjik/related)

- **Validator Testing**

- **Performance Testing**

- **Other Bug Fixes**

- **Unfixed Bugs**

# Deployment

# Languages

- The coding languages used to create this site were HTML and CSS.
- In conjunction with Bootstrap 4.5.3

# Software

- Visual Studio Code to create, load and push my code to Github.
- Git and Github as my version control system for the site.
- Figma to create design-boards, wireframes and prototypes.
- Procreate to create design pages and sketch-work, images and logo.
- tingpng.com [Visit site](https://tinypng.com/)

# Media

- YouTube videos

  - Flow Studio: Color Theory for Noobs [Visit here](https://www.youtube.com/watch?v=AvgCkHrcj90)
  - Blender Guru: Understanding Color [Visit here](https://www.youtube.com/watch?v=Qj1FK8n7WgY)
  - GCFLearnFree: Beginning Graphic Design: Color [Visit here](https://www.youtube.com/watch?v=_2LLXnUdUIc)
  - Satori Graphics: ADVANCED Colour Theory Makes Designs SUPERIOR! [Visit here](https://www.youtube.com/watch?v=XNkV6m4fosw)

- TedTalks
  - ["I Listen To Color": Neil Harbisson](https://www.ted.com/talks/neil_harbisson_i_listen_to_color?language=en)
  - ["What is color?": Colm Kelleher](https://www.ted.com/talks/colm_kelleher_what_is_color)
  - ["How we see color": Colm Kelleher](https://www.ted.com/talks/colm_kelleher_how_we_see_color)
  - ["What color is Tuesday? Exploring synesthesia": Richard Cytowic](https://www.ted.com/talks/richard_e_cytowic_what_color_is_tuesday_exploring_synesthesia)

# Credits

## **Content**

- Geeksforgeeks helped me with my flexbox grid layout. [View here](https://www.geeksforgeeks.org/how-to-set-space-between-the-flexbox/)

- w3schools: code to create an Image Gallery with a Horizontal Scroll. [View here](https://www.w3schools.com/howto/howto_css_image_gallery_scroll.asp)

- KenBroTeach Youtube tutorial for Bootstrap4 Grid system [View here](https://www.youtube.com/watch?v=Tldw2tFMTeY)

- KenBroTeach Youtube tutorial for Bootstrap4 Grid breakpoints [View here](https://www.youtube.com/watch?v=R1gHdv1koh4)

- Heller, E. (2009). Psychology of Colors - Color in Motion. Verlagshaus Braun.
- Gage, J. (1993). Colour and Culture: Practice and Meaning from Antiquity to Abstraction. Thames & Hudson.
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

## **Thanks**

- Richard Wells: my Code Institute Mentor.

- Dan Sanderson: for helping me with my VScode and Github set ups.

- Kera Cudmore: for her excellent guide to writing READMEs
  [View here](https://github.com/kera-cudmore/readme-examples#readme-examples)

- atapas: for his markdown-cheatsheet [View here](https://github.com/atapas/markdown-cheatsheet#horizontal-line)

- Ian Lunn: for his hover css library [View here](https://github.com/IanLunn/Hover)

- David Calikes: for his excellent README file which I've used as a template. [View here](https://github.com/davidcalikes/portfolio-project-one/blob/main/README.md?plain=1)

- Tom Harris: my excellent research buddy and my biggest cheerleader.

- Shaun Russell: my partner, my UI/UX personal mentor, and my provider while I study. Building my new development career change would have been infinitely harder without you. Thank you.
