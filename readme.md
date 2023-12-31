# Marelius Moen's Online CV
-----
This is the online CV for Marelius Moen and this project is made to increase my personal visibility online, to be a landingsite for potential employer, collaberators and collegues. It will serve as a more professional display compared to the personal Instagram and and Facebook accounts that is used to show what I do on my own time, both of these accounts have a link in the footer and they will continue to be used for private content about my everyday life with friends and family.

<img src="assets/images/screen-shot-responsive.png" width="600px">

# User stories
As the sole developer of this website, my goal is to secure employment opportunities in the web development area as well as other potential employment in the area of IT. I came up with the following points, which are applicable to the users:

- As a user, I want to understand the purpose of this website quickly and easily.
- As a user, I want to easily navigate this website (by using a mouse, a keyboard, or a touch screen).

- As a user, I want to view this candidate's work and education history and skills.
- As a user, I want to know what technical languages and tools this candidate is able to work in, as well as the candidate's language proficiency.
- As a user, I want a way to contact this candidate.
- As a user, I want to get a copy of the candidate's traditional CV.

## Strategy
The goal is to make a well-functioning professional CV website. The focus was on making the design both user-friendly and creative.

## Scope
For the users (employers and recruiters), I wanted to give them a good overview of myself (Anjalee Kulasinghe), focusing on my experience, education, and skills. This way, the users can get a better idea of who I am and whether I am a potential candidate for the vacancy. As well, I kept the traditional CV format so it would be easy for the users to find information about me.

## Structure
I followed the traditional CV framework since it is not overly complicated and it will be easy for the users to find the information they are looking for. The Online CV website has a single, long, scrolling page design. My structure features a fixed top navigation that connects the user to each of the sections from anywhere on the page. I have also included a link at the end of the navigation to download a copy of the traditional CV if the user likes that format.


# Wireframe

These are the initial plans and the design sketches for this site:
<img src="assets/images/1st-sketch.jpg" width="300">

And then some more refined design and structure:

index section sketch
<img src="assets/images/index-html.jpg" width="300">

about me section sketch
<img src="assets/images/aboutme-html.jpg" width="300">

contact section sketch
<img src="assets/images/contact-html.jpg" width="300">

# Design changes early in the process

It seemed more intuitive for the user and better from a design POV for achieving a uniform style and size, so I decided that it would be better for the UI to have 5 sections that were responsive to different screen-sizes instead of 5 different pages.
The colors where also changed to a darker purple combination that gave a more professional feel.


# Features 
The page will be quick glimpse in to Marelius Moens work experiences, education & certificates and an easy way to get in touch or send business propositions. 

<img src="assets/images/welcome-part-screenshot.jpg" width="300px">

- The site features a responsive navigation bar that takes you to the different sections of the site, and the navigation bar will follow you on your journey while you’re scrolling further down the page.

- There’s a picture of Marelius Moen himself, with a descriptive alt text for accessibility. There is also an audio player with controls that let you hear how to pronounce the name before an eventual meeting/phonecall.

<img src="assets/images/about-me-screenshot.jpg" width="300px">

- The “About me” section contain a paragraph that in a playful way tells you some background story to why Marelius has the values and work-ethic that he puts pride in today. This paragraph does not explain to much, but makes you curios to know more.

<img src="assets/images/education-screenshot.jpg" width="300px">

- The “Education” section is a short list that precisely informs you about the courses, school and certifications he has completed/attends now, and it also tells the user where in the world he did it. This list is responsive and will show in the same order but fit to smaller screen sizes.

<img src="assets/images/work-screenshot.jpg" width="300px">

- The “Work experience” section is a short list that precisely informs you about the positions, workplaces and timeperiod he worked there, and it also tells the user where in the world he did it. This list is responsive and will show in the same order but fit to smaller screen sizes.

<img src="assets/images/contact-footer-screenshot.jpg" width="300px">

- The “Contact” section has a Get in touch header and 2 active direct link-icons for email (represented by a paperplane icon) and phonecall (represented by an old-school mobile phone icon). 
-The second part of the “Contact” section is a contact form, with required inputs for: First Name, Last Name, Email (Email input value), and a subject text.

- The footer at the bottom of the site is intuitively placed as clos to the contact me section as possible, to make it as smooth as possible to know which options for reaching out that exsists for the user. The footer contains active link icons for Marelius Moens GitHub profile, Instagram profile, Facebook profile and a download link to download his CV/resume in a traditional layout PDF-file.


# Features left to implement
- When uploaded to a server, make the contact-form operational.
- Submit confirmation HTML page needs background responsiveness for mobile screens

# Bugs
- Struggled with achieving a uniform style and size when I had multiple pages, so I decided that it would be better for the UI to have 5 sections that were responsive to different screen-sizes instead.
- The inital color scheme I imagined for the project didn’t go well together, so with I decided to go more towards a dark-purple and black color scheme for a more proffessional look.
- The image was turning egg-shaped when I added the border-radius styling, the solution was to have the image file being completely square.
- Struggled with the positioning of the sections and then within the sections the content, had to redo the whole positioning with flex-styling and adding/removing divs where needed.
- Getting the header background to be the right size and responsive to different screen sizes, had to change width from px to %.

# Testing & validation
- The site works on different screensize and the elements are responsive, looks good and are functional. This test was carried out on a Iphone 14max and in Chrome devtools.
- I confirmed that the header-, navigation-, about me-, education-, experience-, contact- and footer-part of the project are intuitive, easy to read and understandable.
- I've testet that the form works, the first name, last name, email, and subject are all required and the submit button works. When submitting it sends you to another page that thanks you for getting in touch and has a link back to the welcome section. (This is because the project is a front-end project and does not have a dedicated server yet) .

- HTML, no errors or warnings when run through the official W3C validator.
- CSS, no errors or warnings when run through the official W3C validator (jigsaw).
- Top scores in the Lighthouse performance test.
<img src="assets/images/lighthouse-score.png" width="300px">

# Deployment and how it was deployed
This site was deployed to GitHub Pages and this is the method I used:
From the GitHub repository go to the settings, in the source-section dropdown menu select master branch.
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

# Credits

## Content
- The main background effect & background pattern on the header and footer where inspired by the guide at codepen.io. (https://codepen.io/bitmap/pen/AzowBq)
- The box-shadow styling I found at developer.mozilla.org. (https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)
- All the icons are free from fontawesome.com.
- Contact-form and how to change the placeholder-text-color is inspired by the code found in the w3school guide to creating a form with html/css. (https://www.w3schools.com/cssref/sel_placeholder.php)
- The User stories part of this readme.md file is copied from a former students readme file as I could not see anyway to improve it's content for this page. (https://github.com/anjalee-kulasinghe/portfolio-project1-cv-website/blob/main/README.md)

## Media
- Picture taken by Anna Marxen at Deilig Media, used on this website with her permission. ( https://www.deiligmedia.se ).

[def]: ssets/images/mareliusmoen.github.io_marelius-online-cv_4k-screen.pn