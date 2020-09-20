![Zoom logo](./assets/images/logo-small.png)

---

# Zoom Scooters

My project is to support a new business for E-Scooter Fleet management. The business will be deploying E-Scooters around the UK partly in response to COVID-19. UK goverment wanted a solution to public transport overcrowding and social distancing.

The project is designed to provide information to the public on what we do and why do it. Already there is a negative feeling about the addition of scooters due to the illegal use of personal E-Scooters, we intend to provide the facts and help show how E-Scooters are a good thing for the public. Including the home page I have focused on three pages:

- Home - Here I have given an introduction to what the company does, what we do and where we do it.
- About - This page goes into more detail with an interactive/collapsible FAQ style section to allow the user to read answers to the most common questions we recieve.
- Contact Us - Users have the oppertunity to fill out a contact form to send us a message or question and view our contact information.

---

## UX

The website is aimed at the public so I believe users will be a variety of age ranges. I have also used colours that match the green logo which was chosen to show E-Scooters are are clean alternative to fossil fuel transport options. The navigation bar also features the custom logo. On smaller screens, the navigation links compress behind a toggle button. The purpose of the website is to inform and entertain Ipswich Town fans.

Users:

- As a user, I'd like to learn more about what an E-Scooter Fleet Managment company is.
- As a user, I'd like to learn more about the E-Scooters and how they are charged.
- As a user, I'd like to learn more about how E-Scooters are maintained.
- As a user, I'd like to learn more about how E-Scooters are tracked and recovered
- As a user, I'd like to learn more about how E-Scooters are distributed across the cities.
- As a user, I want an easy way to get in touch to ask further questions or send a general message.

[Click here to see my full Wireframe](assets/wireframes/ZoomWireframes.pdf)

**Wirefram Deviation**: Comparison to the wireframes will show that I deviated from the sketches slightly with the content in each section. This is due to a delay in the launch of the business.
- Orginally I had planned to already be running the business by the time this project was completed, however due to delays outside my control the launch has not taken place.
- Cities were unconfirmed and statistics such as number of scooters in each area to hand and model of scooters deployed. This meant having a section dedicated to statistics did not make sense. 
- I considered doing the wireframs again after the site was completed however I felt this was disingenuous in nature and would not accurately show the true progression of the UX design process. I do feel however the overall UX design intentions were kept and achieved. 

**Navigation**: The navigation bar uses Bootstrap 4 features, responsiveness using a hamburger style button when on smaller devices and includes the custom logo designed for the company. The navigation bar has been used on all pages and is consistant across the site. To give the user an indication of which page they are currently on I have used a green bottom border on the active page.

**Footer**: I have used a simple footer design which has four social Font Awesome icons/links to Facebook, YouTube, Twitter and Instagram. To supplement these I have added the company 0800 phone number and parent company name. The footer is used consistantly across all pages.

**Home page**: I have used a hero/jumbotron with a background image of that changes across all three pages to keep interest. The images used are bought and licensed to the company from Adobe stock. The images used are all of E-Scooters in use in a fun, safe and natural manner. Below the hero image there is an introduction section with a breif information on the comapany, two further responsive images and a company tagline to reinforce the companies position. Below this I have added a functions section with the companies branded green colour taken from the logo. The function section has the four main task we complete with a bootstrap button to link to the about us page. Each of the functions uses a Font Awesome icon to reinforce each function. The entire function section uses the Bootstrap grid system for responsiveness and implements two rows and two columns. The cities section is next which displays cities where the company will deploy E-Scooters and the launch periods intended for each with a Font Awesome icon to complement. The standard footer finishes the page.

**About Us**: Keeping with consistancy the navbar, hero and introduction text section is reused here with alternative text and hero image. In the contrasting green section as seen on also on the home page I have included a collapsible unordered list in a FAQ style. Using Bootstrap 4 grid system, four rows with one function per row, each function has three questions which when clicked expand to show the answer. Each function section also sports the same Font Awesome icon used on the home page. The functions section is well responsive and works well on all devices. The page is finished with the standard footer.

**Contact**: Again navbar and hero are resused with alternative hero image. Following this is the contact form created using Bootstrap 4 features, this form is validated using the Code Institute validation tool. It features four form controls, name, email, message and a button. The button is plain as I did not want to overuse the green too much. Below the form is a section showing contact information with differnt styling to ensure good contract with the green background. The information in this section features clickable links to phone and email. Following this is the cities section as seen on the home page with the standard footer finishing the page.

![Responsive image with many different monitors](assets/images/responsive.jpg)

---

## Features

### Existing features

- The Home page features a jumbotron with a zoom effect to draw attention to it. The jumbotron text and background image will inform users what the website is about so I have added the effect to ensure it catches the eye of the user. The effect works on all screensizes.
- The shortcut icons on the Home page have a hover effect which both enlarges the icon but also inverts the colours. This draws attention to them and helps users know that they are clickable links.
- The Highlights page contains a background section. This section enables users to learn more about the state the club was in in 1999-2000. Failing in the play-offs in the 3 previous seasons is partly what made the 1999-2000 promotion more dramatic and this provides users with that knowledge.
- The Highlights page contains embedded YouTube videos of highlights of the three play-off matches. There are images of the games too. This enables users to experience the play-off matches.
- The Highlights page also contains a report of each match which enables users to learn more about them.
- The Meet the Players page contains a different visual effect; when player pictures are hovered over, they flip to show the player name. When football is broadcast on TV, player lines ups often feature images and some graphic effects so I wanted to add some sort of similar effect here. I also placed a football pitch in the background to make the page more visually appealing. This feature enables users to learn more about the key players involved in the matches.
- When clicking on the player images on the Meet the Players page, a modal window opens up (Bootstrap was utilised for this feature). The modal contains more images of the player and more information about them.
- Within the modals, a [Lightbox](https://www.lokeshdhakar.com/projects/lightbox2/) popout can be launched by clicking on any of the images. Users can then scroll through a handful of each player. I have used photos of the players from the 3 play-off matches to ensure they are relevant to the purpose of the website.
- The Share page contains a form which enables users to share their memories and photos. This form is currently only posted to Code Institutes code dump.

### Features for future implementation

If I was to continue the development of this website, I would look to add:

- A page for users to buy merchandise and memorabilia such as kits, matchday programmes, etc.
- A "Your Memories" page containing the photos and memories that people have uploaded to the website.
- A "What Happened Next" page which explains what happened to the team and the players after winning promotion.
- More players to the Meet the Players page, possibly adding the full squad and manager. Time constraints meant I only focused on 6 players up to now.

---

## Technologies Used

I used the following languages, frameworks and libraries to build this website:

- [HTML5](https://en.wikipedia.org/wiki/HTML5) - HTML5 was used to code the content of the website.
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - CSS3 was used to style the content.
- [Bootstrap](https://getbootstrap.com/) - Bootstrap was used to provide a grid structure, navigation toggle effect, navigation links on the Highlights page and multiple other styles by utilising Bootstrap classes such as margins, padding, allignment of text/objects, text decoration, etc.
- [Lightbox](https://www.lokeshdhakar.com/projects/lightbox2/) - This was used to create a picture slideshow for each player on the Meet the Players page. The Lightbox function is launched from within each players modal. The entirety of the [Lightbox CSS library](assets/css/lightbox.css) was downloaded.
- [FontAwesome](https://fontawesome.com/) - FontAwesome was used to insert icons into the webpage. These appear in the Home page as shortcut icons, in the footer as the social media links, on the Highlights page next to goalscorers and in the Meet the Players modals. I also replaced the Bootstrap navigation toggle icon with one from FontAwesome.
- [Google Fonts](https://fonts.google.com/) - Google Fonts have been used to style the text in the website. The header contains the webpage name which has Merienda One font applied, Didact Gothic font is applied to headers and the navigation menu links and the rest of the text is Roboto font.
- [FavIcon](https://www.favicon-generator.org/) - This webpage was used to create the small favicon which appears in the webpage tab. I used the football club logo which appears in the header.

**Not used**: [Hover](https://ianlunn.github.io/Hover/) - Early on in the project, I did add this library thinking that I would utilise it to apply extra hover effects to various elements. However, as I developed the project, I found that using CSS hover effects was giving me the results I was looking to acheive. Thus I ended up removing this CSS library and HTML links from my project.

---

## Testing

### Bugs

The ITFC logo and "One Day In May" text appears in the header (although the ITFC logo disapears on extra-small and small screens). They act as a shortcut to the Home page. Early on in the project I noticed that when hovering over them, a blue line appeared underneath them when I hovered over them. This is built in behaviour which effects all achor elements. To fix this, I created a pseudo-class in my [CSS](assets/css/style.css) to remove all text decoration from anchor elements. This enabled me to then style anchor elements how I wanted and removed the unwanted blue line appearing under the logo and text in my header when I hovered over them.

On the Home page, I used Bootstrap to change the layout of the 3 shortcut icons. However, because the Bootstrap column widths are responsize, as the screen width changed, the size of the icon container changed. But because I used a FontAwesome icon which is a text element, it was not responsive - the font size was fixed. I tried a variety of font-sizes but was finding that one font-size was not appropriate as it would either make the icons look too big on small screens and/or too small on big screens. I could have set up media-queries to change the font size at various breakpoints. However, opted to use a viewport width font-size. This ensures the icon size changes as the width of the screen and thus the column and containers change. Working from large screens down to small, when the medium screen size (width = 768px) is reached, the shortcuts vertically align meaning each one has more width on screen. at this point, I felt the icons were too small so created a media-query rule to increase the font-size to a larger viewport width.

On the Highlights page, I initially had the score displayed in one row with the goalscorers for each team in a second row underneath. The first row contained columns for the home team, home team score, away team score and away team. The second row contained columns for the home team goalscorers and the away team goalscorers. This layout looked good on larger screens but on smaller screen sizes, the team names and goalscorers became cramped and was not visually pleasing. To resolse this, I put all elements into one row but changed the column sizes so that on mediums screens, the goalscorers would automatically overflow underneath. I also used the Bootstrap order class to change the order of each item. The result is that on extra-small and small screen sizes, the home team and home team score appears beside each other with the goalscorers underneath, then underneath that the same layout is repeated for the away team. But on medium size screens and up, the layout appears the same way as I originally intended.

### Speed Tests

I ran speed tests on each page using [GTmetrix](https://gtmetrix.com/). Following this, I reduced all of the images on my website using [tinyPNG](https://tinypng.com/). I also replaced the [Lightbox jquery file](assets/javascript/lightbox-plus-jquery.min.js) with a compressed version. I then ran the speed tests again to check whether the performance of the website has improved.

Below are the before and after screenshots of the tests. The page sizes have reduced and the perfomance score for each page has improved:

![Home page initial test](assets/images/speed-tests/home-initial-test.png)
![Home page second test](assets/images/speed-tests/home-second-test.png)
![Highlights page initial test](assets/images/speed-tests/highlights-initial-test.png)
![Highlights page second test](assets/images/speed-tests/highlights-second-test.png)
![Meet the Players page initial test](assets/images/speed-tests/meet-the-players-initial-test.png)
![Meet the Players page second test](assets/images/speed-tests/meet-the-players-second-test.png)
![Share page initial test](assets/images/speed-tests/share-initial-test.png)
![Share page second test](assets/images/speed-tests/share-second-test.png)

### Further Tests

1. Home page:

   1. All links tested. Internal links all work. External links all work and open in new window.
   2. The page is responsive and looks good on all screen sizes.
   3. The user is able to quickly see that the website is related to Ipswich Town by way of the jumbotron background image and on larger screens, the ITFC logo in the header.
   4. The introduction section underneath the jumbotron give context about the website meaning users are quickly able to identify if the website is of interest to them.
   5. The shortcuts links underneath the introduction ensure users can identify what content is available and how to access it.
   6. Code has been successfully tested through the [Markup Validator](https://validator.w3.org/)

2. Highlights page:

   1. All links tested. Internal links all work. External links all work and open in new window.
   2. Several internal links have been added to enable users to navigate content on the page more easily. Some reports are quite long so these links were added to avoid users having to scroll up and down the page and thus improve user experience.
   3. During testing of the page, I noticed that the background text would align left once the Bootstrap small screen size was reached whilst the text in the highlights section below would only align left once Bootstraps large screen was reached. To ensure consitent flow of the page, I ensured that all text alignments on the page changed at the same screen size; up to small breakpoint (576px) the text is center-aligned and above this, aligns left. This is the same breakpoint at which images are centered on their own or floated next to the text. This consistency will improve user experience.
   4. Having made the above fix, I am confident the page is responsive and looks good on all screen sizes.
   5. The background section and match reports enable users to learn more about the play-off matches.
   6. The YouTube videos and images enable users to experience the play-off matches.
   7. Code has been successfully tested through the [Markup Validator](https://validator.w3.org/)

3. Meet the Players page:

   1. All links tested. Internal links all work. External links all work and open in new window.
   2. The page is responsive and looks good on all screen sizes.
   3. All modals open as expected and close as expected when clicking either the cross button, close button or clicking outside of the modal.
   4. All images in the modal open the Lightbox at the correct part of the slideshow.
   5. The contents of the modals enable users to learn more about some of the players and they can read further by opening their Wikipedia page (in a new window) using the link provided.
   6. Code has been successfully tested through the [Markup Validator](https://validator.w3.org/)

4. Share page:

   1. All links tested. Internal links all work. External links all work and open in new window.
   2. The page is responsive and looks good on all screen sizes.
   3. The form contains two required fields, name and email address. If either of these are blank when the user tries to submit the form, default error messages appear.
   4. If the user doesn't enter a valid email address, the default error message notifies them.
   5. The Reset button behaves as expected.
   6. The Send button posts the form data to Code Institutes form dump page as expected.
   7. Code has been successfully tested through the [Markup Validator](https://validator.w3.org/)

5. style.css
   1. 6. Code has been successfully tested through the [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/)

---

## Deployment

This webpage has been deployed to [GitHub pages](https://lukegarnham.github.io/One-Day-In-May-MS1/).

---

## Credits

### Content

Where code has been copied from an external source, I have referenced this in the code through comments. In many cases, the copied snippet has been amended from the source in order to achieve the desired result for this project. I have listed the various sources below as well.

**Head**

- All CDN links copied from the respective sources - see links above in the **"Technologies Used"** section.
- The FavIcon code snippet was taken from [Digital Ocean](https://www.digitalocean.com). I viewed the source of the home page and copied the code to my site. The Favicon image was created along with my logo from a designer sourced from [Design Crowd](www.designcrowd.com)
- The Apple icons for use on iPhone and iPad code snippet was taken from [Digital Ocean](https://www.digitalocean.com). I viewed the source of the home page and copied the code to my site. The Apple icon image was created along with my logo from a designer sourced from [Design Crowd](www.designcrowd.com)

**Header**

- In the header, the nav element code used to create a toggle menu on small screen sizes was copied from [Bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/#nav).

**Highlights page**

- On the Highlights page, I created tabs to separate the highlights of the 3 matches. I copied code from [Bootstrap](https://getbootstrap.com/docs/4.5/components/navs/#javascript-behavior) to achieve this.

**Meet the Players**

- A portion of HTML code and CSS code was copied from [this website](https://www.w3schools.com/howto/howto_css_flip_card.asp) in order to create the flip-card effect on the player images. Some of the style rules were amended to suit the desired needs of this webpage.
- The code for the player modals was copied from [Bootstrap](https://getbootstrap.com/docs/4.0/components/modal/#vertically-centered). The actual contents of the modals is original work and has not been copied.
- The [Lightbox CSS library](assets/css/lightbox.css) and [Lightbox jquery file](assets/javascript/lightbox-plus-jquery.min.js) were downloaded in their entirety from [this website](https://www.lokeshdhakar.com/projects/lightbox2/#getting-started).

### Media

**YouTube**

- The YouTube videos of the 3 play-off matches are all ones recently posted by the official ITFC YouTube channel recently to mark the 20 year anniversary.
  1. [Game 1](https://www.youtube.com/watch?v=uzy3y_B1LJ0)
  2. [Game 2](https://www.youtube.com/watch?v=vYSh2FyACbM)
  3. [Game 3](https://www.youtube.com/watch?v=K0NsebNs1Cw)

**Images**

- The images used in the project have been found using Google searches. Unfortunately, there is no freely available repository for the images required. I found a series of high quality images on [Getty Images](https://www.gettyimages.co.uk/) all of which have a watermark on unless they are purchased. This meant some of the images used in the website are not high resolution/high quality though I did try to use the best images freely available.
- Some images were found in recent news articles which were published to mark the 20 year anniversary of the teams promotion.
  1. [Article 1](https://www.twtd.co.uk/ipswich-town-news/38311)
  2. [Article 2](https://www.eadt.co.uk/sport/ipswich-town-v-bolton-play-off-semi-final-1-6652862)
  3. [Article 3](https://www.eadt.co.uk/sport/ipswich-town-win-at-wembley-may-2000-1-6675069)
