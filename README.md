# **BE MINDFULL**

Be Mindfull is a website designed to help beginners into meditation. It has 3 sections for the user: 
- The first section will explain the benefits to the user.
- The second section will ease the user into it and has a video for a guided meditation session.
- The last section includes a form for the user to sign up for tips and motivation. 

The overall visual design is clean and tranquil to resonate with the content and will inspire users to start their meditation journey.

To view the deployed website click [here](https://debbie-herridge.github.io/mindfull-meditation/index.html)

![Am I Responsive image](/assets/images/am-i-responsive.png)

# UXD

## Website intentions

For the user:
```
- To gain an insight into the personal benefits for meditation.
- To gather an understanding of what it is.
- To do their first guided meditation session.
```

For the site developer:
```
- To inspire calmness in the user with the visuals.
- To provide good information for the user to start their journey.
- To motivate users to watch and follow the guided session.
```

## Creation process

### 1.Strategy
It is a B2C Website for meditation beginners, the site needs to provide quality information and motivate users to sign up.

### 2.Scope
It will have minamilist design, there is going to be basic features such as navagation bar and images, but the whole design needs to be consistant. It will include a video which needs to be consise and educational.

### 3.Structure
A large visual representational image on the home page below a clean simple heading and nav bar.

Three sections:
- Why - bold benefits in text blocks that respond well to screen size changes.
- How - a breif explaination and large video with user controls.
- Why - a breif explaination and a simple form.

### 4.Skeleton

Using Balsamiq I created the wireframe for my site:

![Balsamiq all pages](/assets/images/balsamiq-all-pages.png)

For a large view of each page please follow the links below:

[Why page](https://github.com/debbie-herridge/mindfull-meditation/blob/main/assets/images/balsamiq-page-one.png) -
[How page](https://github.com/debbie-herridge/mindfull-meditation/blob/main/assets/images/balsamiq-page-two.png) - 
[Where page](https://github.com/debbie-herridge/mindfull-meditation/blob/main/assets/images/balsamiq-page-three.png)

### 5.Surface

I will use google fonts and choose two fonts that pair well, so that the title is capitvating and the text is easy to read.
For the colour scheme I will use grey for the text, opting for a darker grey for the headings and slightly lighter for the text. This is to enhance a subtle emphasis for the content on the ivory background.

## Page Features 

### Header and Nav
The navagation consist of three links, to sections 'why', 'where' and 'how'. It is large and bold.
![Header and Nav](/assets/images/header-nav-screenshot.png)

### Main image
The main image is fitting for the page in what it shows and also the colour schemes. It also contains a motivation quote to inspire readers. Both image and text respond in a appealing way when the screen size is changed.
![main image](/assets/images/Main-image.png)
![main image small](/assets/images/main-image-small%20screen.png)

### Benefits section
Each benefit is contained in its own border to separate them and give them all an equal importance. Each benefit will react and fill the page in a captivating way.

![benefits large screen](/assets/images/responsive-benefits-screenshot-3.png)
![benefits medium screen](/assets/images/responsive-benefits-screenshot-2.png)
![benefits small screen](/assets/images/responsive-benefits-screenshot-1.png)

### Video section
The video has been imported from YouTube with the credit to the creator below. The video is in theme, simple and concise with a calming approach. It will talk the user through their first guided meditation session. It is centered as large as possible on the screen so that the user can clearly see and follow it without having to leave the site.  

![Meditation video](/assets/images/video-screenshot.png)

### Sign up form
A sign up form is at the bottom for users to input their name and email address for emailed tips and motivation. This will help further motivate the user to keep up with their journey even after leaving the website. Its simple with a large subscribe button to invite the user to join.

![Sign up form](/assets/images/form-screenshot.png)

### Footer

#### Image
The image is in a similar theme and colour scheme to compliment the image below the header, this gives the site a more harmonizing feel. The image is centred so that even when reducing the screen size the man is the photo will always be in the middle.

#### Social Media links
Links to social media sites - Youtube, Twitter and Facebook. Are represented by their icons which gives a clean look to the footer.

![Footer image](/assets/images/footer-screenshot.png)

### Future features
A 'back to the top' button would aid the navagation of the page saving users to scroll up to use the nav section again.

# Design changes 
The inital skeleton design was to have three pages, after writing the code and viewing it online the site lacked enough content to have a satisfying scroll. Therefore I transferred the code from the pages into my index file. I then decided to add the image to the footer to incase the content of the site between two complimenting images.

# Testing

### HTML Validator 
Initially the code didn't pass the HTML Validator as I had used two ID tags on the same div, one for the navagation and the other for the styling. I corrected this by removing the styling id and styled it using the general heading styles.

![html validator](/assets/images/html-validator.png)

### CSS Validator
At first the code did not pass as I had not included a '#' before the hexidicamal colour. This was quickly resolved and so my code passed the validator.

![css validator](/assets/images/css-validator.png)

### Personal testing
I have tested and built this site on Mac Safari, I have viewed it on Chrome and Microsoft edge and all works perfectly.

I have also tested it on an Iphone 11 Pro Max, for other mobiles I used the Google DevTools to view what it would look like. 

A bug that has appeared on almost all screens is a slight gap on the right hand size of the screen, I believe it to be the horizontal line pushing the screen by a couple of pixels, it is a visual error and does not effect the site but I will fix this bug in the future.

### Issues and their solutions
I came across issues when ensuring the site stayed visually appealing when the screen size was changed. The first issue was the text in the main image below the header, I did not want the lady in the photo to be covered when the size descaled. I solved this to make the text align left for sizes below 1000px.

Another issue was the benefits section, initally I had a fixed height for each div section but when changing the size of the screen it didn't look right, so I corrected this by adding padding around the text and changing the height to auto for sizes below 1000px.

My biggest issue was with the form, I changed the design from the skeleton phase to float the text description left and the sign up form right. This looked sleek when it was full screen but was proving time consiming to ensure it looked just as sleek on small screens, this was due to absolute margins and padding that I struggled to override when doing the media query. It had become a time consuming issue so I removed the float and using Google DevTools I changed the margin and padding on all id's. In hindsight it looks more consistant with the site now as a single scroll beause it matches the section above. 

# Deployment 
The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

Click [here](https://github.com/debbie-herridge/mindfull-meditation) to view my GitHub repository.

# Credits 

## Content
For the benefits of meditation I used [Cano Health](https://canohealth.com/news/blog/10-benefits-of-meditation/).

Quote on the image from Joseph Addison.

## Media
Images where taken from [Unsplash](https://unsplash.com/s/photos/meditate). A big thank you to Silviu Zidaru and Jared Rice who took the photos I used on my site.

Icons where taken from [Font Awesome](https://fontawesome.com/).

The YouTube video content creator is [Goodfull](https://www.youtube.com/c/Goodful).

## Code
I adapted the code for the footer from the [Love Running](https://learn.codeinstitute.net/sandbox/api/challenges/601194c939e147dad663b867/files/signup.html) site by CodeInstitute.

Colours were chosen by [W3School](https://www.w3schools.com/cssref/css_colors.asp).

Fonts were chosen on [GoogleFonts](https://fonts.google.com/)

