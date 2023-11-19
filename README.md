# Photochallenge

![Photoshop shown on a variety of screen sizes](https://ui.dev/amiresponsive?url=https://8000-zarchri-photocallenge-m87xix7nlm4.ws-eu106.gitpod.io/index.html)

Visit the deployed site: [Photochallenge](https://github.com/zarchri/photocallenge/actions/runs/6916105787)

Callenge your self in our photocourses

We have courses both for new beginner and for you who have insperience and want width your wievs. We have also a photocourse for yoy who wants learn you redigering.
Our phototravels is very popular.

[YouGov](https://yougov.co.uk/topics/lifestyle/explore/activity/Pub_quizzes) show that 98% of people surveyed have heard of a pub quiz, and are rated as the 19th most popular social activity.

During lockdowns pub quizzes remained popular - they just changed format to become virtual. This gave me the idea of creating a quiz site that would feel like a pub quiz, where users could play on their own to improve their general knowledge anywhere and at any time.

![GitHub last commit](https://img.shields.io/github/last-commit/kera-cudmore/TheQuizArms?color=red&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/kera-cudmore/TheQuizArms?color=orange&style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/kera-cudmore/TheQuizArms?color=yellow&style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/kera-cudmore/TheQuizArms?color=green&style=for-the-badge)
![W3C Validation](https://img.shields.io/w3c-validation/html?logoColor=blue&style=for-the-badge&targetUrl=https%3A%2F%2Fkera-cudmore.github.io%2FTheQuizArms%2F)

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](n my css file I have used variables to declare colours, and then used these throughout the css file. 
  From the beginning I had a idea about I want it black because I realy like black and white iage and want a black and white image in the homepaige in the end it ended with black header background wit a green touch in the text.

I have used #000000 and 5C8374 as the primary and secondary colours used for the sites text.

I have used #292929 as the overlay used over the sites background image.

I have used #5C8374 for the border-hover effect of the formsection.

I have used #ffffff in the input-text in the formsection.)
  * [Typography](Google Fonts was used to import the chosen fonts for use in the site.)

For the Page Title I have used the google font Oswald. I chooce this font because I want A font who clearly Shows the title on the page.

For the body of the page I have used the google font Lato. Lato is a sans-serif font like the mosy website use, it is a clean and easy to read.

  * [Imagery]
  (-In the home page I want use a picture with a person with a camera so the person get intention.
  -In the gallery I have chosen picture who can interact with the travelgoal we will go to in the different phototravels
  -In the fornmsection I chooce this picture because I want show thee feeling to photographs togheter and get inspiration from each other.)

  * [Wireframes](#wireframes)
  * [Features](The website is comprised of a home page, a games page, a high scores page, a 404 error page & a 500 error page.

All Pages on the website are responsive and have:

A favicon in the browser tab.

favicon

The title of the site at the top of every page. This title also acts as a link back to the home page. The title are: Photochallenge

Every page will display a custom cursor when on a button. This feature is not available on mobile touch devices.)
    * [The Home Page](#the-home-page)
    * [The Game Page](#the-game-page)
    * [The High Scores Page](#the-high-scores-page)
    * [The 404 Error Page](#the-404-error-page)
    * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  * [Solved Bugs](#solved-bugs)
  * [Known Bugs](#known-bugs)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

- - -
![The Quiz Arms Banner](documentation/the-quiz-arms-banner.png)

## User Experience (UX)

### User Stories

#### First Time Visitor Goals

* I want to take part in a pub quiz online and improve my general knowledge. I want to be able to play at any time, anywhere.
* I want the site to be responsive to my device.
* I want the site to be easy to navigate.

#### Returning Visitor Goals

* I want to be able to choose a level of difficulty that I feel is appropriate for me, based on my experience from my first visit to the site.

#### Frequent Visitor Goals

* I want to be able to adjust the difficulty level to keep improving my knowledge.
* I want to be able to log my high scores to see how I am performing.

- - -

## Design

### Colour Scheme

As the pages of the site have a background image, I wanted to keep the colour scheme used on the site quite small so as to not overwhelm users. Red and green  are very typical colours in traditional British public houses, with the red & green used for upholstery.

In my css file I have used black and lightgreen color

* I have used `#000000` & '#5C8374' as the primary and secondary colours used for the sites text.

* I have used #5C8374 in the borders in the formsection.


  ![The Quiz Arms Color Scheme](documentation/color-scheme.webp)

### Typography

Google Fonts was used to import the chosen fonts for use in the site.

* For the Page Title I have used the google font [Oswald](@import url('https://fonts.googleapis.com/css2?family=Lato:ital@1&family=Oswald:wght@200;300;400;500;600;700&family=Satisfy&display=swap');). I chooce satisfy because I want a font who is easy to read for everyone it is clean and clear.

![Almendra Font Example](documentation/almendra.webp)

* For the body of the page I have used the google font [Lato](@import url('https://fonts.googleapis.com/css2?family=Lato:ital@1&family=Oswald:wght@200;300;400;500;600;700&family=Satisfy&display=swap');). 

![Quicksand Font Example](documentation/quicksand.webp)

### Imagery

I use a image who asccioted with photo so I chooce a girl with a camera.

### Wireframes

Wireframes were created for mobile, tablet and desktop using balsamiq.

![Home Page](documentation/wireframes/homewireframe.webp)
![Difficulty Page](documentation/wireframes/difficultywireframe.webp)
![Game Page](documentation/wireframes/gamewireframe.webp)
![High Scores Page](documentation/wireframes/highscorewireframe.webp)

### Features

The website is comprised of a home page, a gallery page and a signup page, a 404 error page & a 500 error page.

All Pages on the website are responsive and have:

* A favicon in the browser tab.

  ![favicon](documentation/favicon-image.webp)

* The title of the site at the top of every page. This title also acts as a link back to the home page.
  ![Photoshop](https://8000-zarchri-photocallenge-m87xix7nlm4.ws-eu106.gitpod.io/index.html)

* Every page will display a custom cursor when on a button. This feature is not available on mobile touch devices.

![Custom Cursor](documentation/features/custom-cursor.gif)

In all page you can fint in the footer contact information: adress, phone, email and social media links

#### The Home Page

The home page of Photochallenge displays the sites name as a title and then a container which holds information about the the courses we hold about what they are container, place, time and amount.

![Home page image](https://8000-zarchri-photocallenge-m87xix7nlm4.ws-eu106.gitpod.io/index.html)



![Modal open image](documentation/features/modal.png)

The play button will redirect the user to the game page to select the difficulty of their quiz and the high Scores button redirects the user to the high scores page.

#### The Gallery Page

The gallery page displays the sites name as a title. This also acts as a link back to the home page. Here can you see photographs from the different country we have travell to and what photoredigering can do, this page is for little inspirations.

![Image of the gallery page difficulty selection buttons](https://8000-zarchri-photocallenge-m87xix7nlm4.ws-eu106.gitpod.io/gallery.html)



![Image of quiz area](documentation/features/quiz.png)

Once a user has answered the 15 questions they will be taken to the end of the game which will allow them to enter their team name and submit it to be entered onto the high scores page if it is in the top 10 scores. The submit button is disabled by default to prevent the user from submitting without a team name. This is made clear to the user as the cursor will show not allowed when hovered over the submit button.

![End of game](documentation/features/end.png)

#### The Signup Page

The Signup page displays the sites name as a title. This also acts as a link back to the home page. In this page can you sign you up to our different courses. 
IN the background have I chooce  a image with happy teenager with a camera in a picknic in the nature.

![Signup Page Image](https://8000-zarchri-photocallenge-m87xix7nlm4.ws-eu106.gitpod.io/signup.html)

#### The 404 Error Page

The 404 error page displays the sites name as a title. This also acts as a link back to the home page. Within the page container there is a sorry message explaining to the user that there has been an error directing them to the page they were looking for. The user is then given a choice of three buttons to redirect them to other pages on the site, the home page, the games page and the high scores page.

![Error page image](documentation/features/404.png)

#### The 500 Error Page

The 500 error page displays the sites names as a title, which also acts as a link back to the home page. Within the container is an error message that tells the user sorry there seems to be an issue retrieving the quiz data. Two buttons for the home page and the high scores page are below. I did not add the play game button here, as a user will been directed to this page if there is an error calling the API.

![500 Error Page](documentation/features/500.png)

#### Future Implementations

In future implementations I would like to:

1. Efford onlines courses.
2. add narrator function for the hearing impaired
3. Expand the gallery page with more pictures and different folders with both pictures taken of objects and people on our trips but also pictures of the participants in the courses
4. Style the homepage more there information about the courses are more clear and conspicuous.

### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. This has been have achieved by:

* Using semantic HTML.
* Using a hover state on all buttons on the site to make it clear to the user if they are hovering over a button.
* Choosing a sans serif font for the site - these fonts are suitable for people with dyslexia.
* Ensuring that there is a sufficient colour contrast throughout the site.

![contrast button](documentation/contrast-btn.png) ![Contrast button hover](documentation/contrast-btn-hover.png) ![contrast text](documentation/contrast-text.png)

As the site relies on colour to display to the user whether an answer is correct or incorrect, I was interested to see what this would look like for someone with red/green colour blindness. I used the chrome extension [Web Disability Simulator](https://chrome.google.com/webstore/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) to be able to see what someone with red/green colour blindness would see.

In a future implementation I think it would be a great accessibility feature to also add a symbol such as a tick or cross on the answer button to enable people who are colour blind to also be able to access the quiz easier. Each of the images below have whether they are correct/incorrect in the name. Can you tell which one is which?

![Colour blindness (red/green) correct answer](documentation/rg-colour-blind-correct.png)
![Colour blindness (red/green) incorrect answer](documentation/rg-colour-blind-incorrect.png)

- - -

## Technologies Used

### Languages Used

HTML, CSS, Javascript

### Frameworks, Libraries & Programs Used

* [Balsamiq](https://balsamiq.com/) - Used to create wireframes.

* [Git](https://git-scm.com/) - For version control.

* [Github](https://github.com/) - To save and store the files for the website.

* [GitPod](https://gitpod.io/) - IDE used to create the site.

* [Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.

* [Pexels](https://www.pexels.com/sv-se/)
Load down images

* [Google Developer Tools](https://developers.google.com/web/tools) - To troubleshoot and test features, solve issues with responsiveness and styling.

* [TinyPNG](https://tinypng.com/) To compress images

* [gimp](redigeringsprogramme) To resize images.

* [Favicon.io](https://favicon.io/) To create favicon.

* [Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

* [Shields.io](https://shields.io/) To add badges to the README







* [Webpage Spell-Check](https://chrome.google.com/webstore/detail/webpage-spell-check/mgdhaoimpabdhmacaclbbjddhngchjik/related) - a google chrome extension that allows you to spell check your webpage. Used to check the site and the readme for spelling errors.

- - -

## Deployment & Local Development

### Deployment

The site is deployed using GitHub Pages - [The Quiz Arms](https://kera-cudmore.github.io/TheQuizArms/).

To Deploy the site using GitHub Pages:

1. Login (or signup) to Github.
2. Go to the repository for this project, [kera-cudmore/TheQuizArms](https://github.com/kera-cudmore/TheQuizArms).
3. Click the settings button.
4. Select pages in the left hand navigation menu.
5. From the source dropdown select main branch and press save.
6. The site has now been deployed, please note that this process may take a few minutes before the site goes live.

### Local Development

#### How to Fork

To fork the repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, [kera-cudmore/TheQuizArms](https://github.com/kera-cudmore/TheQuizArms)
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, [kera-cudmore/TheQuizArms](https://github.com/kera-cudmore/TheQuizArms)
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Testing

Please refer to [TESTING.md](TESTING.md) file for all testing carried out.

### Solved Bugs

| No | Bug | How I solved the issue |
| :--- | :--- | :--- |
| 1 | An error was displaying in the console when next was clicked after the first question, stating that results wasn't defined. | Data was defined in the callApi(), so couldn't be accessed as it was in local scope rather than global scope. By defining data globally and then passing the data as a parameter into the getQuestion() in the nextQuestion() solved this. |
| 2 | The Questions being pulled in from the JSON have HTML entity characters that are not escaped and therefore display incorrectly with symbols in place of the correct characters. ![Characters not escaping correctly in the JSON data](documentation/characters-not-escaped.webp) | After a lot of research into escaping characters, I came across a post on slack that mentioned using innerHTML rather than innerText. Once I changed the answers to innerHTML the characters are now displaying correctly. |
| 3 | I have the local storage set up to save the final score as mostRecentScore. However when completing a game and submitting the team name the score added to the high scores section would be the previous score and not the most recent score. | After a lot of research to try and find out why this was happening I went over the code again and decided to see if I changed mostRecentScore in the scoreLog to score it would make a difference. By changing this, I have solved the issue and it now pulls the most recent score achieved. |
| 4 | Players were able to select an answer which would then display whether correct or incorrect. However they could still click on the answers which meant they could click all the answers to receive the points.| I researched a way to disable the buttons and initially found that I could use answer1.disabled = true; This worked, however it added quite a bit of code, as I had to add this for each button. Further research led me to find [this article](https://blog.revillweb.com/jquery-disable-button-disabling-and-enabling-buttons-with-jquery-5e3ffe669ece) which showed how to use jQuery and the class on the buttons to enable and disable them all at the same time. This then allows me to enable the buttons when a new question has been populated and once a selection has been made, the answer buttons are disabled until the user clicks next to advance onto the next question. |
| 5 | There was an issue with the data-correct not always being removed correctly from questions, which meant that incorrect answers were displaying as correct | I changed the way the data-correct attribute was removed from the answers, by using the same a for loop similar to what was used to add the data-correct attribute. I also changed the for innerText in the for loop to be innerHTML so that it was correctly reading the same as what was displayed on the button. |
| 6 | If a user selected an incorrect answer and the correct answer contained HTML entity characters (such as /&#(\d+);/g) the correct button styling would not be applied to the displayCorrectAnswer variable and a error would display in the console. This would then prevent the user from progressing in the quiz as the next button would not display for them to move on.![Bug 6](documentation/bug-6.png) | I adjusted line 161 to use innerHTML rather than innerText, however the issue persisted. I looked for an answer online but struggled to find anything that would help. I then reached out to Bim Williams on Slack who is an alumni on the course and asked to run the problem past him. He suggested adding a function that would decode the HTML entity and then apply that function within line 161. The function takes the HTML entity characters and replaces them with the correct characters. I will be researching this topic further in my spare time to gain a deeper understanding of it. |

### Known Bugs

* When viewing on screens that use touch rather than a cursor, the colour change for the answer button selected is not immediately obvious as the hover state remains on the button. If the user clicks away from the button the colour can then been seen.

  ![Touch Button Colour](documentation/touch-button-colour.gif)

* There is a a warning displaying in the console on the live page. This error seems to be because GitHub hosted pages disable googles 3rd party cookie alternative FLoC, which then throws this error. The error doesn't affect the site in any way.

  ![Console warning](documentation/interest-cohort-error.png)

* When friends tested the site they found that very rarely a game will get stuck on a question, and it will not populate a new question but the question no counter continues to increase. This issue only seems to be if a large number of games are played consecutively, possibly using up the questions in the API. I have not been able to replicate this issue to troubleshoot further.
  ![Question overloaded](documentation/questions-depleted.gif)

- - -

## Credits

### Code Used

* I used [this You Tube tutorial](https://www.youtube.com/watch?v=XH5OW46yO8I) to learn how to create a modal for the how to play section.

* As the API I used for the questions declared the correct answer and then had an array of incorrect answers, I had to find a way to shuffle the answers together so that the correct answer wouldn't always appear on the same button. Research led me to the Fisher-Yates Shuffle. Other methods of shuffling can favour some items in the array more than others, however the Fisher Yates Shuffle allows for a more even spread of probability of the answer being placed on each button. I used the following [YouTube tutorial](https://www.youtube.com/watch?v=eATLMjs7y4s&list=PL5egNEXQTWmFHAoWFVRLNAvD-9zzyWVxA&index=3) to further adapt the shuffle I had researched on W3Schools to work with the data I had.

As the JavaScript modules of the Code Institute Diploma did not cover local storage, I had to do a bit of research into this topic myself in order to set up the high scores section of my site.

* I used this [video tutorial](https://www.youtube.com/watch?v=DFhmNLKwwGw&list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx&index=9) on YouTube by [James Q Quick](https://www.youtube.com/channel/UC-T8W79DN6PBnzomelvqJYw) which taught me to save the team name and score to an object, that would then be saved into an array in local storage. It also explained how to sort the items in the array into descending score order, and then to splice the array, I have used the MAX_HIGH_SCORES as my point to splice.

* I used this [video tutorial](https://www.youtube.com/watch?v=jfOv18lCMmw&list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx&index=10) on YouTube by [James Q Quick](https://www.youtube.com/channel/UC-T8W79DN6PBnzomelvqJYw) to learn how to insert the local storage into the high scores page.

### Content

All questions for my site were pulled from [The Open Trivia Database](https://opentdb.com/) using their API.

All other content for the site, such as introduction messages and instructions were written by myself.

### Media

[Page background image of a pub](https://pixabay.com/photos/bar-pub-cafe-establishment-stools-2209813/)

### Acknowledgments

I would like to acknowledge the following people:

* Adegbenga  Adeye - My Code Institute Mentor.

* Bim Williams - For being a great sounding board for me when I faced issues with moving onto the next question in the quiz, and for helping solve the issue faced with the HTML entity characters in the answer buttons.

* [Dave Horrocks](https://github.com/daveyjh) - For taking the time to walk through my code with me when I was struggling with adding event listeners.

* [Emanuel Silva](https://github.com/manni8436) - For cheering me on when I was struggling with the JavaScript, and for testing the site.

* [Abi Harrison](https://github.com/Abibubble) - For being a great rubber duck and helping debug, helping to test the site and for sharing her knowledge on accessibility.

* The Code Institute Slack channel Peer Code Review - Thank you to everyone who took the time to play the quiz and look over the code.