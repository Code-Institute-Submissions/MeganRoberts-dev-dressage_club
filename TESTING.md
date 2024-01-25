# Testing

Return back to the [README.md](README.md) file.

The site has been tested through HTML and CSS validators and in 3 different browsers for a Windows PC - Chrome, Firefox and Edge, the site passed all test. Manual testing was also conducted for the main feauters, all of these test were also passed. The site proved to be responsive when tested on different devices - including mobile (iPhone 12 mini and Samsung Galaxy S20), ipad and desktop. Lighthouse audit was conducted, the site met satisfactory requirements but did show some minor warnings. I have noted the fixed and remaining bugs for the site in this testing file. Please see below to view all of my findings. 

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

![screenshot](../dressage_club/documenation/w3-validator.png)

My deployed URL is - https://validator.w3.org/nu/?doc=https%3A%2F%2Fmeganroberts-dev.github.io%2Fdressage_club%2F.


| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmeganroberts-dev.github.io%2Fdressage_club%2F) | ![screenshot](../dressage_club/documenation/home-page.png) | Delineated sections, clear images, heading, text and icons. Responsive.|
| Gallery | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmeganroberts-dev.github.io%2Fdressage_club%2F) | ![screenshot](../dressage_club/documenation/gallery.png) | Clear heading, responsive and working carousel on all devices |
| Sign up | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmeganroberts-dev.github.io%2Fdressage_club%2F) | ![screenshot](../dressage_club/documenation/signup.page.png) | Clear heading, responsive form and working submit button. Fill field feauture working.|
| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmeganroberts-dev.github.io%2Fdressage_club%2F) | ![screenshot](../dressage_club/documenation/thankyou-page.png) | Text is clear, all links work and the page will refresh back to the home page after 10 seconds |
| Navigation (desktop) | (https://meganroberts-dev.github.io/dressage_club/)| ![screenshot](../dressage_club/documenation/navbar-desktop.png) | Navigation links click through to correct location and club name navigates to home page|
| Navigation (mobile) | (https://meganroberts-dev.github.io/dressage_club/)| ![screenshot](../dressage_club/documenation/navbar-mobile.png) | Navigation links click through to correct location and club name navigates to home page |
| Footer links | (https://meganroberts-dev.github.io/dressage_club/)| ![screenshot](../dressage_club/documenation/footer-validator.png) | Social links in footer navigate to correct social sites (X, Facebook and Instagram) and links open in new tabs. This is the same on all pages.  |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

- https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmeganroberts-dev.github.io%2Fdressage_club%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmeganroberts-dev.github.io%2Fdressage_club%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](../dressage_club/documenation/CSS-validator.png) | Pass: No Errors |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Gallery | Signup | Confrimation | Notes |
| --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](../dressage_club/documenation/chrome.png) | ![screenshot](../dressage_club/documenation/chrome-gallery.png) | ![screenshot](../dressage_club/documenation/chrome-signup.png) | ![screenshot](../dressage_club/documenation/chrome-confirmation.png) | Works as expected |
| Firefox | ![screenshot](../dressage_club/documenation/firefox-home.png) | ![screenshot](../dressage_club/documenation/firefox-gallery.png) | ![screenshot](../dressage_club/documenation/firefox-signup.png) | ![screenshot](../dressage_club/documenation/firefox-confirmation.png) | Works as expected |
| Edge | ![screenshot](../dressage_club/documenation/edge-home.png) | ![screenshot](../dressage_club/documenation/edge-gallery.png) | ![screenshot](../dressage_club/documenation/edge-signup.png) | ![screenshot](../dressage_club/documenation/edge-confirmation.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Gallery | Signup | Confirmation| Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile (iPhone 12 Mini) | ![screenshot](../dressage_club/documenation/iphone-test.png) | ![screenshot](../dressage_club/documenation/iphone-gallery.png) | ![screenshot](../dressage_club/documenation/iphone-signup.png)| ![screenshot](../dressage_club/documenation/iphone-confirmation.png) | Works as expected |
| Mobile (Samsung Galaxy S20 Ultra)| ![screenshot](../dressage_club/documenation/samsung-test.png) | ![screenshot](../dressage_club/documenation/samsung-gallery.png) | ![screenshot](../dressage_club/documenation/samsung-signup.png) | ![screenshot](../dressage_club/documenation/samsung-confirmation.png) | Works as expected |
| Tablet (iPad 10th Gen) | ![screenshot](../dressage_club/documenation/ipad-test.png) | ![screenshot](../dressage_club/documenation/ipad-text-gallery.png) | ![screenshot](../dressage_club/documenation/ipad-test-signup.png) | ![screenshot](../dressage_club/documenation/ipad-confirmation.png) | Works as expected |
| Desktop (Mac Senosa)| ![screenshot](../dressage_club/documenation/mac-testing.png) | ![screenshot](../dressage_club/documenation/mac-gallery.png) | ![screenshot](../dressage_club/documenation/mac-signup.png) | ![screenshot](../dressage_club/documenation/mac-confirmation.png) | Works as expected |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](../dressage_club/documenation/lighthouse-mobile-home.png) | ![screenshot](../dressage_club/documenation/lighthouse-desktop-home.png) | Some minor warnings, Slow response time due to large images, Not enough Meta description  |
| Gallery| ![screenshot](../dressage_club/documenation/lighthouse-mobile-gallery.png) | ![screenshot](../dressage_club/documenation/lighthouse-mobile-gallery.png) | Some minor warnings, Slow response time due to large images  |
| Signup | ![screenshot](../dressage_club/documenation/lighthouse-mobile-signup.png) | ![screenshot](../dressage_club/documenation/lighthouse-desktop-signup.png) | Responsive |


## User Story Testing


| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to simply navigate through the site, so that I can accsess the page I want quickly. | ![screenshot](../dressage_club/documenation/navbar-desktop.png) |
| As a new site user, I would like to have clear content, so that I can read information easily and understand the site. | ![screenshot](../dressage_club/documenation/about-box.png) |
| As a new site user, I would like to use an easy and efficient signup form, so that I can be sure I have signed up.| ![screenshot](../dressage_club/documenation/signup.page.png) |
| As a new site user, I would like to view and use the site on my moible, tablet or desktop, so that I can have full access.| ![screenshot](../dressage_club/documenation/iphone-home.png) |
| As a returning site user, I would like to use the contact info in the footer multiple times.| ![screenshot](../dressage_club/documenation/footer-icons.png) |
|As a site administrator, I should have easy read HTML an CSS code so that other developers can work with the code. | ![screenshot](../dressage_club/documenation/w3-validator.png) |
| As a site administrator, I should be able to easily add or remove new features so that I can maniuplate the website. | ![screenshot](../dressage_club/documenation/CSS-validator.png) |
| As a site administrator, I should have flexible code that allows me to add new content at the request of a client. | ![screenshot](../dressage_club/documenation/index.html-validator.png) |

## Bugs


-Bug in signup form. Fixed on Jan 19th, 2024.

    ![screenshot](../dressage_club/documenation/bug-signup.png)

    - To fix this, I corrected the id names and validation.

- Bug in dropdown option section of the form. Fixed in Jan 19th, 2024.

    ![screenshot](../dressage_club/documenation/bug-form.png)

    - To fix this, I added correct values to each option.

- Bug in index html file. Fixed Jan 19th, 2024.

    ![screenshot](../dressage_club/documenation/bud-validation.png)

    - To fix this, I corrected the validation errors.

- Bug in form section of signup. Html not working in preview. Fixed Jan 19th, 2024.

    ![screenshot](../dressage_club/documenation/bug-section>form.png)

    - To fix this, I changed the "form" attribute to "section".

- Bug in carousel. Images not centered. Fixed Jan 19th, 2024.

    ![screenshot](../dressage_club/documenation/bug-carousel.png)

    - To fix this, I used bootstrap in the validation and added buttons for every image.

## Unfixed Bugs

- Container of navbar links on desktop.

    ![screenshot](../dressage_club/documenation/navbar-desktop.png)

    - Attempted fix: I tried changing the size of the container but this effected the burger dropdown menu on mobile.

- Burger menu links on tablet/ mobile.

    ![screenshot](../dressage_club/documenation/burger-dropdown.png)

    - Attempted fix: I tried changing the size of the container but this effected the navbar on desktop and the spacing between links.

There are no remaining bugs that I am aware of.
