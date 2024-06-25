# Vincent van Gogh

## Overview
The Vincent van Gogh website is designed to provide a look at the life and works of one of the most famous artists in history. This project aims to educate and inspire art enthusiasts, students, and researchers by offering information about Van Gogh's paintings, his biography, and his impact on the modern world. The website serves as a valuable resource for those interested in learning more about his artistic journey and the legacy he left behind.

## Responsive Mockup

![Responsive Mockup](/assets/images/photos_for_readme/amiresponsive.png)

## Features

### Existing Features

## Main page

#### Navigation Bar
- Featured on all pages, the fully responsive navigation bar includes links to the Home page, Biography, Gallery, and In Modern Culture page. The logo is linked to the Home page. It ensures easy navigation across all devices without the need to use the browser's back button.
![Navigation Bar](/assets/images/photos_for_readme/nav_bar.png)

#### Navigation Grid Menu
- The Navigation Grid Menu includes tiles linked to the Biography, Gallery, and In Modern Culture pages with high-quality images of Van Gogh's masterpieces in the background with a text overlay, instantly capturing the user's attention and setting the tone for the site.
![Navigation Grid Menu](/assets/images/photos_for_readme/grid_menu.png)

#### Articles Section
- This section provides a list of three articles on the topic of Vincent van Gogh. The main feature of this section is that each article can be opened and closed with one click using the details and summary pair.
![Articles Section](/assets/images/photos_for_readme/articles_serction.png)

#### Sign-Up section
- Gives users the opportunity to join the mailing list to get news about updates.
![Sign-Up section](/assets/images/photos_for_readme/sign_up.png)

#### Footer
- Featured on all pages, includes links to social media profiles. These links open in a new tab, ensuring users can easily stay on the website.
![Footer](/assets/images/photos_for_readme/footer.png)

## Biography page

#### Biography section
- Includes an article about Van Gogh's biography.
![Biography section](/assets/images/photos_for_readme/biography.png)

## Gallery page

#### Navigation Grid Menu
- The Navigation Grid Menu includes tiles linked to the Portraits, Self-Portraits, Flowers, and Cityscapes and Landscapes sections of the gallery page with high-quality images of Van Gogh's masterpieces in the background with a text overlay, instantly capturing the user's attention and giving them an understanding of what they can find on this page.
![Navigation Grid Menu](/assets/images/photos_for_readme/gallery_grid_menu.png)

#### Gallery section
- The Gallery includes four sections: Portraits, Self-Portraits, Flowers, and Cityscapes and Landscapes. Each section is a grid of painting photos with captions underneath.
![Gallery section](/assets/images/photos_for_readme/gallery_section.png)

## In modern culture page

#### Article section
- Includes the article "Van Gogh: Films and Documentaries" that provides users with a list of films and documentaries about Van Gogh. This article also gives links to IMDB and Rotten Tomatoes pages that open in a new tab.
![Article section](/assets/images/photos_for_readme/in_modern_culture.png)

### Features Left to Implement
- **Discussion Forum**: A community space for art enthusiasts to discuss Van Gogh’s works and share their insights.
- **Expand articles section on Main page**: Adding more articles to the section will attract new users and retain existing ones.
- **Expand articles section on In modern culture page**: Adding more articles to the section will attract new users and retain existing ones.
- **Expand Gallery page**: Adding more photos of Van Gogh's paintings to the Gallery page will attract new users and retain existing ones.

## Testing
- I tested that this website works in different browsers: Firefox, Avast Browser, Chrome, and Chrome for mobile.
- I confirmed that this website is responsive, meets accessibility standards, and looks good on different screen sizes using the devtools toolbar.
- I confirmed that all sections on all pages are readable and easy to understand.
- I confirmed that the sign-up form works well: it will not submit until the required fields are filled, the email field accepts only email addresses, and the submit button works.

### Bugs
#### Solved bugs
- When I checked the website through the W3 validator I noticed that a number of errors were made:
1. A p tag was inside the summary.
2. A script was in the body.
3. One of the sections was without a heading.
- Added h2 heading to the articles section. Moved the p tag from summary to details. Moved the script to the head.

### Validator Testing
- **HTML**: No errors were returned when passing through the official W3C validator.
- **CSS**: No errors were found when passing through the official (Jigsaw) validator.
- **Accessibility**: I confirmed that the colors and fonts chosen are easy to read and accessible by running it through Lighthouse in devtools.
![Lighthouse](/assets/images/photos_for_readme/lighthouse.png)

### Unfixed Bugs
No unfixed bugs

## Deployment
The site was deployed to GitHub Pages. The steps to deploy are as follows:
1. In the GitHub repository, navigate to the Settings tab.
2. On the left side, choose Pages.
3. From the Branch section select the `main` branch and press Save.
4. Once the `main` branch has been selected, the page will automatically refresh with a detailed ribbon display to indicate the successful deployment.

The live link can be found here: [Vincent van Gogh Website](https://mykhailovasylkov.github.io/Vincent-van-Gogh/)

## Credits

### Content
- All text content was created in Chat-GPT.
- Favicon was created in https://favicon.io/
- Font Awesome kit was taken from Running Club Project.
- For the mobile menu, I used a code snippet from the Running Club Project.
- For the Grid Menu, I used this lesson: https://www.w3schools.com/css/css_grid.asp
- The action attribute was used from the Running Club Project.
- I used Chat-GPT to figure out how to add a background image to the body that will be fixed and won't change size.
- I used Chat-GPT to figure out how to change size when hovering over links without changing the position of neighbors.
- For overwriting the default summary sign, I used materials from these articles:
1. https://www.w3schools.com/tags/tag_summary.asp
2. https://www.sitepoint.com/style-html-details-element/
- To figure out how to make the grid menu on the Gallery page responsive, I used  https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns
- For the dropdown menu, I used a code snippet from the Running Club Project.

### Media
- Photo gallery.webp was taken from https://unsplash.com/photos/silhouette-of-people-in-cave-c7xBEFBJhkg
- All other photos was taken from https://commons.wikimedia.org/
