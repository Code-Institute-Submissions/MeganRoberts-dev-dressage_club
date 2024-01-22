# [DRESSAGE CLUB]( https://meganroberts-dev.github.io/dressage_club/)
![screenshot](../dressage_club/documenation/responsive-img.png)

Dressage Club 

# Author 
Megan Roberts 

# Website Overview

Welcome to our interactive Dressage Club site. This website is designed for Dressage enthusiasts to discover when events are happening, enjoy the showcasing of Dressafe images through the gallery page carousel and engage with the clubs community through a user-friendly contact form. The white theme with a contrasting orange color is a modern refrence to this typically old fashioned sport. Also provides clarity, readability, and aesthetics.


## UX

My reasons for chosing a modern deigsn was to appeal to younger users to encourage them to join. The design is also simple and easy to navigate as to also appeal to older users.  

### Colour Scheme

Sporting clubs usually only have one or two main colours that are assostaied with it. I have chosen black and gold in this case. These colours are proffesional and work well when in contrast to one another. 

- `black` used for primary text.
- ` #ffc451;` used for primary highlights.
- `white` used for secondary text.


I used coolors.co for my colour pallete. (https://coolors.co/000000-ffc451-ffffff) 

![screenshot](../dressage_club/documenation/color-pad.png)

I've used CSS `:root` variables to easily update the global colour scheme by changing only one value, instead of everywhere in the CSS file.

```css
:root {
    --primary: rgb(255, 221, 0);
    --dark: black;
    --body: rgb(19, 18, 18);
   --box-shadow: 0 8px 22px black; 
}

```
![screenshot](../dressage_club/documenation/roots.png)

### Typography

- [Titillium](https://fonts.google.com/specimen/Titillium+Web?query=tit) was used for the text of the body. 

- [Raleway](https://fonts.google.com/specimen/Raleway?query=raleway) was used for all the heading text.

- [Bootstrap Icons](https://icons.getbootstrap.com/) icons were used throughout the bootstrap site, such as the social media icons in the footer.

## User Stories
### New Site Users

- As a new site user, I would like to simply navigate through the site, so that I can accsess the page I want quickly.
- As a new site user, I would like to have clear content, so that I can obtain information easily and understand the site.
- As a new site user, I would like to use the contact / sign up form without complications.
- As a new site user, I would like to view and use the site on my moible, tablet or desktop.

### Returning Site Users

- As a returning site user, I would like to use the contact info in the footer multiple times. 

## Wireframes

To follow best practice, wireframes were developed for mobile, tablet, and desktop sizes.
I've used [Figma](https://www.figma.com/file/l2P9ZpD1xivVZg4eyKb2yn/Dressage-Club?type=whiteboard&node-id=0-1&t=WUg73mewiNJ5dveJ-0) to design my site wireframes.

### Mobile Wireframes

<details>
<summary> Click here to see the Mobile Wireframes </summary>

Home
  - ![screenshot](../dressage_club/documenation/mobile-home-page.png)

Gallery
  - ![screenshot](../dressage_club/documenation/mobile-gallery-page.png)

Signup
  - ![screenshot](../dressage_club/documenation/mobile-signup-page.png)

</details>

### Tablet Wireframes

<details>
<summary> Click here to see the Tablet Wireframes </summary>

Home
  - ![screenshot](../dressage_club/documenation/home-page-tablet.png)

Gallery
  - ![screenshot](../dressage_club/documenation/gallery-page-tablet.png)

Signup
  - ![screenshot](../dressage_club/documenation/signup-page-tablet.png)

</details>

### Desktop Wireframes

<details>
<summary> Click here to see the Desktop Wireframes </summary>

Home
  - ![screenshot](../dressage_club/documenation/desktop-home-page.png)

Gallery
  - ![screenshot](../dressage_club/documenation/desktop-gallery-page.png)

Signup
  - ![screenshot](../dressage_club/documenation/desktop-signup-page.png)
</details>

## Features

This project has implemented features:

- Home page with an about box and events section with relevant icons.
- Fixed back to top arrow on the right side of each page.
- Clear images.
- Sign up page contains a form where a user provides info about themselves to join the club.
- Successful form submission is confirmed by "thank you" message on seperate page.
- Responsive design with layout changing sections for smaller devices, including a dropdown burger menu.
- Smooth scrolling

### Existing Features
- **Feature box**

    - Feauture box in landing page containing information about the club and a button linked to sign up page with color hover effect.

![screenshot](../dressage_club/documenation/about-box.png)

- **Event icons**

    - Relevant icons that represent the type of event being promoted.

![screenshot](../dressage_club/documenation/events-icon.png)


- **Social media links**

    - Social media icons in the footer that linked to relevant social pages that change color when hovering.

![screenshot](../dressage_club/documenation/footer-icons.png)
![screenshot](../dressage_club/documenation/facebook-social-link.png)

- **Fill field**

    - A pop up will show to prompt user to fill out correctly before the form can be submited.


![screenshot](../dressage_club/documenation/fill-field.png)

- **Dropdown menu**

    - A responsive burger dropdown menu will show on tablets and smaller devices. Utilising the navbar space.

![screenshot](../dressage_club/documenation/burger-dropdown.png)

- **Carousel**

    - Responsive carousel with user friendly/ highlighted arrows. 

![screenshot](../dressage_club/documenation/carousel-gallery.png)

- **Confirmation page**

    - A confirmation page will show after the user submits the form. This page is set to return back to the home page after 10 seconds.  

![screenshot](../dressage_club/documenation/thankyou-page.png)
![screenshot](../dressage_club/documenation/home-page.png)


### Future Features

- Newsletter sign up in footer
    - Add an email form section in the footer for users to autmatically sign up to a newsletter, using bootstrap (https://getbootstrap.com/docs/5.0/forms/overview/). A newsletter is an easy way to boost the clubs network.
- Additional page for events
    - This page would include training events aswell as compeition events and a search bar for users to find events near them. This feature will make the wesbite more inclusive for users. 
- Multiple carousels in gallery page
    - Add more but smaller image carousels with bootstrap (https://getbootstrap.com/docs/4.0/components/carousel/). Tis will give a better aesthetic in my opinion. 

## Tools & Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [CSS](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- [CSS :root variables](https://www.w3schools.com/css/css3_variables.asp) used for reusable styles throughout the site.
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) used for an enhanced responsive layout.
- [CSS Grid](https://www.w3schools.com/css/css_grid.asp) used for an enhanced responsive layout.
- [JavaScript](https://www.javascript.com) used for user interaction on the site.
- [Git](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)
- [GitHub](https://github.com) used for secure online code storage.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [Gitpod](https://gitpod.io) used as a cloud-based IDE for development.
- [Bootstrap](https://getbootstrap.com) used as the front-end CSS framework for modern responsiveness and pre-built components.

## Testing

For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/MeganRoberts-dev/dressage_club), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://meganroberts-dev.github.io/dressage_club)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/MeganRoberts-dev/dressage_club) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://MeganRoberts-dev.github.io/dressage_club/`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/MeganRoberts-dev/dressage_club)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/MeganRoberts-dev/dressage_club)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

## Credits

### Content

| Source | Location | Notes |
| --- | --- | --- |
| [Markdown Builder](https://tim.2bn.dev/markdown-builder) | README and TESTING | Tool to help generate the Markdown files |
| [FreeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-html-forms-by-building-a-registration-form/step-64) | Signup page| Learnt to write forms|
| [YouTube](https://www.google.com/search?q=youtube+build+a+wesbite+with+boostrap+html+css&sca_esv=600400644&sxsrf=ACQVn0-adQy4ARdksw-_33ShG9sEzJEvtA%3A1705940667208&ei=u5auZfubDPG59u8Pk4eCgA0&ved=0ahUKEwi75eebtPGDAxXxnP0HHZODANAQ4dUDCBA&uact=5&oq=youtube+build+a+wesbite+with+boostrap+html+css&gs_lp=Egxnd3Mtd2l6LXNlcnAiLnlvdXR1YmUgYnVpbGQgYSB3ZXNiaXRlIHdpdGggYm9vc3RyYXAgaHRtbCBjc3MyCRAhGAoYoAEYCjIJECEYChigARgKSK0NUOECWPAMcAF4AZABAJgB-AGgAfIJqgEFMC43LjG4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIGECEYChgK4gMEGAAgQYgGAZAGCA&sclient=gws-wiz-serp#fpstate=ive&vld=cid:86481065,vid:ucPGbHzpVm0,st:00) | Entire site | Inspiration for my wesbites design |
| [YouTube](https://www.youtube.com/watch?v=gqOEoUR5RHg) | Boostrap tutorial | Tutorial for understanding boostrap |
| [CodeInstitute](https://learn.codeinstitute.net/dashboard) | Entire site | Gained knowledge and understanding of HTML/ CSS and web building |
| [Stackoverflow](https://stackoverflow.com/) | Entire site | Helped with troubleshooting |
| [Bootstrap v5.0.2](https://getbootstrap.com/docs/5.0/getting-started/introduction/) | Entire site/HTML files | used throughout site for a responsive design |


### Media


| Source | Location | Type | Notes |
| --- | --- | --- | --- |
| [Bootstrap](https://icons.getbootstrap.com/) | Footer | Icon | Social link icons|
| [Bootstrap](https://icons.getbootstrap.com/) | Home page | Icon | Trophy icon for events|
| [Shutterstock](https://www.shutterstock.com/image-photo/portrait-red-dressage-horse-young-woman-1725894646)(https://www.shutterstock.com/image-photo/horse-dressage-quadrangle-on-hoof-stroke-1332691166)(https://www.shutterstock.com/image-photo/equestrian-sport-portrait-dressage-horse-training-2053178834)(https://www.shutterstock.com/th/image-photo/top-view-girl-lies-on-horse-1725894073)(https://www.shutterstock.com/image-photo/dressage-portrait-sorrel-horse-on-nature-80416996)(https://www.shutterstock.com/sv/image-photo/black-dressage-horse-detail-isolated-on-483577879) | Gallery page | Image | Group of photos for gallery |
| [Pexels](https://www.pexels.com/photo/woman-sitting-on-a-horse-4894985/) | Gallery page | Image | Group of photos for gallery |

### Acknowledgements

- I would like to thank my Code Institute mentor, Tim Nelson (https://github.com/TravelTimN) for his support throughout the development of this project.
- I would like to thank the Code Institute Slack community (https://code-institute-room.slack.com) for the moral support; it kept me going and gave me additional motivation.